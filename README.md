DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miguel Cândido - Siga-me nas Redes</title>
    <link rel="stylesheet" href="styles.css">
    <script src="scripts.js" defer></script>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="foto.png" alt="Foto de Miguel Cândido" class="profile-photo">
            <h1>Miguel Cândido</h1>
            <p>Bem-vindo(a) às minhas redes! Não esqueça de se inscrever no meu canal e me seguir no Instagram para mais conteúdos incríveis!</p>
        </div>
        <div class="social-links">
            <a href="https://youtube.com/@miguelcandidopr018?si=ZyPq_WUzqOad80ry" class="button youtube" target="_blank">Inscreva-se no YouTube</a>
            <a href="https://www.instagram.com/miguelcandidopr18/" class="button instagram" target="_blank">Siga-me no Instagram</a>
        </div>
        <div class="contact-form">
            <h2>Entre em contato</h2>
            <form action="form-handler.php" method="POST" onsubmit="return validateForm()">
                <input type="text" name="nome" placeholder="Seu nome" required>
                <input type="email" name="email" placeholder="Seu email" required>
                <textarea name="mensagem" placeholder="Sua mensagem" required></textarea>
                <button type="submit" class="button submit">Enviar</button>
            </form>
        </div>
    </div>
</body>
</html>
