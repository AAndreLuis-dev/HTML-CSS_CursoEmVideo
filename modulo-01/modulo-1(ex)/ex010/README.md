# Exercício 010
## Trabalhando com Links
### Index(Página 001)
![Resultpic](https://github.com/AAndreLuis-dev/HTML-CSS_CursoEmVideo/blob/main/modulo-1(img)/imgex010-edit.png)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="Icons8-Ios7-Programming-Console.ico" type="image/x-icon">
    <title>Trabalhando com Links</title>
</head>
<body>
    <h1>Usando links externos</h1>
    <p>Você pode acessar <a href="https://github.com/AAndreLuis-dev" target="_blank" rel="external">meu repositório público do GitHub</a>. <br> Você também pode acessar o <a href="https://www.youtube.com/watch?v=LeOVXQDsAIY&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=27&ab_channel=CursoemV%C3%ADdeo" target="_blank" rel="external">canal do Guanabara</a></p></a>
    <h1>Usando links internos</h1>
    <p>Aqui é minha primeira página. Se quiser, você também pode acessar a <a href="pag002.html" target="_self" rel="next">segunda</a></p>
    <p>Você também pode acessar nossa <a href="noticias/pag003.html" target="_self" rel="next">página de notícias</a></p>
    <h1>Links para download</h1>
    <ul>
        <li><a href="livros/10 - Ligações em toda parte.pdf">Baixando o livro em Pdf.</a></li>
        <li><a href="livros/10 - Ligações em toda parte.zip" download="livros/10 - Ligações em toda parte.zip" type="application/zip">Baixar o livro em Zip</a>.</li>
    </ul>
</body>
</html>
```
### Página 002
![Resultpic](https://github.com/AAndreLuis-dev/HTML-CSS_CursoEmVideo/blob/main/modulo-1(img)/imgex010-2-edit.png)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página número dois</title>
</head>
<body>
    <h1>Está é a seunda página do meu site</h1>
    <p>Aqui é a segunda página.</p>
    <p>Está página é oferecimento da <a href="Https://www.hostnet.com.br" target="_blank" rel="nofollow">Hostnet</a></p>
    <p><a href="index.html" rel="prev">Primeira página.</a></p>
</body>
</html>
```
### Página 003
![Resultpic](https://github.com/AAndreLuis-dev/HTML-CSS_CursoEmVideo/blob/main/modulo-1(img)/imgex010-3-edit.png)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terceira página</title>
</head>
<body>
    <h1>É a terceira página </h1>
    <p>Está é a terceria página.</p>
    <p>Volte para a <a href="../index.html   ">primeira página.</a></p>
</body>
</html>
```
