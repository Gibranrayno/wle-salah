<!DOCTYPE html>
<html lang="en">

<head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A heartfelt birthday celebration page for Wanda with photos and a special message.">
    <title>Happy Birthday, Wanda!</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fffad7;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 700px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }

        h1 {
            font-size: 2rem;
            color: #b47b38;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1rem;
            color: #b47b38;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px 0;
        }

        .photo-gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            margin: 10px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .photo-gallery img:hover {
            transform: scale(1.1);
        }

        .message-box {
            background-color: #fff8da;
            border: 2px solid #fffad7;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .message-box p {
            margin-bottom: 10px;
        }

        footer {
            margin-top: 30px;
            font-size: 0.9rem;
            color: #999;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Happy Birthday, Wanda!</h1>
        <h2>Wishing you the best day ever.</h2>
        <p>You deserve all the joy and happiness in the world. I'm so grateful to have you in my life. Here's to many
            more years of walking through together, laughter, and amazing memories!</p>

        <div class="photo-gallery">
            <img src="Happy.jpg" alt="Happy image">
            <img src="Candle.jpg" alt="Candle image">
            <img src="Special.jpg" alt="Special image">
            <img src="Foryou.jpg" alt="For you image">
        </div>

        <div class="message-box">
            <h2>A Special Message for You</h2>
            <p>Thank you for being the amazing person you are. Your kindness, humor, and loyalty really mean a lot to me.
                I’m so lucky to know you. May all your dreams come true this year and beyond.</p>
            <p>Happy Birthday!</p>
        </div>

        <footer>
            <p>Made with Love, by gibran</p>
        </footer>
    </div>

    <!-- Audio element -->
    <audio autoplay loop>
        <source src="Time of Our Life.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

</body>

</html>
