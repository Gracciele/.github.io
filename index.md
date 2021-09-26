<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>Caraguatatuba</title>
</head>
<body>
<header class='header'>
    <h1>Caraguatatuba</h1>
</header>


<main class='container'>
    <fieldset class='fieldsetFundo'>
        <legend>Dados Pessoais</legend>
        <form action="#" method="POST">

            <label for="nome">Nome:</label>
            <input placeholder='Seu nome completo' type="text" name='nome' id="nome" required="required" maxlength="100">

            <label for="email">E-mail:</label>
            <input placeholder='Seu email' type="email" name='email' id="email" required="required">
            
            
            <label for="Telefone">Telefone:</label>
            <input placeholder='Seu telefone com DDD'type="number" required="required" maxlength="15" name="phone">

            <label>Data de Nascimento</label>
            <input type='date' name='data' id='data'>
    </fieldset>

    <fieldset class='fieldsetFundo2'>
        <legend>+18</legend>
        <input type='radio' name='idade' id='+18'>
        <label for='+18'>Sim</label>

        <input type='radio' name='idade' id='-18'>
        <label for='-18'>Não</label>
    </fieldset>

    <fieldset class='fieldsetFundo3'>
        <legend>O que Mais Gosta?</legend>
        <input type='radio' name='praias' id='praias'>
        <label for='praias'>Praias</label>

        <input type='radio' name='Culinária' id='Culinária'>
        <label for='Culinária'>Culinária</label>

        <input type='radio' name='eventos notunos' id='Eventos Noturnos'>
        <label for='Eventos Noturnos'>Eventos Noturnos</label>

        <input type='radio' name='eventos diurnos' id='Eventos Diurnos'>
        <label for='Eventos Diurnos'>Eventos Diurnos</label>

        <input type='radio' name='locais' id='Culinária'>
        <label for='Surf'>Surf</label>
    </fieldset>

    <fieldset class='fieldsetFundo4'>
        <legend>Selecione Quais Seus Interesses Na Cidade</legend>
        <div class="opcionais"></div>
        <input type='radio' name='Interesses' id='Turista'>
        <label for='Turista'>Turista</label>

        <input type='radio' name='Interesses' id='Residente'>
        <label for='Residente'>Residente</label>

        <input type='radio' name='Interesses' id='Estudante'>
        <label for='Estudante'>Estudante</label>
    </fieldset>

    <button type='reset'>Cancelar</button>
                <button type='submit'>Enviar</button>



</body>
</html>
