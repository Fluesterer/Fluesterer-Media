<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fluesterer Media</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #6e7e8f, #3b4e62);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;
            flex-direction: column;
        }
        .container {
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            width: 90%;
            max-width: 450px;
            text-align: center;
            backdrop-filter: blur(10px);
            margin-bottom: 20px;
        }
        h1 {
            font-size: 2.5em;
            color: #ffcc00;
            margin-bottom: 25px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .link-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .link-container a {
            display: block;
            padding: 18px;
            background: linear-gradient(145deg, #ff6a00, #ff8e00);
            color: white;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 8px;
            transition: all 0.3s ease;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
        }
        .link-container a:hover {
            background: linear-gradient(145deg, #ff8e00, #ff6a00);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
            transform: translateY(-3px);
        }
        .link-container a:active {
            background: linear-gradient(145deg, #ff6a00, #ff8e00);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
            transform: translateY(0);
        }
        .footer {
            position: absolute;
            bottom: 20px;
            right: 20px;
            font-size: 0.9em;
            color: white;
            text-align: right;
        }
        .footer a {
            color: #ffcc00;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Fluesterer Media</h1>
        <div class="link-container">
            <a href="https://www.youtube.com/@FluestererYT" target="_blank">YouTube Kanal besuchen</a>
            <a href="https://www.roblox.com/de/users/5565076645/profile" target="_blank">Roblox Profil besuchen</a>
            <a href="https://www.roblox.com/de/communities/35060056/Die-Fl-sternen#!/about" target="_blank">Roblox Gruppe besuchen</a>
            <a href="https://discord.gg/HWtUsY8Cqd" target="_blank">Discord Server besuchen</a>
            <a href="javascript:void(0);" onclick="showLinks()">Alle Links</a>
        </div>
    </div>

    <div class="footer">
        <p>Made <br>by <br>Fluesterer</p>
    </div>

    <div id="all-links" style="display: none; color: white; text-align: center; margin-top: 20px;">
        <p><a href="https://www.youtube.com/@FluestererYT" target="_blank">fluestereryt kanal besuchen</a></p>
        <p><a href="https://www.roblox.com/de/users/5565076645/profile" target="_blank">roblox profil besuchen</a></p>
        <p><a href="https://www.roblox.com/de/communities/35060056/Die-Fl-sternen#!/about" target="_blank">roblox gruppe besuchen</a></p>
        <p><a href="https://discord.gg/HWtUsY8Cqd" target="_blank">discord server besuchen</a></p>
    </div>

    <script>
        function showLinks() {
            var linksDiv = document.getElementById("all-links");
            if (linksDiv.style.display === "none") {
                linksDiv.style.display = "block";
            } else {
                linksDiv.style.display = "none";
            }
        }
    </script>

</body>
</html>
