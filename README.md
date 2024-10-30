<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
        }

        .container {
            width: 80%;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        header h1 {
            font-size: 2em;
            color: #5b5b8a;
            text-align: center;
            margin-bottom: 20px;
        }

        .about, .skills {
            background-color: #ffffff;
            border-radius: 8px;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .about h2, .skills h2 {
            color: #4a4a68;
            margin-bottom: 10px;
        }

        ul {
            list-style-type: none;
            padding-left: 20px;
        }

        ul li {
            margin: 10px 0;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Ahoj, jsem [Tvé Jméno]!</h1>
        </header>
        
        <section class="about">
            <h2>O mně</h2>
            <p>👨‍💻 Jsem [Tvá profese nebo studium, např. "software developer", "student informatiky"]. Baví mě [něco konkrétního, co tě zajímá – např. vývoj webových aplikací, analýza dat, práce s IoT]. Mým cílem je tvořit software, který má pozitivní dopad na lidi a společnosti.</p>
            <ul>
                <li>📍 Působím v [město, stát]</li>
                <li>💼 Pracuji v [název společnosti] nebo studuji na [název univerzity]</li>
            </ul>
        </section>
        
        <section class="skills">
            <h2>🔧 Technologie a Nástroje</h2>
            <p>Seznam technologií, které ovládám, nebo nástrojů, se kterými pracuji:</p>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>Python, Django, Flask</li>
                <li>MySQL, MongoDB</li>
                <!-- Přidej další dle potřeby -->
            </ul>
        </section>
    </div>
</body>
</html>
