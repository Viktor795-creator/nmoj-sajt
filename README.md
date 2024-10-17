
<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="Viktor Dimitrov" content="width=device-width, initial-scale=1.0">
    <title>Moj Lični Sajt</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Ime i Prezime</h1>
        <img src="!tvoja-slika.jpg" alt="![Uploading Screenshot_20240910-192627.png…]()
" class="profile-pic">
        <p class="profession">Gmail:viktordimitrov994@gmail.com</p>
        <p class="contact-info">Telefon: 0638803599</p>
        <div class="socials">
            <a href="https://discord.gg/G2gRRqfNMm" target="_blank">Prvi dicord</a>
            <a href="https://discord.gg/aEycKK8guy" target="_blank">Dugi discord Server</a>
        </div>
    </div>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 600px;
    margin: auto;
    padding: 20px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.profile-pic {
    width: 150px; /* Možeš prilagoditi veličinu */
    border-radius: 50%;
    margin-bottom: 20px;
}

.socials a {
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    color: #007bff;
}

.socials a:hover {
    text-decoration: underline;
}
