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
            "Russell Wilson",
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

<button id="notebooks" onclick='toggleNotebooks()'>Open Notebooks</button>

<div id="notebook">
  <button onclick='window.location.href="{{ site.baseurl }}/2024/09/10/SongSearch.html"'>iTunes Music Finder</button>
  <br>
  <button onclick='window.location.href="{{ site.baseurl }}/2024/09/12/HTMLBasics_IPYNB_2_.html"'>HTML Basics</button>
  <br>
  <button onclick='window.location.href="{{ site.baseurl }}/about"'>About Me</button>
</div>

<script>
    function toggleNotebooks() {
    const container = document.getElementById("notebook");

    if(container.style.display == "none") {
      container.style.display = "block";
    } else {
      container.style.display = "none";
    }
  }
</script>

<style> 
@import url('https://fonts.googleapis.com/css2?family=Roboto');
h1{ text-align: center; font-size: 50px; color: #0352fc; font-family: 'Roboto', serif;}
h2{ text-align: left; font-size: 18px; color: #0352fc;}
body{ text-align: left; font-size: 15px; font-family: 'Roboto', serif; background: black; }
</style>