<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coach Sport & Diététique</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        p {
            line-height: 1.6;
        }
        .services ul {
            list-style: none;
            padding: 0;
        }
        .services ul li {
            background: #efefef;
            margin: 10px 0;
            padding: 10px;
            border-left: 5px solid #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            font-size: 1em;
            border: 1px solid #ccc;
        }
        form input[type="submit"] {
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Coach Sport & Diététique</h1>
    </header>
    <nav>
        <a href="#about">À Propos</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>À Propos</h2>
        <p>Je suis coach sportif diplômé et conseillé en diététique. Avec plusieurs années d'expérience, j'accompagne mes clients dans l'atteinte de leurs objectifs de santé, de performance physique et de bien-être. Ma mission est de vous fournir des plans d'entraînement personnalisés et des conseils nutritionnels adaptés à vos besoins.</p>
    </section>
    <section id="services" class="services">
        <h2>Mes Services</h2>
        <ul>
            <li>Coaching sportif personnalisé sur 8 semaines</li>
            <li>Planification diététique sur mesure</li>
            <li>Suivi et évaluation des performances</li>
            <li>Conseils en mode de vie sain</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Votre nom" required>
            <input type="email" name="email" placeholder="Votre email" required>
            <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
            <input type="submit" value="Envoyer">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Coach Sport & Diététique. Tous droits réservés.</p>
    </footer>
</body>
</html>
