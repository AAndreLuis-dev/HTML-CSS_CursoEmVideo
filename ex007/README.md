# Exercício 007
## Formatação de Texto
![Resultpic](https://github.com/AAndreLuis-dev/HTML-CSS_CursoEmVideo/blob/main/ex007/imgex007-edit.png)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="Icons8-Ios7-Programming-Console.ico" type="image/x-icon">
    <title>Formatação de Texto</title>
</head>
<body>
    <h1>Principais formatações</h1>
    <h2>Negrito / Destaque </h2>
    <p>Temos nessa frase aqui um <b> termo em negrito</b> usando a tag B. (Não semântica)</p>
    <p>Nesta frase, temos um <strong>termo em negrito </strong> usando a tag STRONG.(com semântica) </p>

    <h2>Itálico / Ênfase </h2>
    <p>Nesta frase, temos um <i>tempo em itálico</i> usando a tag I</p>
    <p>
        Nesta frase, temos um <em>termo em ênfase</em> usando a tag EM. (semântica)
    </p>
    <h2>
        Marcador de texto
    </h2>
    <p>
        Podemos, também, criar um <mark style="background-color: rgb(204, 47, 19);"> texto marcado </mark> com a tag MARK. 
        
        <p>E, no outro parágrafo, temos  <mark> um outro texto marcado </mark> no final.</p>
        <h2>Texto grande e pequeno.</h2>
        <p>Estamos criando um <big>texto grande</big> e um <small>texto pequeno</small> neste parágrafo.</p> <!--Big se tornou obsoleta, recomendado usar CSS para modificar a estética.-->

        <h2>Texto deletado</h2>
        <p>Podemos marcar um <del>
            texto excluido
        </del> para indicar que ele pode ser lido, mas não considerado.</p>

        <h2>Texto inserido</h2>
        <p>Podemos marcar <ins>um texto como inserido</ins> para dar uma ênfase que ele foi adicionado depois.</p>

        <h2>Texto sobrescrito</h2>
        <p>Para inserir coisas do tipo x<sup>20</sup>+3</p>

        <h2>Texto subscrito</h2>
        <p>Para inserir coisas do tipo H<sub>2</sub>O</p>
</body>
</html>
```
