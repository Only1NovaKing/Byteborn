<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Byteborn: Cyberpunk RPG</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Byteborn</h1>
        <p>A Cyberpunk RPG on Pi Network</p>
    </header>
    <main>
        <section id="about">
            <h2>Neon Dreams Await</h2>
            <p>I'm BytebornDev, a daily Pi miner crafting <em>Byteborn</em>, a cyberpunk RPG on Pi App Studio (Beta). Explore Neon Sprawl with Fishing, Battling, & Customization. Join the Art Crew on Pixilart to create 8-bit neon sprites & earn credit! 13+ safe, no IP issues. Let’s spark Pi’s economy by Jan 2026! <a href="https://www.pixilart.com/groups/join-the-byteborn-art-team-3bb7885f37" target="_blank">Join Now</a></p>
        </section>
        <section id="credits">
            <h2>Artist Credits</h2>
            <ul id="artist-list"></ul>
        </section>
        <section id="prompt-reader">
            <h2>Submit Game Prompt</h2>
            <textarea id="prompt-input" maxlength="140" placeholder="Enter 140-character game prompt"></textarea>
            <button onclick="submitPrompt()">Submit</button>
            <p id="prompt-feedback"></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2026 [Tyler J Applegate]. Byteborn art owned by [Tyler J Applegate]. No IP copying. <a href="privacy.html">Privacy Policy</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Byteborn: Cyberpunk RPG</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Byteborn</h1>
        <p>A Cyberpunk RPG on Pi Network</p>
    </header>
    <main>
        <section id="about">
            <h2>Neon Dreams Await</h2>
            <p>I'm BytebornDev, a daily Pi miner crafting <em>Byteborn</em>, a cyberpunk RPG on Pi App Studio (Beta). Explore Neon Sprawl with Fishing, Battling, & Customization. Join the Art Crew on Pixilart to create 8-bit neon sprites & earn credit! 13+ safe, no IP issues. Let’s spark Pi’s economy by Jan 2026! <a href="https://www.pixilart.com/groups/join-the-byteborn-art-team-3bb7885f37" target="_blank">Join Now</a></p>
        </section>
        <section id="credits">
            <h2>Artist Credits</h2>
            <ul id="artist-list"></ul>
        </section>
        <section id="prompt-reader">
            <h2>Submit Game Prompt</h2>
            <textarea id="prompt-input" maxlength="140" placeholder="Enter 140-character game prompt"></textarea>
            <button onclick="submitPrompt()">Submit</button>
            <p id="prompt-feedback"></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2026 [Tyler J Applegate]. Byteborn art owned by [Tyler J Applegate]. No IP copying. <a href="privacy.html">Privacy Policy</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>


body {
    background: #1a1a1a;
    color: #00FFFF;
    font-family: 'Press Start 2P', cursive;
    margin: 0;
    padding: 0;
    text-align: center;
}
header {
    background: #FF00FF;
    padding: 20px;
}
h1 {
    font-size: 24px;
    color: #00FFFF;
}
h2 {
    font-size: 18px;
    margin: 20px 0;
}
p, a {
    font-size: 14px;
    color: #00FFFF;
}
a:hover {
    color: #FF00FF;
}
main {
    padding: 20px;
}
#credits ul {
    list-style: none;
    padding: 0;
}
#credits li {
    margin: 10px 0;
}
#prompt-input {
    width: 80%;
    max-width: 400px;
    height: 60px;
    background: #000;
    color: #00FFFF;
    border: 2px solid #FF00FF;
    font-family: 'Press Start 2P', cursive;
}
button {
    background: #FF00FF;
    color: #00FFFF;
    border: none;
    padding: 10px 20px;
    font-family: 'Press Start 2P', cursive;
    cursor: pointer;
}
button:hover {
    background: #00FFFF;
    color: #FF00FF;
}
footer {
    background: #FF00FF;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

// Artist credits (update with Pixilart usernames)
const artists = [
    { name: "ArtCrewUser1", contribution: "Neon Fish" },
    { name: "ArtCrewUser2", contribution: "Data Wraith" }
];

// Populate artist credits
const artistList = document.getElementById("artist-list");
artists.forEach(artist => {
    const li = document.createElement("li");
    li.textContent = `${artist.name}: ${artist.contribution}`;
    artistList.appendChild(li);
});

// Prompt submission (placeholder for feedback)
function submitPrompt() {
    const input = document.getElementById("prompt-input").value;
    const feedback = document.getElementById("prompt-feedback");
    if (input.length > 0 && input.length <= 140) {
        feedback.textContent = "Prompt submitted! We’ll review it for Byteborn.";
        feedback.style.color = "#00FFFF";
    } else {
        feedback.textContent = "Prompt must be 1–140 characters.";
        feedback.style.color = "#FF00FF";
    }
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Byteborn P<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Byteborn Privacy Policy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Byteborn Privacy Policy</h1>
    </header>
    <main>
        <p><em>Byteborn</em> collects no data on this site. The game uses Pi API for username and PGS transactions, 13+ safe, 18+ for Pi mining per Pi Network’s KYC. Contact: byteborn.art@gmail.com</p>
        <a href="index.html">Back to Home</a>
    </main>
    <footer>
        <p>&copy; 2026 [Tyler J Applegate].</p>
    </footer>
</body>
</html>rivacy Policy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Byteborn Privacy Policy</h1>
    </header>
    <main>
        <p><em>Byteborn</em> collects no data on this site. The game uses Pi API for username and PGS transactions, 13+ safe, 18+ for Pi mining per Pi Network’s KYC. Contact: byteborn.art@gmail.com</p>
        <a href="index.html">Back to Home</a>
    </main>
    <footer>
        <p>&copy; 2026 Tyler J Applegate.</p>
    </footer>
</body>
</html>
