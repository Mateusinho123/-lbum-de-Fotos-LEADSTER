<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Álbum de Fotos Responsivo-Tarefa Empresa LEADSTER</title>
    <style type="text/css">
        body {
            margin: 0px;
            background-color: orangered;
            color: gray;
        }
        #rolagem {
            height: 720px;
            margin-bottom: 10px;
            width: auto;
            margin-left: auto;
            margin-right: auto;
            text-align: center;
            overflow: hidden;
        }
        .caixa-miniatura {
            border: 1px solid greenyellow;
            width: 100px;
            display: inline-block;
            margin-left: 2px;
            margin-right: 2px;
            padding: 0px;
            overflow: hidden;
            height: 57px;
        }
        #miniaturas {
            text-align: center;
            position: fixed;
            bottom: 0px;
            margin-left: auto;
            margin-right: auto;
            left: 0px;
            right: 0px;
            border-top: thin solid gray;
            padding-top: 10px;
            padding-bottom: 10px;
            background-color: blue;
        }
        header {
            text-align: center;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-color: black;
            color: white;
        }
        footer {
            background-color: greenyellow;
        }
        @media screen and (max-width: 768px) {
            section, aside {
                width: 100%;
                padding: 0;
            }
        }
        @media screen and (max-width: 600px) {
            nav div#miniaturas  {
                float: none;
                text-align: center;
            }
        }
        @media screen and (max-width: 600px) {
            nav #img1  {
                float: none;
                text-align: center;
            }
        }
        @media screen and (max-width: 600px) {
            nav #img2 {
                float: none;
                text-align: center;
            }
        }
        @media screen and (max-width: 600px) {
            nav #img3  {
                float: none;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        MEU BELO ÁLBUM DE FOTOS
    </header>
    <div id="rolagem">
        <!--<img src="Amor.jpeg"--> <img src="https://images.pexels.com/photos/2014422/pexels-photo-2014422.jpeg" width="1280" height="720" id="img1">
        <!--img src="Life.jpeg"--> <img src="https://images.pexels.com/videos/2499611/free-video-2499611.jpg" width="1280" height="720" id="img2">
        <!--img src="best.jpeg"--> <img src="https://images.pexels.com/videos/1448735/free-video-1448735.jpg" width="1280" height="720" id="img3">
        <!--<h1>Imagens grandes aqui</h1>-->
    </div>
    <div id="miniaturas">
        <div class="caixa-miniatura"><a href="#img1"><!--<img src="Amor.jpeg"--><img src="https://images.pexels.com/photos/2014422/pexels-photo-2014422.jpeg" width="100" height="57" alt=""/></a>Miniatura 1</div>
        <div class="caixa-miniatura"><a href="#img2"><!--<img src="Life.jpeg"--><img src="https://images.pexels.com/videos/2499611/free-video-2499611.jpg" width="100" height="57" alt=""/></a>Miniatura 2</div>
        <div class="caixa-miniatura"><a href="#img3"><!--img src="best.jpeg"--> <img src="https://images.pexels.com/videos/1448735/free-video-1448735.jpg" width="100" height="57" alt=""/></a>Miniatura 3</div>
        
        <footer>
            Leadster-Produzido por: Mateus Cassiano
        </footer>
    </div>
</body>
</html>
