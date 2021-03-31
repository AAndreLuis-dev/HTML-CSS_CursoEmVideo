# Exercício 011
##  Mídias em HTML5
![Result](https://github.com/AAndreLuis-dev/HTML-CSS_CursoEmVideo/blob/main/modulo-01/modulo-1(img)/ex011.jpeg)

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/Icons8-Ios7-Programming-Console.ico" type="image/x-icon">
    <title>Mídias em HTML5</title>
</head>
<body>
    <h1>Imagens dinâmicas</h1>
    <p>Tente abrir este site em vários dispositivos diferentes ou simplesmente aumente e diminua o tamanho do seu navegador.
    </p>

    <picture>
        <source media="(max-width:750px )" srcset="imagens/foto-p.png" type="image/png">
        <source media="(max-width:1050px )" srcset="imagens/foto-m.png" type="image/png">
        <img src="imagens/foto-g.png" alt="Imagem flexivel">
    </picture>

    <h1>Reproduzindo Áudio</h1>
    <p>Vamos aprender a reproduzir áudios com HTML5</p>
    <!--<audio src="midia/happy-mistake.mp3" controls autoplay > </audio> -->
    <audio preload="metadata"controls loop>
        <source src="midia/happy-mistake.mp3" type="audio/mpeg" >
        <p>infelizmente seu navegador não consegue produzir áudio. <a href="midia/happy-mistake.mp3"> Click aqui para baixar a mídia</a></p>
    </audio>
</body>
</html>
```
