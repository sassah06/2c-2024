<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meu Projeto</title>
<link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Hurricane&display=swap" rel="stylesheet">
</head>
<body>
<header class="cabecalho">
<img class="cabecalho_imagem" src="mundo_logo.png" alt="">
<h1 class="cabecalho_titulo">Nossa Turma de 2024</h1>
<ul>
<li class="cabecalho_lista">A Escola</li>
<li class="cabecalho_lista">Os Alunos</li>
</ul>
</header>
<section class="corpo">
<img class="corpo_imagem" src="info_logo.png" alt="Desenho do Corpo do Site">
<div class="corpo_textos">
<h2 class="copo_titulo">Trilha de Programação I</h2>
<p class="corpo_paragrafo"> Desenvolvendo pensamentos voltados a programação e a
utilização dos computadores com inteligência e sabedoria, criando a espectativa de melhores e maiores
possibilidades.
</p>
</div>
</section>
<section class="estudante">
<h3 class="rodape_estudantes">Quem são nossos estudantes</h3>
</section>
</body>
</html>
align-self: center;
font-family: "Hurricane", cursive;
font-weight: 400;
font-size: 65px;
}
.corpo_textos{
display: flex;
flex-direction: column;
font-size: 30px;
align-items: baseline;
}
.corpo_paragrafo{
padding: 15px 0;
text-align: justify;
margin: 0 25px;
}
