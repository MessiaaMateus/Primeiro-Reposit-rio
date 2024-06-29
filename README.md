<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <styles>
        * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #dcdcdc;
  }
  body {
      background-color: #101728;
      padding-bottom: 0%;
  }
  .all {
      display: flex;
      height: 600px;
      width: 100%;
      align-items: center;
      border-bottom: 3px solid rgb(2, 214, 129);
  }
  .section {
      height: 600px;
      width: 100%;
      border-bottom: 3px solid rgb(2, 214, 129);
  }
  #header-fixed {
      position: relative;
      box-shadow: 0 5px 100px #080b14;
      position: fixed;
      top: 0;
      z-index: 9;
      background-color: #21293D;
      height: 80px;
      width: 100%;
  }
  #nav-bar-items {
      position: absolute;
      right: 50px;
      top: 8px;
  }
  .fa-house, .fa-user, .fa-envelope, .fa-comment {
      color: #ffffff;
      font-size: 17px;
  }
  #curriculum button {
      border: 2px solid rgb(0, 255, 153);
      background-color: #21293D;
      height: 55px;
      width: 120px;
      margin: 13px 3rem ;
      border-radius: 8px;
      cursor: pointer;
  }
  #curriculum button:hover {background-color: rgb(2, 214, 129);}
  #curriculum a {text-decoration: none;}
  #curriculum h4 {
      color: #fff;
      font-size: 15px;
  }
  #nav-bar-items li {
      list-style: none;
      cursor: pointer;
      border-radius: 50%;
      padding: 10px 12px;
      margin: 8px;
      display: inline-block;
      border: 2px solid rgb(0, 255, 153);
  }
  #nav-bar-items li:hover {background-color: rgb(2, 214, 129);}
  #apresentation {
      margin-left: 6rem;
      margin-top: 80px;
      padding-top: 70px;
  }
  .name {
      margin-bottom: 25px;
      width: 12%;
      font-size: 30px;
      font-weight: bold;
      line-height: 40px;
      transition: transform 0.2s ease-in-out;
      cursor: context-menu;
  }
  .name:hover {
      transform: scale(1.1);
  }
  .info {
      padding-bottom: 25px;
      width: 30%;
  }
  .info p {
      font-size: 17px;
      font-weight: 500;
      letter-spacing: 0.5;
      color: #dcdcdc;
      transition: transform 0.2s ease-in-out;
      cursor: context-menu;
  }
  .info p:hover {
      transform: scale(1.1);
  }
  .p {padding-bottom: 20px;}
  .void {
      height: 20px;
      width: 300px;
      border-top: 2px solid rgb(1, 255, 153);
  }
  .contact-me {
      width: 350px;
      font-size: 17px;
      font-weight: 500;
      color: #dcdcdc;
  }
  .contact-me p {
      transition: transform 0.2s ease-in-out;
      cursor: context-menu;
  }
  .contact-me p:hover {
      transform: scale(1.1);
  }
  .contact-me a button {
      height: 60px;
      width: 200px;
      border-radius: 30px;
      border: none;
      background-color: rgb(0, 218, 131);
      color: #ffffff;
      font-size: 17px;
      font-weight: bold;
      padding-bottom: 4px;
      margin-top: 25px;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
  }
  .contact-me a button:hover {
      background-color: rgb(1, 255, 153);
      transform: scale(1.1);
  }
  #image-me1 img {
      height: 450px;
      width: 450px;
      border-radius: 50%;
      background-position: center;
      background-size: cover;
      border: 8px solid #101728;
      outline: 5px solid rgb(1, 255, 153);
      opacity: 0.9;
      transition: transform 0.5s ease-in-out;
  }
  #image-me1 {
      display: flex;
      position: absolute;
      top: 9rem;
      right: 13rem;
      z-index: 1;
      background-color: #080b14;
      border-radius: 50%;
  }
  #image-me1 img:hover {
      opacity: 1;
      transform: scale(1.1);
  }
  .decoration-container {
      position: absolute;
      height: 677px;
      width: 32%;
      background-color: rgb(1, 255, 153);
      right: 0;
      top: 0;
  }
  .description-father {
      position: relative;
      height: 100%;
      width: 100%;
      background-image: url(../img/espaço1.avif);
      background-position: center;
      background-size: cover;
  }
  .description-son {
      position: absolute;
      right: 5rem;
      top: 10rem;
      width: 50%;
      font-weight: 500;
      text-align: center;
  }
  .description-son h2 {
      margin-bottom: 40px;
      font-size: 40px;
  }
  .description-son p {font-size: 18px;}
  .important-word {color: rgb(1, 255, 153);}
  .center-container {
      display: flex;
      height: 500px;
      width: 100%;
      background-color: #21293D;
  }
  .brief {
      width: 50%;
      font-size: 22px;
      color: #dcdcdc;
      font-weight: 500;
      font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      line-height: 30px;
      padding: 0 40px 0 100px;
  }
  .brief p {text-align: start;}
  .brief h2 {
      font-size: 40px;
      padding-bottom: 70px;
      padding-top: 60px;
      color: rgb(1, 255, 153);
  }
  .image-me2 {
      display: inline-block;
      height: 400px;
      width: 450px;
      margin: auto 80px auto 80px;
  }
  .image-me2 img {
      height: 400px;
      width: 450px;
      border-radius: 20px;
      background-size: cover;
      background-position: center;
  }
  .image-me3 {
      display: inline-block;
      height: 400px;
      width: 450px;
      margin: auto 80px auto 80px;
  }
  .image-me3 img {
      height: 400px;
      width: 450px;
      border-radius: 20px;
      background-size: cover;
      background-position: center;
  }
  ::-webkit-scrollbar {
      background-color: #21293D;
      border: 2px solid #13192c25;
  }
  ::-webkit-scrollbar-thumb {
      background-color: #101728;
      border-radius: 20px;
      height: 100px;
      border: 2px solid rgb(1, 255, 153);
  }
  ::-webkit-scrollbar-button:single-button:increment {
      background-image: url(../img/setadown.png);
      background-position: center;
      background-size: cover;
  }
  ::-webkit-scrollbar-button:single-button:decrement {
      background-image: url(../img/setaup.png);
      background-position: center;
      background-size: cover;
  }
  .description-father2 {
      position: relative;
      height: 100%;
      width: 100%;
      background-image: url(../img/espaço2.avif);
      background-position: center;
      background-size: cover;
  }
  #section-works {
      padding-bottom: 80px;
      margin-top: 50px;
      border-bottom: 3px solid rgb(1, 255, 153);
  }
  #section-works h2 {
      color: rgb(1, 255, 153);
      font-size: 40px;
      text-align: center;
  }
  .works {
      display: flex;
      justify-content: space-around;
      align-items: center;
      width: 90%;
      height: 500px;
      margin: 20px auto;
  }
  .project {
      width: 300px;
      height: 400px;
      background-color: #21293D;
      border-radius: 20px;
      position: relative;
  }
  #see-more button {
      background-color: rgb(0, 218, 131);
      color: #fff;
      height: 50px;
      width: 200px;
      border: none;
      border-radius: 8px;
      font-size: 17px;
      font-weight: 500;
      cursor: pointer;
  }
  #see-more button:hover {background-color: rgb(1, 255, 153);}
  #see-more {text-align: center;}
  .soon {
      position: absolute;
      transform: rotate(-35deg);
      background-color: #101728;
      height: 60px;
      width: 138%; 
      top: 170px;
      left: -58px;
  }
  .soon h4 {
      text-align: center;
      font-size: 20px;
      padding-top: 12px;
  }
  .section-skills {
      display: flex;
      position: relative;
      justify-content: center;
      align-items: center;
      height: 1066px;
      width: 100%;
      border-bottom: 3px solid rgb(1, 255, 153);
  }
  .section-skills h2 {
      position: absolute;
      font-size: 40px;
      top: 50px;
      color: rgb(0, 255, 153);
  }
  .skills {
      padding-top: 50px;
      display: flex;
      justify-content: space-around;
      margin-top: 500px;
      flex-wrap: wrap;
      gap: 80px;
      /* background-color: #080b14; */
      height: 80%;
      width: 90%;
      margin: auto ;
  }
  .skill {
      height: 140px;
      width: 390px;
      background-color: #080b14;
      border-radius: 8px;
  }
  .porcent1 {width: 300px;}
  .porcent2 {width: 240px;}
  .porcent3 {width: 50px;}
  .porcent4 {width: 50px;}
  .porcent5 {width: 50px;}
  .porcent6 {width: 50px;}
  .porcent7 {width: 50px;}
  .porcent8 {width: 50px;}
  .porcent {
      height: 25px;
      /* width: 50px; */
      background-color: rgb(0, 255, 153);
      border-radius: 8px;
  }
  .skill h3, .porcent {
      margin-left: 40px;
      margin-top: 20px;
  }
  .skill h3 {font-size: 30px;}
  #footer-section {
      display: flex;
      position: relative;
      align-items: end;
      justify-content: start;
      height: 600px;
      width: 100%;
  }
  #thanks {
      position: absolute;
      top: 20%;
      left: 24%;
      font-size: 3rem;
  }
  #thanks h2 {color: rgb(1, 255, 153);}
  #footer-container {
      position: relative;
      display: flex;
      height: 300px;
      width: 100%;
      background-color: #21293D;
  }
  #more-info h2 {
      font-size: 35px;
      margin-top: 30px;
  }
  #more-info p {
      font-size: 18px;
      margin-top: 15px;
      width: 500px;
      font-weight: 500;
      color: #c2c2c2;
  }
  #more-info {
      width: 50%;
      margin-left: 18px;
  }
  #opnion h2 {
      font-size: 35px;
      margin-bottom: 25px;
  }
  #your-opnion {
      position: absolute;
      right: 180px;
      top: 10%;
      font-weight: 500;
  }
  #your-opnion textarea {
      border: none;
      height: 141px;
      width: 244px;
      border-radius: 30px;
      background-color: #101728;
  }
  #your-opnion input {
      position: absolute;
      height: 45px;
      width: 100px;
      margin-left: 20px;
      margin-top: 90px;
      background-color: rgb(1, 201, 121);
      border: none;
      border-radius: 7px;
      color: #fff;
      font-weight: 500;
      font-size: 15px;
  }
  #your-opnion input:hover {
      background-color: rgb(0, 255, 153);
  }
  #your-opnion textarea::placeholder {
      color: #5f6578;
      font-weight: 400;
      font-style: italic;
      padding: 10px 0 0 10px;
  }
  #social-medias {
      position: absolute;
      left: 20px;
      bottom: 30px;
  }
  #social-medias li {
      list-style: none;
      display: inline-block;
      padding: 5px 20px 0 0;
  }
  .fa-brands {font-size: 25px;}
  .fa-brands:hover {color: #fff;}
  /* ANIMAÇÕES */
  /* RESPONSIVIDADE */
  @media screen and (max-width: 600px) {
      .section {
          height: 1000px;
      }
      .center-container {
          display: block;
      }
  }
    </styles>
    <link rel="icon" type="image" href="./img/avatar.png">
    <script src="./js/script.js"></script>
    <title>Mateus Messias Front-Developer</title>
</head>
<body>
    <div id="main-container">
        <header id="header-fixed">
            <div id="curriculum"><button><a href="https://acrobat.adobe.com/id/urn:aaid:sc:va6c2:1b0742a9-e758-4104-90af-b12e57fbf971">
                <h4>Curriculo</h4></a></button>
            </div>
            <nav id="nav-bar-items">
                <ul>
                    <a href="#main-container"><li><i class="fa-solid fa-house"></i></li></a>
                    <a href="#about-me"><li><i class="fa-solid fa-user"></i></li></a>
                    <a href="#section-works"><li><i class="fa-solid fa-envelope"></i></li></a>
                    <a href="#footer-section"><li><i class="fa-solid fa-comment"></i></li></a>
                </ul>
            </nav>
        </header>
        <main>
            <section class="section">
                <div id="apresentation">
                    <div class="name">
                        <h1>Mateus Messias</h1>
                    </div>
                    <div class="void"></div>
                    <div class="info">
                        <p class="p">Desenvolvedor Front end e entusiasta da área de técnologia.</p>
                        <p>Sempre buscando aprendizado e conhecimento para uma carreira de sucesso!</p>
                    </div>
                    <div class="void"></div>
                    <div class="contact-me">
                        <p>Se quiser conversar, clique no botão abaixo para falar comigo!</p>
                        <a href="https://wa.me/5519997132642?text=Olá+Mateus,+tudo+bem?+"><button>Fale comigo</button></a>
                    </div>
                </div>
                <div class="decoration-container">
                    <div id="image-me1"><img src="./img/eu3.jpeg" alt="primeira foto minha"></div>
                </div>
            </section>
            <article class="section">
                <div class="description-father">
                    <div class="description-son">
                        <h2>Sou um <span class="important-word">Internauta</span> do mundo da T.I que sempre busca saber e conhecer</h2> 
                        <p>
                            Desenvolvedor Front End assíduo nos estudos e apaixonado por programação, sempre 
                            buscando saber e conhecer novas tecnologias com ênfase na prática e aprimoramento
                            de suas habilidades, destancando-se pela genuína vontade de entender como funciona
                            o mundo por trás dos computadores!
                        </p>
                    </div>
                </div>
            </article>
            <section class="all" id="about-me">
                <div class="center-container">
                    <div class="brief">
                        <h2>Sobre mim</h2>
                        <p> 
                            Prazer! Me chamo Mateus, tenho 18 anos e moro na cidade de Campinas São Paulo, sou um estudante 
                            do colégio Cotuca, atualmente cursando eletrônica. <br><br>
                            Sou uma pessoa extrovertida que gosta de conversar e trocar experiências! Prezo muito pelo
                            respeito e honestidade visando sempre ter um vida coerente aos valores cristãos.
                        </p>
                    </div>
                    <div class="image-me2"><img src="./img/eu1.jpg" alt="segunda foto minha"></div>
                </div>
            </section>
            <section class="all">
                <div class="center-container">
                    <div class="image-me3"><img src="./img/eu2.jpeg" alt="terceira foto minha"></div>
                    <div class="brief">
                        <h2>Um pouco mais sobre</h2>
                        <p> 
                            Adoro exatas, com ênfase na área da T.I e computação, procuro me desenvolver nesta
                            área por conta, pois tenho grande interesse de um dia me tornar um especialista no assunto.<br><br> 
                            Sou uma pessoa comunicativa com um espírito forte de liderança, procuro sempre tratar 
                            todos bem e ser gentil! Contudo sempre fui uma pessoa muito animada e otimista. 
                        </p>
                    </div>
                </div>
            </section>
            <article class="section">
                <div class="description-father2">
                    <div class="description-son">
                        <h2>Sou um jovem <span class="important-word">Interessado</span> e focado que corre atras de seus objetivos</h2> 
                        <p>
                            Gosto de fazer as coisas acontecerem, sendo uma pessoa focada nos objetivos e
                            com responsabilidade, tenho sempre grande interesse em aprender e desenvolver 
                            projetos. Além de tudo procuro sempre o aprendizado por meio de experiencias e
                            fortes vivencias, pois é onde eu acredito que se encontra o maior dos conhecimentos!
                        </p>
                    </div>
                </div>
            </article>
            <section id="section-works">
                <h2>Projetos</h2>
                <div class="works">
                    <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div>
                    <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div>
                    <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div>
                    <!-- <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div>
                    <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div>
                    <div class="project">
                        <div class="soon"><h4>Em Breve</h4></div>
                    </div> -->
                </div>
                <div id="see-more"><a href="#"><button>Ver mais</button></a></div>
            </section>
            <section class="section-skills">
                <h2>Skills</h2>
                <div class="skills">
                    <div class="skill1 skill">
                        <h3>HTML 5</h3>
                        <div class="porcent1 porcent"></div>
                    </div>
                    <div class="skill2 skill">
                        <h3>CSS 3</h3>
                        <div class="porcent2 porcent"></div>
                    </div>
                    <div class="skill3 skill">
                        <h3>JAVASCRIPT</h3>
                        <div class="porcent3 porcent"></div>
                    </div>
                    <div class="skil4 skill">
                        <h3>REACT</h3>
                        <div class="porcent4 porcent"></div>
                    </div>
                    <div class="skill5 skill">
                        <h3>NODE JS</h3>
                        <div class="porcent5 porcent"></div>
                    </div>
                    <div class="skill6 skill">
                        <h3>MY SQL</h3>
                        <div class="porcent6 porcent"></div>
                    </div>
                    <div class="skill7 skill">
                        <h3>TYPESCRIPT</h3>
                        <div class="porcent7 porcent"></div>
                    </div>
                    <div class="skill8 skill">
                        <h3>ANGULAR</h3>
                        <div class="porcent8 porcent"></div>
                    </div>
                </div>
            </section>
        </main>
        <footer id="footer-section">
            <div id="thanks">
                <h2>Obrigado pela visita!</h2>
            </div>
            <div id="footer-container">
                <div id="more-info">
                    <h2>Para mais informações</h2>
                    <p>
                        Acompanhe minha carreira pelas minhas redes sociais! <br/>
                        Adoraria ajudar em projetos, mande uma mesnagem! 😁😎 <br/> <br/>
                        (19) 99713-2642 <br/>
                        mateusmessias.upnet@gmail.com
                    </p>
                </div>
                <div id="social-medias">
                    <ul>
                        <li>
                          <a href="https://www.instagram.com/mateuzz_055/"><i class="fa-brands fa-instagram"></i></a>
                        </li>
                        <li>
                          <a href="https://www.facebook.com/mateus.messiasdasilva.5/friends/"><i class="fa-brands fa-facebook"></i></a>                          </li>
                        <li>
                          <a href="https://github.com/MessiaaMateus"><i class="fa-brands fa-github"></i></a>
                        </li>
                        <li>
                          <a href="https://www.linkedin.com/in/mateus-messias-06715b264/"><i class="fa-brands fa-linkedin"></i></a>
                        </li>
                    </ul>
                </div>
                <div id="your-opnion">
                    <form action="#">
                        <div id="opnion">
                            <h2>O que você achou?</h2>
                        </div>
                        <textarea 
                        name="comentário" 
                        id="comment"
                        placeholder="Deixe aqui seu comentário sobre o que você achou do site!"
                        ></textarea>
                        <input type="submit" />
                    </form>
                </div>
            </div>
        </footer>
    </div>
</body>
</html>
