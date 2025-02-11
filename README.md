<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ma Page Personnelle</title>
    <style>
        /* Styles CSS */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        img {
            width: 90px;
            margin: auto;
            height: auto;
            box-shadow: #21b65a;
        }

        section {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h2 {
            color: #4CAF50;
        }

        p {
            font-size: 1.1rem;
        }

        button {
            display: block;
            margin: 90px auto;
            padding: 10px 90px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049;
        }

        footer {
            text-align: center;
            padding: 3px 0;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <!-- Structure HTML -->
    <header>
        <h1>Bienvenue sur ma page personnelle</h1>
    </header>

    <section id="about">
        <h2>À propos de moi</h2>
        <img src="mon ig.jpg" alt="Mon image">
        <p>Je m'appelle <strong>ASSIA DJOLE HENOC</strong><br>
             Passionnée par L'informatique . je deviens  étudiant a l'université virtuelle de côté d'ivoire en première année de licence en <strong>Réseau Sécurité et Informatique (RSI)</strong>. <br> 
             J'ai étudié La promagramtion en <strong>PYTON,HTML,CSS et en LANGAGE PASCAL</strong> à <strong> l'université vituelle de côte d'Ivoire(UVCI) </strong> pendants mon année universitaire 2025-2026.<br>
             j'adore écouter de la musique,regardez des dessins animés et aussi jouer a des jeux mais pendant mes pausse j'aime regarder des vidéos sur la prorammation et aussi le réseaux informatique
            .</p>
    </section>

    <section id="passion">
        <h2>Ma passion</h2>
        <p>Ma plus grande passion est la Technologie.<br> 
             J'aime cela parce que La technologie est un domaine vaste et fascinant qui touche presque tous les aspects de notre vie moderne.<br>
             C'est un domaine en constante évolution La technologie évolue rapidement, ce qui signifie qu'il y a toujours quelque chose de nouveau à apprendre.<br>
             Tu ne t'ennuieras jamais, car il y a toujours des défis à relever et des innovations à découvrir.<br>
             C'est créatif,C'est un domaine collaboratif,C'est lucratif et aussi C'est amusant.
         </p>
    </section>

    <button id="messageButton">Cliquez-moi !</button>

    <footer>
        <p><a href="mailto:djole.assia@uvci.educ.ci" style="color: #4CAF50; text-decoration: none;">Contactez-moi à djole.assia@uvci.educ.ci </a></p>
    </footer>

    <!-- JavaScript -->
    <script>
        document.getElementById('messageButton').addEventListener('click', function() {
            alert('Merci d\'avoir visité ma page ! 😊');
        });
    </script>
</body>
</html>
