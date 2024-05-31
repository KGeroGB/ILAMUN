<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ILAMUN</title>
    <style>
        body {
            margin: 0;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
        #logoie {
            position: absolute;
            top: 10px;
            left: 10px;
            width: 110px;
        }
        #logo {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 150px;
        }
        .grid-container {
            display: grid;
            place-items: center;
            height: 100vh; /* Centra verticalmente en toda la pantalla */
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .large-space {
            margin-bottom: 1rem;
        }
        h1, h4 {
            text-align: center;
        }
        .content {
            padding: 1rem;
        }
        @media (max-width: 600px) {
            #logoie, #logo {
                width: 80px;
            }
            .grid-container {
                padding: 0 10px;
                height: auto; /* Ajusta la altura para pantallas pequeñas */
            }
            .large-space {
                margin-bottom: 0.8rem;
            }
            h1 {
                font-size: 1.5rem;
            }
            h4 {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <img id="logoie" src="I.E.png" alt="Logo IE">
    <img id="logo" src="ILAMUNLOGOSINFONDO.png" alt="Logo ILAMUN">
    
    <div class="grid-container">
        <img src="FORMANDO IDERES DEL MAÑANA.png" alt="Formando Líderes del Mañana">
    </div>
<br>
    <div class="content">
        <h1 class="large-space">¿Qué es ILAMUN?</h1>
        <h4>Es el modelo de las naciones unidas ILAMUN de la Institución Educativa La Madrid. Se creó en el año 2022, que fue también el primer año de nuestra institución en modalidad presencial. El proyecto se creó con el fin de generar espacios y ambientes en los cuales se puedan debatir temas globales llegando a un común acuerdo entre sí, de este modo, formar líderes del mañana.</h4>
    </div>
</body>
</html>
