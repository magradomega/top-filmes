<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Top 5 Filmes</title>

    <style>
        /* 1. Seletor de elemento */
        body {
            background-color: black;
            color: white;
            font-family: Arial;
            text-align: center;
        }

        /* 2. Seletor de ID */
        #titulo {
            color: cyan;
        }

        /* 3. Seletor de classe */
        .filme {
            margin: 10px;
        }

        /* 4. Pseudo-classe */
        .filme:hover {
            color: yellow;
        }

        /* 5. Seletor descendente */
        .filme img {
            border: 2px solid white;
        }
    </style>
</head>

<body>

    <!-- CSS inline -->
    <h1 id="titulo" style="font-size: 30px;">
        🎬 Top 5 Filmes
    </h1>

    <div class="filme">
        <img src="https://upload.wikimedia.org/wikipedia/en/d/d6/Avatar_%282009_film%29_poster.jpg" width="150">
        <p>Avatar</p>
    </div>

    <div class="filme">
        <img src="https://upload.wikimedia.org/wikipedia/en/0/0d/Avengers_Endgame_poster.jpg" width="150">
        <p>Vingadores: Ultimato</p>
    </div>

    <div class="filme">
        <img src="https://upload.wikimedia.org/wikipedia/en/2/22/Titanic_poster.jpg" width="150">
        <p>Titanic</p>
    </div>

    <div class="filme">
        <img src="https://upload.wikimedia.org/wikipedia/en/a/a2/Star_Wars_The_Force_Awakens_poster.jpg" width="150">
        <p>Star Wars</p>
    </div>

    <div class="filme">
        <img src="https://upload.wikimedia.org/wikipedia/en/4/4d/Avengers_Infinity_War_poster.jpg" width="150">
        <p>Guerra Infinita</p>
    </div>

    <footer style="margin-top:20px;">
        <p>Site simples</p>
    </footer>

</body>
</html>
