<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Use os pincéis corretos</title>
    <style>
        body {
            font-family: "Poppins", Arial, sans-serif;
            background: linear-gradient(135deg, #fbd3e9, #bb377d);
            margin: 0;
            padding: 0;
            color: #333;
        }

        h1 {
            font-size: 2.2em;
            color: #fff;
            text-align: center;
            margin-top: 40px;
            text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
        }

        .container {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
            min-height: 80vh;
            padding: 40px;
        }

        .text-box {
            background-color: rgba(255, 255, 255, 0.85);
            padding: 40px 50px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.15);
            max-width: 450px;
            margin: 20px;
            text-align: left;
        }

        p {
            font-size: 1.1em;
            line-height: 1.7em;
            margin-bottom: 12px;
        }

        b {
            color: #bb377d;
        }

        .image-box {
            margin: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .image-box img {
            width: 450px;
            max-width: 100%;
            border-radius: 15px;
            border: 5px solid #fff;
            box-shadow: 0 6px 20px rgba(0,0,0,0.25);
        }

        @media (max-width: 900px) {
            .container {
                flex-direction: column-reverse;
                text-align: center;
            }

            .text-box {
                text-align: center;
            }

            h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <h1>Use os pincéis corretos.</h1>

    <div class="container">
        <!-- Texto à esquerda -->
        <div class="text-box">
            <p>Para cada passo de maquiagem use o pincel certo.</p>
            <p><b>Pincel Flat Kabiki</b> para aplicar base.</p>
            <p><b>Pincel pequeno pontiagudo</b> para aplicar corretivo.</p>
            <p><b>Pincel grande e fofo</b> para aplicar pó solto.</p>
            <p><b>Pincel pequeno com cerdas longas</b> para aplicar sombra.</p>
        </div>

        <!-- Imagem à direita -->
        <div class="image-box">
            <img src="PINCEIS.png" alt="Pincéis de maquiagem">
        </div>
    </div>
</body>
</html>
