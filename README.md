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
