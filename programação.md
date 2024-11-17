## ![html-5](https://github.com/user-attachments/assets/db7c6936-4b66-43cf-84ec-904ade06b20b)  **index.html**:

```
<!DOCTYPE html>
  <html lang="pt-br">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Porfólio - Carlos Possi</title>
      <link rel="stylesheet" href="./styles/style.css">
  </head>
  <body>
      <header class="cabecalho">
          <div class ="cabecalho__titulo">
              <h3> Carlos Augusto Possi</h3>
          </div>
          <nav class="cabecalho__menu"> 
              <a class="cabecalho__menu__link" href="index.html">Home</a>
              <a class="cabecalho__menu__link" href="about.html">Sobre mim</a>
              <a class="cabecalho__menu__link" href="contato.html">Contato</a>
          </nav>
      </header>
      <main class="conteudo">
          <section class="conteudo__paragrafo">
              <p class="conteudo__paragrafo_inicio">[QUEM SOU EU?]</p>
              <h1 class="conteudo__paragrafo_final">Sou um estudante em busca de Conhecimento e Aperfeiçoamento no Desenvolvimento Front-end.</h1>
          </section>
          <img class="imagem"src="./assets/Design sem nome.png" alt="Foto do Carlos Possi (Programador)">
      </main>
      <footer></footer>
  </body>
  </html>
```
<br>

## ![html-5](https://github.com/user-attachments/assets/db7c6936-4b66-43cf-84ec-904ade06b20b)  **about.html**:

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Porfólio - Carlos Possi</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header class="cabecalho">
        <div class ="cabecalho__titulo">
            <h3> Carlos Augusto Possi</h3>
        </div>
        <nav class="cabecalho__menu"> 
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="about.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
        </nav>
    </header>
    <main class="conteudosobre">
        <section class="conteudo_sobremim">
            <h1 class="conteudo__sobremim__titulo">Sobre mim: </h1>
            <p class="conteudo__sobremim__texto">
                Sou aluno de Engenharia da Computação na FIAP, tenho 20 anos e estou muito empolgado com o aprendizado e os desafios dessa área. 
                <br>
                A faculdade tem me proporcionado uma base sólida tanto em teoria quanto em práticas de desenvolvimento e inovação tecnológica. 
                <br>
                Desde que entrei no curso, meu interesse por tecnologias emergentes e soluções inovadoras só aumentou, especialmente nas áreas de Inteligência Artificial, Internet das Coisas e Sistemas Distribuídos. 
                <br>
                Além disso, sou fascinado pelo impacto da tecnologia na sociedade e busco sempre explorar como ela pode ser usada de forma sustentável e responsável. 
                <br>
                Tenho me envolvido em vários projetos acadêmicos, e tenho certeza de que, com o tempo, vou conseguir contribuir para transformar grandes ideias em realidade.
            </p>
            <br>
            <br>
            <h1 class="conteudo__sobremim__titulo">Linguagens Dominadas:</h1>
        
            <div class="conteudo__linguagens">
                <img src="./assets/python.png" onmouseover="this. src='./assets/python (1).png'" onmouseout="this. src='./assets/python.png'" alt="Icone do Python">
                <img src="./assets/c-logo.png" onmouseover="this. src='./assets/c-logo (1).png'" onmouseout="this. src='./assets/c-logo.png'" alt="Icone do C++">
                <img src="./assets/html.png" onmouseover="this. src='./assets/html (1).png'" onmouseout="this. src='./assets/html.png'" alt="Icone do HTML">
                <img src="./assets/css-3.png" onmouseover="this. src='./assets/css-3 (1).png'" onmouseout="this. src='./assets/css-3.png'" alt="Icone do CSS">
            </div>
        </section>
        <img class="imagem"src="./assets/Design sem nome.png" alt="Foto do Carlos Possi (Programador)">
    </main>
