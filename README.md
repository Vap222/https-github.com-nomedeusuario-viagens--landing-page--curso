# https-github.com-nomedeusuario-viagens--landing-page--curso

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Vilarejo Europeu</title>
    <style>
        /* Define a fonte padrão para toda a página */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Estilização da barra de navegação */
        nav {
            background-color: #333; /* Cor de fundo escura */
            padding: 10px; /* Espaçamento interno */
            position: sticky; /* Fixa o menu no topo ao rolar a página */
            top: 0;
        }

        /* Links da navegação */
        nav a {
            color: white; /* Cor do texto */
            text-decoration: none; /* Remove sublinhado */
            margin: 0 15px; /* Espaçamento entre os links */
            font-size: 18px; /* Tamanho da fonte */
        }

        /* Efeito ao passar o mouse sobre os links */
        nav a:hover {
            text-decoration: underline; /* Adiciona sublinhado */
            color: #ffa500; /* Altera a cor do texto */
        }

        /* Centralização do conteúdo principal */
        main {
            text-align: center;
        }

        /* Configuração do banner */
        .banner {
            background-image: url('https://example.com/village.jpg'); /* Substitua pelo link de uma imagem real */
            background-size: cover; /* Ajusta o tamanho da imagem para cobrir toda a área */
            background-position: center; /* Centraliza a imagem */
            height: 300px; /* Altura fixa */
            display: flex; /* Habilita o flexbox */
            align-items: center; /* Centraliza verticalmente o conteúdo */
            justify-content: center; /* Centraliza horizontalmente o conteúdo */
            color: white; /* Cor do texto */
            text-shadow: 2px 2px 5px black; /* Adiciona sombra ao texto */
        }

        /* Estilização do título dentro do banner */
        .banner h1 {
            font-size: 36px;
        }

        /* Configuração geral das seções */
        section {
            padding: 50px; /* Espaçamento interno */
        }

        /* Estilos específicos para cada seção */
        #TripMe {
            background-color: #f4f4f4; /* Cor de fundo clara */
        }

        #MeetUs {
            background-color: #e8e8e8; /* Cor de fundo levemente mais escura */
        }

        #Advice {
            background-color: #dcdcdc; /* Cor de fundo ainda mais escura */
        }

        /* Configuração dos links internos */
        a[href^="#"] {
            cursor: pointer; /* Define o cursor como "pointer" ao passar sobre o link */
        }

        /* Estilização do rodapé */
        footer {
            text-align: center; /* Centraliza o texto */
            padding: 20px; /* Espaçamento interno */
            background-color: #333; /* Cor de fundo escura */
            color: white; /* Cor do texto */
        }
    </style>
</head>
<body>
    <!-- Navegação principal -->
    <nav>
        <a href="#TripMe">TripMe</a> <!-- Link para a seção TripMe -->
        <a href="#MeetUs">MeetUs</a> <!-- Link para a seção MeetUs -->
        <a href="#Advice">Advice</a> <!-- Link para a seção Advice -->
        <a href="#top">Home</a> <!-- Link para voltar ao topo -->
    </nav>

    <!-- Conteúdo principal -->
    <main id="top">
        <!-- Banner com imagem de fundo e texto sobreposto -->
        <div class="banner">
            <h1>Descubra o Charme dos Vilarejos Europeus</h1>
        </div>

        <!-- Seção TripMe -->
        <section id="TripMe">
            <h2>TripMe</h2>
            <p>Explore destinos incríveis e crie memórias inesquecíveis. Planeje sua viagem com dicas exclusivas de lugares únicos.</p>
        </section>

        <!-- Seção MeetUs -->
        <section id="MeetUs">
            <h2>MeetUs</h2>
            <p>Conheça nossa equipe de especialistas em viagens e deixe-nos ajudar a transformar sua próxima aventura em realidade.</p>
        </section>

        <!-- Seção Advice -->
        <section id="Advice">
            <h2>Advice</h2>
            <p>Receba conselhos valiosos sobre como aproveitar ao máximo sua viagem. De dicas de economia a roteiros secretos, temos tudo para você.</p>
        </section>
    </main>

    <!-- Rodapé da página -->
    <footer>
        <p>&copy; 2024 TripMe. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
