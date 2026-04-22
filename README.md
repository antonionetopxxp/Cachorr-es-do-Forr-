<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cachorrões do</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
:root{
    --primary:#ff3c00;
    --dark:#1a1a1a;
    --bg:#0f0f0f;
    --text:#ffffff;
}

*{margin:0;padding:0;box-sizing:border-box;font-family:sans-serif;}

body{
    background:var(--bg);
    color:var(--text);
}

/* HEADER */
header{
    background:linear-gradient(135deg,#ff3c00,#ff8800);
    padding:30px 15px;
    text-align:center;
}

header h1{
    font-size:2rem;
    font-weight:900;
}

header p{
    font-size:0.9rem;
    opacity:0.9;
}

/* CONTAINER */
.container{
    max-width:1000px;
    margin:auto;
    padding:20px;
}

/* VIDEOS */
.video-grid{
    display:grid;
    grid-template-columns:1fr;
    gap:20px;
}

@media(min-width:700px){
    .video-grid{
        grid-template-columns:1fr 1fr;
    }
}

.video-card{
    background:#1c1c1c;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 5px 20px rgba(0,0,0,0.4);
}

.video-card iframe{
    width:100%;
    height:200px;
    border:none;
}

.video-info{
    padding:12px;
    text-align:center;
}

/* BOTÕES */
.social-buttons{
    display:flex;
    justify-content:center;
    gap:15px;
    margin-top:25px;
}

.social-buttons a{
    padding:12px 18px;
    border-radius:8px;
    text-decoration:none;
    color:#fff;
    font-weight:bold;
    display:flex;
    align-items:center;
    gap:8px;
    transition:0.3s;
}

.whatsapp{
    background:#25d366;
}

.instagram{
    background:#e1306c;
}

.social-buttons a:hover{
    transform:scale(1.08);
}

/* FLOAT WHATS */
.whatsapp-float{
    position:fixed;
    bottom:20px;
    right:20px;
    width:55px;
    height:55px;
    background:#25d366;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:28px;
    color:#fff;
    text-decoration:none;
    box-shadow:0 4px 15px rgba(0,0,0,0.4);
}

/* FOOTER */
footer{
    text-align:center;
    padding:20px;
    font-size:0.8rem;
    opacity:0.6;
}
</style>
</head>

<body>

<header>
    <h1>🐶 Cachorrões do</h1>
    <p>O som que bate forte 🔥</p>
</header>

<main class="container">

    <h2 style="text-align:center;margin-bottom:20px;">🎵 Nossos Vídeos</h2>

    <div class="video-grid">

        <!-- VIDEO 1 -->
        <div class="video-card">
            <iframe src="https://www.youtube.com/embed/VIDEO1"></iframe>
            <div class="video-info">Show Ao Vivo</div>
        </div>

        <!-- VIDEO 2 -->
        <div class="video-card">
            <iframe src="https://www.youtube.com/embed/VIDEO2"></iframe>
            <div class="video-info">Clipe Oficial</div>
        </div>

        <!-- VIDEO 3 -->
        <div class="video-card">
            <iframe src="https://www.youtube.com/embed/VIDEO3"></iframe>
            <div class="video-info">Melhores Momentos</div>
        </div>

    </div>

    <!-- BOTÕES -->
    <div class="social-buttons">

        <a href="https://wa.me/SEUNUMERO" target="_blank" class="whatsapp">
            <i class="fab fa-whatsapp"></i> WhatsApp
        </a>

        <a href="https://instagram.com/SEUINSTAGRAM" target="_blank" class="instagram">
            <i class="fab fa-instagram"></i> Instagram
        </a>

    </div>

</main>

<footer>
© 2026 Cachorrões do — Todos os direitos reservados
</footer>

<!-- BOTÃO FLUTUANTE -->
<a href="https://wa.me/SEUNUMERO" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
</a>

</body>
</html>
