<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PodHorizon - Podcast Reviews en Aanbevelingen</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 85%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #222;
            color: #fff;
            padding: 10px 0;
            border-bottom: #ffc107 3px solid;
            text-align: center;
        }
        header img {
            max-width: 150px;
            height: auto;
        }
        header nav {
            margin-top: 10px;
        }
        header nav a {
            color: #fff;
            text-decoration: none;
            padding: 5px 20px;
            text-transform: uppercase;
            font-size: 16px;
        }
        .hero {
            background: #333;
            color: #fff;
            padding: 60px 20px;
            text-align: center;
        }
        .content {
            padding: 20px 0;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .post {
            background: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .post img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            margin-bottom: 10px;
        }
        .post h2 {
            font-size: 20px;
            margin-bottom: 10px;
        }
        .post .details {
            margin: 10px 0;
        }
        .post .details p {
            margin: 5px 0;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <img src="https://example.com/your-logo-url.png" alt="PodHorizon Logo">
            <nav>
                <a href="#home">Home</a>
                <a href="#reviews">Reviews</a>
                <a href="#favorites">Favorieten</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>
    <div class="hero">
        <div class="container">
            <h1>Welkom op PodHorizon</h1>
            <p>Ontdek de beste podcasts met onze uitgebreide reviews en aanbevelingen.</p>
        </div>
    </div>
    <div class="container content">
        <section id="reviews">
            <h2>Recente Reviews</h2>
            <div class="grid-container">
                <div class="post">
                    <img src="image_url" alt="Podcast Image">
                    <h2>Titel van de Podcast</h2>
                    <p><strong>Reviewdatum:</strong> 12 juni 2024</p>
                    <p><strong>Beoordeling:</strong> ★★★★☆</p>
                    <div class="details">
                        <p><strong>Makers:</strong> Naam Makers</p>
                        <p><strong>Muziek:</strong> Naam Muziek</p>
                        <p><strong>Genre:</strong> Genre van de Podcast</p>
                    </div>
                    <p>Hier komt een gedetailleerde review van de podcast. Beschrijf waar de podcast over gaat, wat je ervan vond, en waarom anderen het zouden moeten luisteren.</p>
                </div>
                <!-- Voeg hier meer reviews toe -->
            </div>
        </section>
        <section id="favorites">
            <h2>Favoriete Podcasts</h2>
            <div class="grid-container">
                <div class="post">
                    <h2>Titel van de Podcast</h2>
                    <p>Beschrijving van waarom deze podcast een favoriet is. Wat maakt deze podcast bijzonder en waarom zou je het aanbevelen?</p>
                </div>
                <!-- Voeg hier meer favorieten toe -->
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:ankosteenbeek@gmail.com">ankosteenbeek@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/ankosteenbeek/">https://www.linkedin.com/in/ankosteenbeek/</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 PodHorizon. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>