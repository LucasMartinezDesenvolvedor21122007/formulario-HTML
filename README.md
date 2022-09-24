<!DOCTYPE html>
<html lang="en">
</head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="index.css" media="screen">
<title>Cadastro</title>
<head>
</body>

<div class="campo">
    <h1 id="titulo">Cadastro De Clientes</h1>
    <p id="subtitulo">Complete suas informações</p>
    <br>
</div class="campo">

<form>
    <fieldset class="campo">
        <div class="campo">
            <label for="nome">Nome</label>
            <input type="text" name="nome" id="nome" required>
        </div class="campo">

        <div class="campo">
            <label for="Sobrenome">Sobrenome</label>
            <input type="text" name="Sobrenome" id="Sobrenome" required>
        </div class="campo">
    </fieldset class="campo">

    <div class="campo">
       <label for="email">Email</label>
       <input type="email" name="email" id="email" required>
    </div class="campo">

<label for="produtos">selecione os produtos que você deseja</label>
<label>
    <br>
    <input type="checkbox" name="produto1" id="produto1" value="Iphone">Iphone
    <br>
    <input type="checkbox" name="produto2" id="produto2" value="Apple Watch">apple Watch
    <br>
    <input type="checkbox" name="produto3" id="produto3" value="MacBookpro">MacBookpro
</label for="produtos">
<br>
<div class="campo">
    <label class="campo">Há Quantos Anos Você é cliente da nossa empresa</label>
    <select id="trabalho">
        <option selected disabled value="">selecione</option>
       <option>1 ano</option>
       <option>2 anos</option>
       <option>3 anos</option>
       <option>4 anos</option>
       <option>+4 anos</option>
    </select>
</div class="campo">
<br>
<fieldset>
    <div id="check">
        <label>Quais Produtos da nossa empresa você gosta mais</label>
        <input type="checkbox" name="produto1" id="produto1" value="MacBookPro">
        <label>MacBookPro</label>
        <input type="checkbox" name="produto2" id="produto2" value="Apple Watch">
        <label>Apple Watch</label>
        <input type="checkbox" name="produto3" id="produto3" value="airpods">
        <label class="campo">airpods</label>
    </div class="campo">
</fieldset class="grupo">

<div class="campo">
    <br>
    <label>Conte Um Pouco Da Sua Experiência</label>
    <textarea rows="2" style="width:25em;" id="experiência" name="experiência"></textarea>
</div class="campo">

<button type="submit">Enviado Com Sucesso!</button>


</form>

<body>
<html>

*{
    margin:0;
    padding: 0;
}

#titulo{
    font-family: sans-serif;
    color:#370b6193;
    margin-left: 11%;
}

#subtitulo{
    font-family: sans-serif;
    color:#380b61;
    margin-left: 11%;
}

fieldset{
    border:0;
}

body{
    background-color: #F0F8FF;
    font-family: sans-serif;
    font-size: medium;
    color:#59429d;
    margin-left: 6%;
    margin-top: 5%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 1px;
}

.campo{
   margin-bottom: 1em;
}

.campo label{
    margin-bottom: 1px;
    color:#59429d;
    display: block;
}

fieldset.grupo.campo{
    float:left;
    margin-right:1em;
}

.campo input [type="text"], .campo input[type="email"], .campo select, .campo textarea{
    padding: 0.2em;
    border:1px solid #59429d;
    box-shadow: 1px 1px 1px rgb(66, 66, 66);
    display: block;
}

.campo select option{
    padding-right: 1em;
}

.campo input:focus, .campo select:focus, .campo textarea:focus{
    background: #E0E0F8;
}

.botão{
    font-size: 1.2em;
    background: #59429d;
    border:0;
    margin-bottom: 1em;
    color:#ffffff;
    padding: 0.2em 0.7em;
    box-shadow:2px 2px 2px rgba(0,0,0,0.2);
    text-shadow: 1px 1px 1px 1px rgba(0,0,0,0.7);
    position:absolute;
    top: 15%;
    left: 15%;
    margin-right: -45%;
    transform: translate(-50%, -50%);
}

.botão:hover{
    background: #ccbbff;
    box-shadow: inset 1px, 1px, 1px rgba(0,0,0,0.5);
    text-shadow:none;
}

.botão, select{
    cursor:pointer;
}

#check{
  display:inline-block;
}
