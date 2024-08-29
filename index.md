---
layout: base
title: Eshaan Kumar's CSA Student Blog 
description: Home Page
hide: true
---

# Eshaan Kumar
## CSA Student Blog

![Alt text](images/aboutme.jpg)

<style>
    body {
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
        background-color: black; /* Optional: black background for contrast */
    }
    button {
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
        background-color: yellow; /* Optional: yellow button */
        border: none;
    }
    #playerDisplay {
        margin-top: 20px;
        font-size: 24px;
        font-weight: bold;
        color: yellow; /* Bright yellow text color */
    }
</style>
<body>
<button onclick="displayRandomPlayer()">Pick a Player</button>

    <div id="playerDisplay"></div>

    <script>
        const players = [
            "Russel Wilson",
            "Najee Harris",
            "George Pickens",
            "T.J. Watt",
            "Minkah Fitzpatrick",
            "Cam Heyward",
            "Pat Freiermuth",
            "Justin Fields",
            "Joey Porter Jr.",
            "Alex Highsmith"
        ];

        function displayRandomPlayer() {
            const randomIndex = Math.floor(Math.random() * players.length);
            const selectedPlayer = players[randomIndex];
            document.getElementById("playerDisplay").innerText = selectedPlayer;
        }
    </script>
</body>
