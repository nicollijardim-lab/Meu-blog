# Meu-blog
bem vindo (a) ao meu blog
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O Poder da Empatia - Blog</title>
  <!-- Ícones do FontAwesome para os botões de Like/Dislike -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header class="header">
    <div class="container">
      <h1 class="logo">Blog Empatia</h1>
      <nav>
        <a href="#">Home</a>
        <a href="#">Artigos</a>
        <a href="#">Sobre</a>
      </nav>
    </div>
  </header>

  <main class="container content">
    <article class="post">
      <h2>O Poder da Empatia: Conectando Pessoas e Transformando Vidas</h2>
      <p class="meta">Publicado em 2026 | Por Maria Silva</p>

      <!-- Imagem principal via Link -->
      <img src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=1000&q=80" alt="Pessoas se abraçando e demonstrando empatia" class="post-img">

      <p>A empatia é a capacidade de se colocar no lugar do outro, buscando compreender seus sentimentos e perspectivas. Em um mundo cada vez mais conectado digitalmente, mas por vezes distante interpessoalmente, praticar a empatia torna-se um pilar fundamental para relações saudáveis.</p>

      <h3>Como Praticar no Dia a Dia?</h3>
      <p>Praticar a escuta ativa, suspender julgamentos precipitados e demonstrar interesse genuíno pelas histórias alheias são passos simples que transformam nossa convivência em sociedade.</p>

      <!-- Segunda Imagem via Link -->
      <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=1000&q=80" alt="Pessoas conversando e escutando com atenção" class="post-img">

      <!-- Seção de Feedback com Links de Like / Dislike -->
      <div class="feedback-container">
        <p>Este artigo foi útil para você?</p>
        <div class="buttons">
          <a href="#like" class="btn btn-like">
            <i class="fa-solid fa-thumbs-up"></i> Gostei <span class="count">128</span>
          </a>
          <a href="#dislike" class="btn btn-dislike">
            <i class="fa-solid fa-thumbs-down"></i> Não Gostei <span class="count">4</span>
          </a>
        </div>
      </div>
    </article>
  </main>

  <footer class="footer">
    <p>&copy; 2026 Blog Empatia. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
  background-color: #f4f6f8;
  color: #333;
  line-height: 1.6;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Header */
.header {
  background-color: #2c3e50;
  color: #fff;
  padding: 20px 0;
}

.header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header nav a {
  color: #fff;
  text-decoration: none;
  margin-left: 15px;
  transition: opacity 0.2s;
}

.header nav a:hover {
  opacity: 0.8;
}

/* Post Content */
.content {
  margin-top: 30px;
  margin-bottom: 40px;
}

.post {
  background: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
}

.post h2 {
  color: #2c3e50;
  margin-bottom: 10px;
}

.post .meta {
  font-size: 0.85rem;
  color: #7f8c8d;
  margin-bottom: 20px;
}

.post-img {
  width: 100%;
  height: 350px;
  object-fit: cover;
  border-radius: 6px;
  margin: 20px 0;
}

.post p {
  margin-bottom: 15px;
}

/* Botões de Like e Dislike */
.feedback-container {
  margin-top: 30px;
  padding-top: 20px;
  border-top: 1px solid #eee;
  text-align: center;
}

.feedback-container p {
  font-weight: bold;
  margin-bottom: 15px;
  color: #555;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 15px;
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 10px 20px;
  border-radius: 20px;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.3s ease;
}

.btn-like {
  background-color: #e8f5e9;
  color: #2e7d32;
  border: 1px solid #a5d6a7;
}

.btn-like:hover {
  background-color: #2e7d32;
  color: #fff;
}

.btn-dislike {
  background-color: #ffebee;
  color: #c62828;
  border: 1px solid #ef9a9a;
}

.btn-dislike:hover {
  background-color: #c62828;
  color: #fff;
}

.count {
  font-size: 0.85rem;
  opacity: 0.8;
}

/* Footer */
.footer {
  text-align: center;
  padding: 20px;
  background-color: #ecf0f1;
  color: #7f8c8d;
  font-size: 0.9rem;
}
