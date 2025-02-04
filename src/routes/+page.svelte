<title>Início - UEFA Champions League</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            text-align: center;
            color: #333;
        }

        /* Barra de navegação */
        nav {
            background-color: #003A5C;
            width: 100%;
            padding: 15px 0;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 100;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav .logo-container {
            display: flex;
            align-items: center;
            margin-left: 20px;
        }

        nav .logo {
            height: 50px;
            width: auto;
            margin-right: 10px;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 25px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            text-transform: uppercase;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #0061F2;
        }

        /* Seção Hero */
        .hero-section {
            background-color: #003A5C;
            color: white;
            padding: 120px 20px;
            text-align: center;
            font-size: 2.5em;
            font-weight: bold;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* Galeria de Times */
        .team-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 60px;
            gap: 20px;
            padding: 0 20px;
        }

        .team-card {
            width: 230px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            padding: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            overflow: hidden;
        }

        .team-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .team-card h3 {
            margin-top: 15px;
            font-size: 1.6em;
            color: #003A5C;
            font-weight: bold;
        }

        .team-card:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 45px rgba(0, 0, 0, 0.15);
        }

        .team-card:hover img {
            transform: scale(1.1);
        }

        /* Links das seções */
        .section-link {
            text-decoration: none;
            color: #003A5C;
            background-color: #ffffff;
            padding: 15px 30px;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin: 10px;
            font-size: 1.5em;
            transition: background-color 0.3s ease, color 0.3s ease;
            display: inline-block;
            font-weight: 500;
        }

        .section-link:hover {
            background-color: #0061F2;
            color: white;
        }

        /* Layout do conteúdo */
        .container {
            margin-top: 160px;
            padding: 20px;
        }

        .container .section-title {
            font-size: 2.5em;
            color: #003A5C;
            margin-bottom: 30px;
            font-weight: bold;
        }
    </style>


    <!-- Barra de navegação -->
    <nav>
        <div class="logo-container">
       
            <span style="color: white; font-size: 1.7em; font-weight: bold;">UEFA Champions League</span>
        </div>
        <ul>
            <li><a href="noticias">Notícias</a></li>
            <li><a href="classificacao">Classificação</a></li>
            <li><a href="estadio">Estádio</a></li>
        </ul>
    </nav>

    <!-- Seção Hero -->
    <div class="hero-section">
        <h1>Bem-vindo à UEFA Champions League</h1>
        <p>Acompanhe os melhores times, jogos e classificações da competição mais emocionante da Europa.</p>
    </div>

    <!-- Seção Galeria de Times -->
    <div class="container">
        <div class="section-title">Times Participantes</div>
        <div class="team-gallery">
            <div class="team-card">
                <img src="/liverpool.jpg" alt="Liverpool">
                <h3>Liverpool</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/FC_Barcelona_%28logo%29.svg" alt="Barcelona">
                <h3>Barcelona</h3>
            </div>
            <div class="team-card">
                <img src="/atletico de ma.webp" alt="Atlético de Madrid">
             
                <h3>Atlético de Madrid</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Arsenal_FC.svg" alt="Arsenal">
                <h3>Arsenal</h3>
            </div>
            <div class="team-card">
                <img src="/bayer leverkusen.jpg "alt="Bayer Leverkusen">
                <h3>Bayer Leverkusen</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/d2/FC_Internazionale_Milano_logo.svg" alt="Internazionale">
                <h3>Internazionale</h3>
            </div>
        </div>
    </div>
