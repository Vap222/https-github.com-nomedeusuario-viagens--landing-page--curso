
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Vilarejo Europeu</title>
    <style>
        /* Estilo básico e fonte padrão */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navegação */
        nav {
            background-color: #333;
            padding: 10px;
            position: sticky;
            top: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
            color: #ffa500;
        }

        /* Banner */
        .banner {
            background-image: url('https://example.com/village.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 5px black;
        }

        .banner h1 {
            font-size: 36px;
        }

        /* Seções */
        section {
            padding: 50px;
        }

        #TripMe {
            background-color: #f4f4f4;
        }

        #MeetUs {
            background-color: #e8e8e8;
        }

        #Advice {
            background-color: #dcdcdc;
        }

        /* Rodapé */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        /* Links internos */
        a[href^="#"] {
            cursor: pointer;
        }
    </style>
</head>
<body>
    <!-- Navegação principal -->
    <nav>
        <a href="#TripMe">TripMe</a>
        <a href="#MeetUs">MeetUs</a>
        <a href="#Advice">Advice</a>
        <a href="#top">Home</a>
    </nav>

    <!-- Banner -->
    <header id="top" class="banner">
        <h1>Descubra o Charme dos Vilarejos Europeus</h1>
    </header>

    <!-- Conteúdo principal -->
    <main>
        <section id="TripMe">
            <h2>TripMe</h2>
            <p>Explore destinos incríveis e crie memórias inesquecíveis. Planeje sua viagem com dicas exclusivas de lugares únicos.</p>
        </section>

        <section id="MeetUs">
            <h2>MeetUs</h2>
            <p>Conheça nossa equipe de especialistas em viagens e deixe-nos ajudar a transformar sua próxima aventura em realidade.</p>
        </section>

        <section id="Advice">
            <h2>Advice</h2>
            <p>Receba conselhos valiosos sobre como aproveitar ao máximo sua viagem. De dicas de economia a roteiros secretos, temos tudo para você.</p>
        </section>
    </main>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 TripMe. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
