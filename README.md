# Save the updated HTML content to a file with IMDb-inspired design
imdb_style_html_content = """
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
    <div class