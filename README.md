<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Básico</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        a {
            color: #4CAF50;
            text-decoration: none;
        }
        .imagem-container {
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>

    <section>
        <h2>Sobre Mim</h2>
        <p>Olá! Este é um site básico feito para fins de demonstração. Aqui você pode aprender um pouco sobre HTML, CSS e como estruturar um site simples.</p>

        <div class="imagem-container">
            <img src="https://via.placeholder.com/600x300" alt="Imagem de exemplo">
        </div>

        <p>Se você está interessado em aprender mais, visite o <a href="https://www.w3schools.com/" target="_blank">W3Schools</a> para tutoriais e documentação sobre desenvolvimento web.</p>
    </section>

    <footer>
        <p>&copy; 2025 Meu Site Básico</p>
    </footer>

</body>
</html>
