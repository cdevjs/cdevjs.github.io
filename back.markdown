---
layout: page
title: Back to the site
permalink: /back/
---


<body>

    <h1>Seu endereço IP é:</h1>
    <p id="ip"></p>

    <script>
        // Função para obter o endereço IP
        function getIP(callback){
            fetch('https://api64.ipify.org?format=json')
            .then(response => response.json())
            .then(data => callback(data.ip))
            .catch(error => callback('Erro ao obter o IP.'));
        }

        // Atualiza o elemento HTML com o endereço IP
        function updateIP(ip){
            document.getElementById('ip').innerText = ip;
        }

        // Chama a função para obter e exibir o IP
        getIP(updateIP);
    </script>
</body>



