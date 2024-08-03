<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Roupas - UrbanX</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #111;
            color: #fff;
            padding: 15px 0;
            text-align: center;
            border-bottom: 2px solid #6a1b9a;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 15px 0;
        }
        nav a {
            color: #6a1b9a;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #222;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
        }
        h2 {
            color: #fff;
            border-bottom: 2px solid #6a1b9a;
            padding-bottom: 10px;
        }
        .catalog-section {
            margin-bottom: 30px;
        }
        .catalog-section h3 {
            color: #6a1b9a;
            margin-top: 0;
        }
        .item {
            border: 1px solid #444;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            background-color: #333;
        }
        .item img {
            max-width: 150px;
            height: auto;
            border-radius: 5px;
        }
        .item-details {
            display: flex;
            gap: 15px;
        }
        .item-details p {
            margin: 0;
            color: #aaa;
        }
        .contact-form {
            margin-top: 20px;
        }
        .contact-form label {
            display: block;
            margin: 10px 0 5px;
            color: #fff;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #444;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #6a1b9a;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        .contact-form button:hover {
            background-color: #4e148c;
        }
        footer {
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 10px;
            border-top: 2px solid #6a1b9a;
        }
    </style>
</head>
<body>
    <header>
        <h1>Catálogo de Roupas - UrbanX</h1>
        <nav>
            <a href="#disponiveis">Peças Disponíveis</a>
            <a href="#esgotadas">Esgotadas</a>
            <a href="#futuras">Futuras</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <div class="container">
        <section id="disponiveis" class="catalog-section">
            <h2>Peças Disponíveis</h2>
            <div class="item">
                <h3>Blusa Casual</h3>
                <div class="item-details">
                    <img src="blusa-casual.jpg" alt="Blusa Casual">
                    <p>Tamanhos: P, M, G, GG</p>
                </div>
                <p>Descrição: Blusa casual confortável e estilosa.</p>
            </div>
            <!-- Adicione mais itens aqui -->
        </section>

        <section id="esgotadas" class="catalog-section">
            <h2>Peças Esgotadas</h2>
            <div class="item">
                <h3>Blusa Elegante</h3>
                <div class="item-details">
                    <img src="blusa-elegante.jpg" alt="Blusa Elegante">
                    <p>Tamanhos: M, G</p>
                </div>
                <p>Descrição: Blusa elegante, ideal para eventos formais.</p>
            </div>
            <!-- Adicione mais itens aqui -->
        </section>

        <section id="futuras" class="catalog-section">
            <h2>Peças Futuras</h2>
            <div class="item">
                <h3>Blusa de Inverno</h3>
                <div class="item-details">
                    <img src="blusa-inverno.jpg" alt="Blusa de Inverno">
                    <p>Tamanhos: P, M, G, GG</p>
                </div>
                <p>Descrição: Blusa de inverno que estará disponível em breve.</p>
            </div>
            <!-- Adicione mais itens aqui -->
        </section>

        <section id="contato" class="catalog-section">
            <h2>Contato</h2>
            <form class="contact-form">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 UrbanX. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
