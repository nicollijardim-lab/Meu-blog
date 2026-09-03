# Meu-blog
bem vindo (a) ao meu blog
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoVida - Blog sobre a Natureza</title>
    <style>
        /* Estilos Gerais */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f8f5;
            color: #2d3748;
            line-height: 1.6;
        }

        /* Cabeçalho */
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                        url('https://images.unsplash.com/photo-1448375240586-882707db888b?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: #ffffff;
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Navegação */
        nav {
            background-color: #2e7d32;
            display: flex;
            justify-content: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav a {
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: #1b5e20;
        }

        /* Layout Principal */
        .container {
            max-width: 1100px;
            margin: 30px auto;
            padding: 0 20px;
            display: flex;
            gap: 30px;
        }

        /* Conteúdo dos Posts */
        .main-content {
     function botaoClicado() {
console.log("fui clicado");
let texto = botao.querySelector("span");

if (curtiu === false) {
texto.textContent++;
curtiu = true;
} else {
texto.textContent--;
curtiu = false;
}
}
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
