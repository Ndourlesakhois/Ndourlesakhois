<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma ville Podor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 50px 0;
        }

        header h1 {
            margin: 0;
            font-size: 3em;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .section-content {
            flex-basis: 30%;
            text-align: center;
            padding: 20px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .section-content:hover {
            transform: scale(1.05);
        }

        .section-content img {
            max-width: 100%;
            height: auto;
            margin-bottom: 15px;
        }

        .section-content h2 {
            color: #333;
            font-size: 1.5em;
        }

        .section-content p {
            color: #777;
            line-height: 1.6;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            .section-content {
                flex-basis: 100%;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenue à Podor ma Ville</h1>
    </header>

    <section>
        <div class="section-content">
            <img src="Quai Pdr.jpg" alt="Image 1">
            <h2>Quai de Podor</h2>
            <p>Sur le quai de Podor, une dizaine de maisons construites au début du XIXe siècle et aux noms évocateurs (Maurel, Prom, Buhan, Teissère, Singer, Peyrissac), témoignent de l’effervescence du commerce qui en a marqué l’histoire pendant près de deux siècles. La maison située au coin Nord du quai porte le nom de Guillaume Foy dont la marque commerciale, contrairement aux autres, n’a pas traversé les siècles et perduré. Elle a été remarquablement restaurée et sert de maison d’hôtes.</p>
        </div>

        <div class="section-content">
            <img src="FS.jpeg" alt="Image 2">
            <h2>Fleuve Sénégal</h2>
            <p>Le Sénégal est un fleuve d'Afrique de l'Ouest au régime tropical, de 1 750 kilomètres de longueur, qui prend sa source en Guinée à 750 mètres d'altitude. Il arrose le Mali, puis la Mauritanie et le Sénégal, tout en servant de frontière entre ces deux pays, avant de se jeter dans l'océan Atlantique à Saint-Louis.</p>
        </div>

        <div class="section-content">
            <img src="https://via.placeholder.com/300x200" alt="Image 3">
            <h2>Section 3</h2>
            <p>Curabitur aliquet quam id dui posuere blandit. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Ma page web - Tous droits réservés</p>
    </footer>

</body>
</html>
