CODE BREAKERS PROJECT
======================

Scope of the project
---------------------
This is our first project creating from scratch a web page using html css coding and other collaboration tools. 

SECTIONS
==========


Our HTML code so far: 



<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=h1, initial-scale=1.0">
    <title>MyDevTeam</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="Container">
        <header>
            <div class="Logo">
                <h1>Code<span class="title-color">Breakers</span></h1>
            </div>
            <nav>
                <a href="#somos">Somos</a>
                <a href="#equipo">Equipo</a>
                <a href="">
                <button class="button">
                Contáctanos
                </button>
                </a>
            </nav>
        </header><br>
        <section class="section" id="somos">
            <div class="img-container">
                <img src="/img/R-removebg-preview (1).png" alt="">
            </div>
            <div class="flexBox">
                <h2 class="consultores">Consultores tecnológicos</h2>
                <p>Especialistas en desarrollo web</p><br>
                <button class="button-1">
                    Te llamamos
                </button>
            </div>
        </section>
        <section class="card" id="equipo">
            <article class="card-item">
                <div class="card-content">
                    <figure class="card-picture">
                        <img src="/img/oscar.png" alt="Oscar">
                    </figure>
                    <div class="card-texts">
                        <h3 class="card-title">Oscar Heredia</h3>
                        <p class="card-job">Especialista en desarrollo web</p>
                        <a class="link" href=""></a>
                    </div>
                </div>
            </article>    
            <article class="card-item">
                <div class="card-content">
                    <figure class="card-picture">
                        <img src="/img/Aneeb.jpg" alt="Aneeb">
                    </figure>
                    <div class="card-texts">
                        <h3 class="card-title">Aneeb</h3>
                        <p class="card-job">Especialista en desarrollo web</p>
                        <a class="link" href=""></a>
                    </div>
                </div>
            </article>    
            <article class="card-item">
                <div class="card-content">
                    <figure class="card-picture">
                        <img src="/img/Esther.jpg" alt="Esther">
                    </figure>
                    <div class="card-texts">
                        <h3 class="card-title">Esther Reyes</h3>
                        <p class="card-job">Especialista en desarrollo web</p>
                        <a class="link" href=""></a>
                    </div>
                </div>
            </article>    
            <article class="card-item">
                <div class="card-content">
                    <figure class="card-picture">
                        <img src="/img/Vanessa.jpg" alt="Vanessa">
                    </figure>
                    <div class="card-texts">
                        <h3 class="card-title">Vanessa Cariñena</h3>
                        <p class="card-job">Especialista en desarrollo web</p>
                        <a class="link" href="">
                </div>
            </article>    
        </section>
</body>
</html>

<br>

And this is our  CSS so far:

/* reset default */
@font-face {
    font-family: jost;
    src: url(/Font/Jost-Medium.ttf);
}
* {
    box-sizing: border-box; 
    margin: 0;
    padding: 0;
}
body {
    font-family: jost;
    margin: 0;
    padding: 0;
}

header {
    background-color: #FF7F99 ;
    color: white;
    height: 100px;
    padding: 30px;

    /* flexBox */
    display: flex;
    justify-content: space-between;
    align-items: center;

    flex-direction: row;
    flex-wrap: nowrap;
}
header nav {
    /* flexBox*/
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}

header nav a {
    padding: 14px 15px;
    color: white;
    display: flex;
    text-align: center;
    text-decoration: none;
    /*flexbox*/
    flex-grow: 1;
    flex-wrap: wrap;
}
 .title-color {
    color: #FFCA41;
 }

.button{
    font-size: 16px;
    color: white;
    border-radius: 60px;
    background-color: #ffc34150;
    border: 15px #ffc341ec;
    height: 30px;
    width: 100px
}
.section {
    display: flex;
    padding: 150px;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    margin: auto;
}
.img-container {
    width: 300px;
    height: 300px;
    border-radius: 150px 0px 150px 150px;
    background-color: #FF7F99;
    overflow: hidden ;
    /*flexbox*/
    display: flex; 
}
.img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
}
.flexBox {
    display: flex;
    padding: 80px;
    flex-direction: column;
}
.consultores {
    font-size: 50px;
    color: #FF7F99;
}
.button-1{
    font-size: 15px;
    color: white;
    border-radius: 60px;
    background-color: #FFCA41;
    border: 15px #ffc341ec;
    height: 30px;
    width: 100px
} /*Codigo de la letra Te llamamos*/
.card{
    background-color: #FF7F99;
    width: 100% ;
    margin: auto;
    padding: 60px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-wrap: wrap;
}
.card-content {
    display: flex;
    padding: 10px;
    flex-wrap: wrap;
    align-items: center;
    flex-direction: column;
    margin: auto; 
}
.card-picture {
    width: 277px;
    height: 277px;
    max-width: 1200px;
    border-radius: 277px;
    display: flex;
    overflow: hidden;  
    object-fit: cover;
    justify-content: center;
    }

.card-texts {
    text-align: center;
    padding: 25px;
}
.card-title {
    font-size: 25px;
    color: antiquewhite;
    
}

LINKS
=====

http://127.0.0.1:5500