</body>
</html>
```
<br>

## ![html-5](https://github.com/user-attachments/assets/db7c6936-4b66-43cf-84ec-904ade06b20b)  **contato.html**:

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Porfólio - Carlos Possi</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header class="cabecalho">
        <div class ="cabecalho__titulo">
            <h3> Carlos Augusto Possi</h3>
        </div>
        <nav class="cabecalho__menu"> 
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="about.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
        </nav>
    </header>
    <main class="redes">
        <section class="redes__conteudo">
            <a class="redes__link" href="mailto:cmp.1a.carlos.possi393@gmail.com">
                <img src="./assets/gmail (2).png" onmouseover="this. src='./assets/gmail (1).png'" onmouseout="this. src='./assets/gmail (2).png'" alt="Icone do Gmail">
                Gmail
            </a>
            <a class="redes__link" href="https://www.instagram.com/carlospossi/">
                <img src="./assets/instagram (2).png" onmouseover="this. src='./assets/instagram (3).png'" onmouseout="this. src='./assets/instagram (2).png'" alt="Icone do Instagram">
                Instagram
            </a>
            <a class="redes__link" href="https://github.com/CarlosPossi">
                <img src="./assets/github (1).png" onmouseover="this. src='./assets/github (2).png'" onmouseout="this. src='./assets/github (1).png'" alt="Icone do GitHub">
                GitHub
            </a>
            <a class="redes__link" href="https://www.linkedin.com/in/carlos-augusto-possi/">
                <img src="./assets/linkedin (1).png" onmouseover="this. src='./assets/linkedin (2).png'" onmouseout="this. src='./assets/linkedin (1).png'" alt="Icone do Linkedin"> 
                Linkedin
            </a>
        </section>
        <img class="imagem"src="./assets/Design sem nome.png" alt="Foto do Carlos Possi (Programador)">
    </main>
</body>
</html>
```
<br>

## ![css-3](https://github.com/user-attachments/assets/293bc2c5-ffe8-4f4d-817e-c8d2a12e15c4) **style.css**
```
@import url('https://fonts.googleapis.com/css2?family=Geist+Mono:wght@100..900&family=Lexend:wght@100..900&family=Raleway:ital,wght@0,100..900;1,100..900&family=Roboto+Slab:wght@100..900&display=swap');

* {
    margin: 0%;
    padding: 0%;
}

.cabecalho{
    display: flex;
    justify-content: space-between;
    margin: 4% 12% 0% 6%; 
}

.cabecalho__titulo {
    width: 9%;
    display: flex;
    text-align:center;
    font-family:"Roboto Slab", serif;
    font-size: 15px;
    font-weight: 500;
}

.cabecalho__menu {
    display: flex;
    align-items: center;
    gap: 100px;
}

.cabecalho__menu__link {
    text-decoration: none;
    font-family: "Raleway", sans-serif;
    font-size: 15px;
    font-weight: 800;
    color: #000000;
}

.conteudo {
    width: 90%;
    display: flex;
    justify-content:space-between;
    gap: 1%;
    margin: 0% 0% 0% 6%;
}

.conteudo__paragrafo {
    display: flex;
    align-self: flex-end;
    flex-direction: column;
}

.conteudo__paragrafo_inicio {
    color: #272727;
    font-family:"Geist Mono", monospace;
    font-size: 14px;
    font-weight: 700;
}
.conteudo__paragrafo_final {
    width: 63%;
    color: #000000;
    font-family: "Lexend", sans-serif;
    font-size: 49px;
    font-weight: 650;
}

.cabecalho__menu__link:hover {
    text-decoration-line: underline; 
    text-decoration-color: #000000;
    text-decoration-thickness: 3px;
    text-decoration-line: solid;
}


.conteudosobre{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0% 4%;
    gap: 90px;
}

.conteudo__sobremim {
    display: flex;
    flex-direction: column;
}

.conteudo__sobremim__titulo {
    width: 100%;
    color: #000000;
    font-family: "Raleway", sans-serif;
    font-size: 30px;
    font-weight: 500;
    text-align: center;
}

.conteudo__sobremim__texto {
    width: 80%;
    margin: 1% 10%;
    color: #686D76;
    font-family:"Geist Mono", monospace;
    font-size: 20px;
    font-weight: 300;
    text-align: center;
}

.conteudo__linguagens {
    width: 40%;
    margin: 1% 29.5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.redes {
    margin: 0% 0% 0% 26%;
    display: flex;
    gap: 300px;
    align-items: center;
}

.redes__conteudo {
    display: flex;
    flex-direction: column;
    justify-content:space-between;
    gap: 40px;
    align-items: center;
}

.redes__link{
    width: 70%;
    display: flex;
    text-decoration: none;
    color:#000000;
    font-family: "Raleway", sans-serif;
    font-size: 20px;
    font-weight: 500;
    gap: 10px;
    align-items: center;
    border: solid #000000;
    padding: 15px 80px;
    border-radius: 10px;
}

.redes__link:hover {
    background-color: #EEEEEE;
}

.conteudo__paragrafo_inicio:hover{
    transition: 1s ease;
    color: #6A7EFC;
}

.conteudo__paragrafo_final:hover {
    transition: 1s ease;
    color: #FF5656;
}

*:hover {
    cursor: pointer;
}
```
