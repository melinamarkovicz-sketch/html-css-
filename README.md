# html-css-
    <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atividade - HTML e CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>Atividade: HTML e CSS</h1>
        <h2>Perguntas Sortidas</h2>

        <ol>
            <li>O que é HTML?</li>
            <li>O que significa a sigla CSS?</li>
            <li>Qual é a função da tag &lt;head&gt;?</li>
            <li>Qual é a função da tag &lt;body&gt;?</li>
            <li>Para que serve a tag &lt;title&gt;?</li>
            <li>Como conectar um arquivo CSS ao HTML?</li>
            <li>Qual tag cria um parágrafo?</li>
            <li>Qual tag cria um link?</li>
            <li>Qual propriedade CSS altera a cor do texto?</li>
            <li>Qual propriedade CSS altera a cor de fundo?</li>
            <li>O que faz a propriedade <strong>font-size</strong>?</li>
            <li>Qual é a diferença entre HTML e CSS?</li>
            <li>O que faz a propriedade <strong>margin</strong>?</li>
            <li>O que faz a propriedade <strong>padding</strong>?</li>
            <li>Cite dois ambientes de desenvolvimento para HTML e CSS.</li>
        </ol>

        <h2>Verdadeiro ou Falso</h2>

        <ul>
            <li>( ) HTML é responsável pela estrutura da página.</li>
            <li>( ) CSS serve para estilizar a página.</li>
            <li>( ) A tag &lt;p&gt; cria um parágrafo.</li>
            <li>( ) O CSS possui extensão .css.</li>
            <li>( ) O HTML pode funcionar sem CSS.</li>
        </ul>

        <h2>Múltipla Escolha</h2>

        <p><strong>1.</strong> Qual é a extensão de um arquivo HTML?</p>

        <label><input type="radio" name="q1"> .css</label><br>
        <label><input type="radio" name="q1"> .html</label><br>
        <label><input type="radio" name="q1"> .js</label><br>

        <p><strong>2.</strong> Qual propriedade altera a cor do texto?</p>

        <label><input type="radio" name="q2"> margin</label><br>
        <label><input type="radio" name="q2"> color</label><br>
        <label><input type="radio" name="q2"> padding</label><br>

        <br>

        <button>Enviar Respostas</button>

    </div>
body{
    font-family: Arial, Helvetica, sans-serif;
    background:#f0f2f5;
    margin:0;
}

.container{
    width:80%;
    max-width:900px;
    margin:30px auto;
    background:#ffffff;
    padding:30px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

h1{
    text-align:center;
    color:#0d6efd;
}

h2{
    color:#333;
    border-bottom:2px solid #0d6efd;
    padding-bottom:5px;
}

ol li,
ul li{
    margin:10px 0;
}

label{
    display:block;
    margin:5px 0;
}

button{
    background:#0d6efd;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:6px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#084298;
}
</body>
</html>
