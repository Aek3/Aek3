<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Personnelle de Sport</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2em;
        }
        .section {
            margin-bottom: 2em;
        }
        .section h2 {
            color: #4CAF50;
        }
        .videos iframe {
            width: 100%;
            height: 315px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page personnelle de football</h1>
    </header>
    <nav>
        <a href="#about">À propos</a>
        <a href="#performances">Performances</a>
        <a href="#articles">Articles</a>
        <a href="#videos">Vidéos</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>À propos de moi</h2>
            <p>Je suis un passionné de football, joueur amateur et fervent supporter. Sur cette page, je partage mes performances personnelles, mes articles favoris sur mes joueurs préférés, et des vidéos de mes matchs.</p>
        </section>
        <section id="performances" class="section">
            <h2>Mes Performances</h2>
            <ul>
                <li>Match contre l'équipe locale - 2 buts marqués</li>
                <li>Tournoi de quartier - 3 passes décisives</li>
                <li>Championnat régional - meilleur joueur du match</li>
            </ul>
        </section>
        <section id="articles" class="section">
            <h2>Articles sur mes joueurs préférés</h2>
            <ul>
                <li><a href="https://www.example.com/article1" target="_blank">Biographie de Lionel Messi</a></li>
                <li><a href="https://www.example.com/article2" target="_blank">Les exploits de Cristiano Ronaldo</a></li>
                <li><a href="https://www.example.com/article3" target="_blank">Les meilleurs moments de Zinedine Zidane</a></li>
            </ul>
        </section>
        <section id="videos" class="section videos">
            <h2>Vidéos de mes matchs</h2>
            <iframe src="https://www.youtube.com/embed/example1" frameborder="0" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/example2" frameborder="0" allowfullscreen></iframe>
        </section>
    </div>
</body>
</html>
