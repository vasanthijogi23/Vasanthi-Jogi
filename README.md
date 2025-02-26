# Vasanthi-Jogi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding of [Your Names]</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-image: url('floral-bg.jpg');
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            text-align: center;
            color: #4A4A4A;
        }
        header {
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Wedding</h1>
        <p>Join us in celebrating our special day!</p>
        <p>Date: February 28, 2026</p>
        <p>Venue: Pondicherry</p>
        <a href="https://www.google.com/maps">View Location</a>
    </header>
    
    <section id="countdown">
        <h2>Countdown to Our Big Day</h2>
        <div id="timer"></div>
    </section>
    
    <section id="our-story">
        <h2>Our Story</h2>
        <p>[Add your love story here]</p>
    </section>
    
    <section id="gallery">
        <h2>Photo Gallery</h2>
        <input type="file" id="upload-photo" multiple>
        <div id="photo-gallery"></div>
    </section>
    
    <section id="rsvp">
        <h2>RSVP</h2>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" required>
            <label for="attendance">Will you attend?</label>
            <select id="attendance">
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>
            <button type="submit">Submit</button>
        </form>
    </section>
    
    <section id="music">
        <h2>Enjoy the Wedding Vibes</h2>
        <audio controls autoplay loop>
            <source src="indian-music.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </section>
    
    <script src="script.js"></script>
</body>
</html>
