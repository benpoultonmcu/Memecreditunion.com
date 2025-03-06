<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meme Credit Union</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="meme-background">
        <p class="meme-text">MEME CREDIT UNION</p>
    </div>
</body>
</html>

/* style.css */
body {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #ffffff;
}

.meme-text {
    font-family: 'Impact', sans-serif;
    font-size: 4em;
    color: white;
    text-transform: uppercase;
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
    letter-spacing: 2px;
    padding: 10px;
}

.meme-background {
    background-color: #4B2E83;
    border: 5px solid #D32F2F;
    border-radius: 50%;
    width: 300px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

.meme-text:hover {
    transform: scale(1.1);
    transition: transform 0.2s ease-in-out;
}
