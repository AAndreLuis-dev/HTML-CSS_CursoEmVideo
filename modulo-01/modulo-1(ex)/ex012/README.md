# Exercício
## Videos com HTML5
![Result]()
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Videos com HTML5</title>
</head>
<body>
    <h1>Inserindo videos hospedados localmente</h1>
    <p>
        Este video está hospedado no meu própio servidor.
    </p>

    <video controls poster="imagens/pexels-roberto-vivancos-2190283.jpg" width="560" autoplay loop> 
        <source src="midia/meu-video.webm" type="video/webm">
            <source src="midia/meu-video.m4v" type="video/m4v">
                <source src="midia/meu-video.mp4" type="video/mp4">
                    <p>Seu navegador não tem compatibilidade com videos.</p>
    </video>

    <h1>Inserindo videos do Youtube</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/eF9Qoc6p_4Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</body>
</html>
```