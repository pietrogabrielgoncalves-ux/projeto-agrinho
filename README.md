# projeto-agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Projeto Agrinho 2026</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
    font-size: 25px;
}

header{
    background: green;
    color: white;
    text-align: center;
    padding: 20px;
}

section{
    max-width: 900px;
    margin: 20px auto;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

img{
    width: 100%;
    border-radius: 10px;
}

h1,
h2,
p,
button,
footer,
header p{
    font-size: 25px;
}

h1,
h2{
    color: green;
    font-weight: bold;
}

button{
    background: green;
    color: white;
    border: none;
    padding: 15px 30px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover{
    background: darkgreen;
}

footer{
    text-align: center;
    background: #222;
    color: white;
    padding: 15px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Projeto Agrinho 2026</h1>
    <p>Campo e Cidade: Uma Conexão Essencial</p>
</header>

<section>
    <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854" alt="Plantação">

    <h2>O Agro em Nossa Vida</h2>

    <p>
        O campo produz os alimentos que chegam diariamente à mesa dos brasileiros.
        Sem os agricultores, seria impossível termos arroz, feijão, frutas,
        verduras, leite e carne.
    </p>

    <p>
        Além de alimentar a população, o agronegócio gera empregos e movimenta a
        economia do Brasil. A tecnologia também está presente no campo,
        tornando a produção mais eficiente e sustentável.
    </p>

    <h2>Campo e Cidade Juntos</h2>

    <p>
        A cidade depende do campo para receber alimentos e matérias-primas.
        Já o campo depende da cidade para obter máquinas, tecnologia e serviços.
        Essa parceria é fundamental para o desenvolvimento do país.
    </p>

    <button id="botaoAgrinho" onclick="window.open('https://www.youtube.com/watch?v=7kp0MyU4kpA', '_blank')">
        Saiba Mais
    </button>
</section>

<footer>
    <p>Projeto Agrinho 2026 - Desenvolvido por Seu Nome</p>
</footer>

</body>
</html>-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Projeto Agrinho 2026</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
    font-size: 25px;
}

header{
    background: green;
    color: white;
    text-align: center;
    padding: 20px;
}

section{
    max-width: 900px;
    margin: 20px auto;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

img{
    width: 100%;
    border-radius: 10px;
}

h1,
h2,
p,
button,
footer,
header p{
    font-size: 25px;
}

h1,
h2{
    color: green;
    font-weight: bold;
}

button{
    background: green;
    color: white;
    border: none;
    padding: 15px 30px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover{
    background: darkgreen;
}

footer{
    text-align: center;
    background: #222;
    color: white;
    padding: 15px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Projeto Agrinho 2026</h1>
    <p>Campo e Cidade: Uma Conexão Essencial</p>
</header>

<section>
    <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854" alt="Plantação">

    <h2>O Agro em Nossa Vida</h2>

    <p>
        O campo produz os alimentos que chegam diariamente à mesa dos brasileiros.
        Sem os agricultores, seria impossível termos arroz, feijão, frutas,
        verduras, leite e carne.
    </p>

    <p>
        Além de alimentar a população, o agronegócio gera empregos e movimenta a
        economia do Brasil. A tecnologia também está presente no campo,
        tornando a produção mais eficiente e sustentável.
    </p>

    <h2>Campo e Cidade Juntos</h2>

    <p>
        A cidade depende do campo para receber alimentos e matérias-primas.
        Já o campo depende da cidade para obter máquinas, tecnologia e serviços.
        Essa parceria é fundamental para o desenvolvimento do país.
    </p>

    <button id="botaoAgrinho" onclick="window.open('https://www.youtube.com/watch?v=7kp0MyU4kpA', '_blank')">
        Saiba Mais
    </button>
</section>

<footer>
    <p>Projeto Agrinho 2026 - Desenvolvido por Seu Nome</p>
</footer>

</body>
</html>
document.addEventListener("DOMContentLoaded", function() {

    const botao = document.getElementById("botaoAgrinho");

    botao.addEventListener("click", function() {
        window.open("https://www.youtube.com/watch?v=7kp0MyU4kpA", "_blank");
    });

});
