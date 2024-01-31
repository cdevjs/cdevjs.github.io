---
layout: page
title: test
permalink: /test/
---



<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CYADEV</title>
    <meta name="description" content="Hello there! This is my personal blog and portifolio">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg bg-body-tertiary ">
            <div class="container-fluid">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-braces-asterisk" viewBox="0 0 16 16">
                <path fill-rule="evenodd" d="M1.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C2.25 2 1.49 2.759 1.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6M14.886 7.9v.164c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456v-1.3c-1.114 0-1.49-.362-1.49-1.456V4.352C14.51 2.759 13.75 2 12.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6M7.5 11.5V9.207l-1.621 1.621-.707-.707L6.792 8.5H4.5v-1h2.293L5.172 5.879l.707-.707L7.5 6.792V4.5h1v2.293l1.621-1.621.707.707L9.208 7.5H11.5v1H9.207l1.621 1.621-.707.707L8.5 9.208V11.5z"/>
              </svg>    
              <a class="navbar-brand p-1" href="#">cyadev.com</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="home">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" data-bs-toggle="modal" data-bs-target="#exampleModal" href="">Contact</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="https://cdevjs.github.io">Blog</a>
                  </li>

                  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                    <div class="modal-dialog">
                      <div class="modal-content">
                        <div class="modal-header">
                          <h1 class="modal-title fs-5" id="exampleModalLabel">My Contact</h1>
                          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                        Hi, if you wanna contact me for a make an budget, you can use this way : Discord: Boes3077.<br> Else, you can use e-mail: cdevpyjs@gmail.com 😊
                        </div>
                        <div class="modal-footer">
                          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                          
                        </div>
                      </div>
                    </div>
                  </div>
                
                </ul>
              </div>
            </div>
          </nav>
    </header>

    <div class="container d-flex justify-content-center" style="margin-top: 9%;">
      <div class="card" style="width: 55%; border-radius: 25px;">
        <div class="card-body">
          <h1 class="text-center">Hello, everyone👋!!!</h1>
          <p class="text-center">This is my personal blog and portfolio!
            <br>
            So, feel free to explore this site!
            <br>
            Thanks for your click! 😉
          </p>
        </div>
      </div>
    </div>
    
    
      
      <footer class="py-3 my-4 fixed-bottom">
        <ul class="nav justify-content-center border-bottom pb-3 mb-3">
          <li class="nav-item"><a href="home" class="nav-link px-2 text-body-secondary">Home</a></li>
          <li class="nav-item"><a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal" class="nav-link px-2 text-body-secondary">Contact</a></li>
          <li class="nav-item"><a href="https://cdevjs.github.io" class="nav-link px-2 text-body-secondary">Blog</a></li>
        </ul>
        <p class="text-center text-body-secondary " id="ph">Made with love by Pedro H 🫶🏻</p>
        <p class="text-center text-body-secondary mb-0">"Your time is limited, don't waste it living someone else's life."</p>
        <p class="text-center text-body-secondary mb-0">Steve Jobs</p>
      </footer>
    
      <script>
        console.log("What are you doing here? 🤨");


// Troca de emoji a cada 5 segundos
const emojis = ['🫶🏻', '❤️', '🚀', '🌟', '🎉']; // Adicione outros emojis se desejar
let index = 0;

function changeEmoji() {
  document.getElementById('ph').innerHTML = `Made with love by Pedro H ${emojis[index]}`;
  index = (index + 1) % emojis.length;
}

setInterval(changeEmoji, 1000);


function soma(a,b){
  return a + b;
}

function afs(){

var num1 = parseFloat(prompt("Type the number"));
var num2 = parseFloat(prompt("Type the second number"));

var res = soma(num1,num2);



console.log(res);

}



function est(){
  console.log("Todos sabem que eu te amo");
};


function div(a,b){
  return a / b;
};



function divs(){
var dum1 = parseFloat(prompt("Type the number"));
var dum2 = parseFloat(prompt("Type the second number"));

var des = div(dum1,dum2);


console.log(des);
};





      </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
</body>
</html>
