# Okaiquelopes.github.io
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CJ - Conselho de Jovens OPOCA</title>
    <link rel="stylesheet" href="css/home.css">
    <link rel="shortcut icon" href="css/img/icone cj.ico" type="image/x-icon">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Oswald:wght@300;400&family=Righteous&family=Sarala:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap');
*{
    margin: 0;
    padding: 0;
    text-decoration: none;
}
html{
    scroll-behavior: smooth;
}
::-webkit-scrollbar{
    width: 10px;
}
::-webkit-scrollbar-track{
    background: #8E5D52;
    border-radius: 30px;
}
::-webkit-scrollbar-thumb{
    background: #2F2325;
    border-radius: 30px;
}
body{
    background: linear-gradient(68.15deg, #2F2325 16.62%, #8E5D52 85.61%);
}
/*section{
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    /*justify-content: center;
    align-items: center;
}*/
/*.conteudo{
    padding: 50px;
    max-width: 1200px;
}*/
.cabecalho{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
}
.cabecalho-menu{
    /*width: 100%;
    height: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    padding: 15px;
    background-color: white;
    border-bottom: 0.2px solid black;
    gap: 100px; */
    display: flex;
    padding: 24px;
    gap: 32px;
    position: fixed;
    border-bottom: 0.4px solid #FFF2E7;
    width: 100%;
    background: linear-gradient(68.15deg, #2f2325a8 16.62%, #8E5D52 85.61%);
}
.cabecalho-item{
    /*font-family: 'Oswald';
    color: black;
    font-weight: 500;
    font-size: 20px;*/
    font-family: 'Sarala', sans-serif;
    color: #FFF2E7;
    font-weight: 400;
    font-size: 18px;
    text-align: center;
    gap: 32px;
    margin: 0 auto;
}
#home{
    display: flex;
    width: 100%;
    margin: 0 auto;
    height: 100vh;
    flex-direction: column;
    align-items: center;
    justify-content: center;

}
#home h1{
    margin-bottom: 15px;
    display: flex;
    /*flex-direction: column;
    gap: 32px;*/
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 30px;
    color: #FFF2E7;
    margin-top: 15px;
}
#home p{
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 14px;
    color: #ecd6c4b4;
}
.img-cj{
    width: 100%;
    justify-content:space-around;
    align-items: center;
    height: 420px;

}
#equipe{
    /*display: flex;
    width: 100%;
    height: 100vh;
    flex-direction: column;
    align-items: center;
    justify-content: center;*/
    max-width: 1200px;
    margin: 0 auto;
}
#equipe h1{
    margin-bottom: 15px;
    display: flex;
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 28px;
    
    color: #FFF2E7;
}
#equipe h2{
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 18px;
    color: #ECD6C4;
}
.card{
    width: 28%;
    display:inline-block;
    margin: 1% 1%;
    padding: 15px;
    margin-top: 15px;
}
.cj-img{
    height: 300px;
    width: 100%;
    margin-bottom: 10px;
    background-position: center;
    background-size: cover;
}
h3{
    margin-bottom: 10px;
    color: #FFF2E7;
    font-size: 24px;
    padding-left: 7px;
    text-align: center;
}
.card p{
    margin-bottom: 10px;
    color: #ECD6C4;
    text-align: center;
}
#img-1{
    background-image: url(img/kaique.png);
    width: 100%;
}
#img-2{
    background-image: url(img/gustavo.png);
    width: 100%;
}
#img-3{
    background-image: url(img/sara.png);
    width: 100%;
}
#img-4{
    background-image: url(img/priscila.png);
    width: 100%;
}
#img-5{
    background-image: url(img/daniel.png);
    width: 100%;
}
#img-6{
    background-image: url(img/augusto.png);
    width: 100%;
}
#sobre{
    display: flex;
    width: 100%;
    height: 100vh;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
#sobre h1{
    margin-bottom: 15px;
    display: flex;
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 28px;
    margin-top: 15px;
    color: #FFF2E7;
}
#sobre p{
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 18px;
    color: #ECD6C4;
}
#acon{
    display: flex;
    width: 100%;
    height: 100vh;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
#acon h1{
    margin-bottom: 15px;
    display: flex;
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 28px;
    margin-top: 15px;
    color: #FFF2E7;
}
#acon p{
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 18px;
    color: #ECD6C4;
}
.bold{
    font-weight: bold;
    font-family: sans-serif;
    color: #ECD6C4;
}
footer{
    /*background-color: black;
    color: white;
    /*border-top: 3px solid #0f642f;
    text-align: center;
    padding: 40px;*/
    padding: 32px;
    border-top: 0.4px solid #FFF2E7;
    color: #ECD6C4;
    text-align: center;
}
  </style>
</head>
<body>
    <header class="cabecalho">
        <nav class="cabecalho-menu">
            <a class="cabecalho-item" href="#home">Home</a>
            <a class="cabecalho-item" href="#acon">Acontecimentos</a>
            <a class="cabecalho-item" href="#equipe">Equipe</a>
            <a class="cabecalho-item" href="#sobre">Sobre</a>
        </nav>
    </header>

    <main class="conteudo">
        <section id="home">
            <h1>Conselho de Jovens Opoca</h1>
            <img class="img-cj" src="css/img/foto na escola.JPG"> 
            <p><i>"Foto exemplar"</i></p><!--foto do cj na tela inicial-->
        </section>

        <section id="acon">
            <h1>Acontecimentos</h1>
            <p><i>aqui vai ter os acontecimentos, podem ser fotos, coisas dos projetos que participamos, oq quisermos</i></p>
        </section>

        <section id="equipe">
            <h1>Equipe</h1>
            <h2>Os conselheiros:</h2>
            <div class="card">
                <div class="cj-img" id="img-1"></div>
                <h3>Kaique Lopes</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>

            <div class="card">
                <div class="cj-img" id="img-2"></div>
                <h3>Gustavo Tomaz</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>

            <div class="card">
                <div class="cj-img" id="img-3"></div>
                <h3>Sara Vitória</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>

            <div class="card">
                <div class="cj-img" id="img-4"></div>
                <h3>Priscila</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>

            <div class="card">
                <div class="cj-img" id="img-5"></div>
                <h3>Daniel Soares</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>

            <div class="card">
                <div class="cj-img" id="img-6"></div>
                <h3>Augusto Tomaz</h3>
                <p>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                    <br>
                    "Aqui vai ficar uma bio" "Aqui vai ficar uma bio"
                </p>
            </div>
        </section>

        <section id="sobre">
            <h1 class="sobre-h1">Sobre o Conselho de Jovens</h1>
            <p class="sobre-p">
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
                <br>
                <i>Aqui vai ter um texto dizendo o que é o conselho de jovens / Aqui vai ter um texto dizendo o que é o conselho de jovens</i>
            </p> <!--aqui vai ficar um texto falando oq é o conselho de jovens-->
        </section>
    </main>

    <footer>
        <p><span class="bold">Conselho de Jovens OPOCA / Observatório Popular Cidade do Anjo </span>&copy; 2022</p>
    </footer>
</body>
</html>
