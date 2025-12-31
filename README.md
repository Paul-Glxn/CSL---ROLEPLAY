<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>CSL - ROLEPLAY</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            color: #ffffff;
            background:
                linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee");
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(15, 15, 15, 0.85);
            padding: 15px 0;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline-block;
            margin: 0 20px;
        }

        nav ul li a {
            color: #ffffff;
            text-decoration: none;
            font-size: 16px;
            letter-spacing: 1px;
        }

        nav ul li a:hover {
            color: #ffb347;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 140px 20px 80px;
        }

        h1 {
            font-size: 52px;
            letter-spacing: 3px;
            margin-bottom: 10px;
            text-align: center;
        }

        .subtitle {
            text-align: center;
            font-size: 18px;
            color: #cccccc;
            margin-bottom: 50px;
        }

        .card {
            background: rgba(20, 20, 20, 0.75);
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        .card p {
            font-size: 18px;
            line-height: 1.7;
        }

        .highlight {
            border-left: 4px solid #ffb347;
            padding-left: 20px;
            font-weight: bold;
        }

        .join {
            text-align: center;
            margin-top: 50px;
        }

        .join h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .join-buttons a {
            display: inline-block;
            margin: 15px;
            padding: 15px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: #0f0f0f;
            background: #ffb347;
        }

        .join-buttons a:hover {
            background: #ffd18a;
        }

        .socials {
            margin-top: 60px;
            text-align: center;
        }

        .socials a {
            display: inline-block;
            margin: 10px 15px;
            color: #ffb347;
            text-decoration: none;
            font-size: 18px;
        }

        .socials a:hover {
            text-decoration: underline;
        }

        footer {
            margin-top: 70px;
            text-align: center;
            font-size: 14px;
            color: #aaaaaa;
        }
    </style>
</head>
<body>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#about">Über uns</a></li>
            <li><a href="#join">Join</a></li>
            <li><a href="#socials">Socials</a></li>
        </ul>
    </nav>

    <div class="container">
        <h1>CSL – ROLEPLAY</h1>
        <div class="subtitle">American Setting • Midcore Roleplay • FiveM Server</div>

        <div class="card" id="about">
            <p>
                CSL – Roleplay ist ein FiveM Server mit starkem Fokus auf amerikanische Settings.
                Wir bieten ein realistisches Midcore-Roleplay-Erlebnis,
                bei dem Qualität, Struktur und sauberes RP im Vordergrund stehen.
            </p>

            <p>
                Ob ziviles Leben, Crime, Polizei oder Business –
                bei CSL kannst du deine eigene Story in einer glaubwürdigen
                und lebendigen Welt schreiben.
            </p>
        </div>

        <div class="card highlight">
            Ohne Pablo und Julian wäre dieses Projekt nicht möglich.
            Sie sind das Fundament der Entwicklung –
            ohne ihren Einsatz, ihre Zeit und ihre Vision gäbe es CSL – Roleplay nicht.
        </div>

        <div class="join" id="join">
            <h2>Jetzt beitreten</h2>
            <div class="join-buttons">
                <a href="https://discord.gg/aSbmDyr88H" target="_blank">Discord beitreten</a>
                <a href="https://cfx.re/join/jy3kvk" target="_blank">Direkt auf FiveM joinen</a>
            </div>
        </div>

        <div class="socials" id="socials">
            <a href="https://www.youtube.com/@CSL-1.0" target="_blank">YouTube</a>
            <a href="https://www.tiktok.com/@project.california.fivem?is_from_webapp=1&sender_device=pc" target="_blank">TikTok</a>
            <a href="https://www.twitch.tv/projectcalifornia" target="_blank">Twitch</a>
        </div>

        <footer>
            © CSL – Roleplay | Project California
        </footer>
    </div>

</body>
</html>

