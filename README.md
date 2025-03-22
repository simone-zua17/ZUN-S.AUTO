
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zun’s Auto - Landing Page</title>
    <style>
        /* Estilos gerais */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #222, #f8c102);
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8c102;
        }

        .search-bar {
            text-align: center;
            margin: 20px 0;
        }

        .search-bar input {
            padding: 10px;
            width: 300px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        section {
            padding: 40px;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .modelos, .contato, .historia, .ceo, .pagamento {
            background-color: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 800px;
        }

        .modelos img, .ceo img {
            width: 100%;
            border-radius: 8px;
        }

        .ceo img {
            width: 200px;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        .modelos h3, .ceo h3 {
            margin-top: 10px;
        }

        .buy-button {
            background-color: #f8c102;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
            transition: background 0.3s;
        }

        .buy-button:hover {
            background-color: #d9a400;
        }

        footer {
            background: linear-gradient(90deg, #f8c102, #222);
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Zun’s Auto</h1>
        <nav>
            <ul>
                <li><a href="#modelos">Modelos</a></li>
                <li><a href="#historia">História</a></li>
                <li><a href="#ceo">CEO</a></li>
                <li><a href="#pagamento">Pagamentos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <div class="search-bar">
        <input type="text" placeholder="Pesquise modelos ou peças...">
    </div>
    
    <section id="modelos" class="modelos">
        <h2>Modelos da Zun’s Auto</h2>
        <div class="container">
            <div>
                <img src="atlas.jpg" alt="Zun’s Atlas">
                <h3>Zun’s Atlas</h3>
                <p>Um SUV espaçoso e luxuoso, com tração sofisticada e um design marcante.</p>
                <p><strong>Preço: $50,000</strong></p>
                <a href="#" class="buy-button">Comprar</a>
            </div>
            <div>
                <img src="SUV.jpeg" alt="Zun’s Z-Prime">
                <h3>Zun’s Z-Prime</h3>
                <p>Modelo acessível e inovador, perfeito para quem busca eficiência e estilo.</p>
                <p><strong>Preço: $35,000</strong></p>
                <a href="#" class="buy-button">Comprar</a>
            </div>
        </div>
    </section>

    <section id="historia" class="historia">
        <h2>História da Zun’s Auto</h2>
        <p>A Zun’s Auto nasceu do sonho de criar veículos inovadores e acessíveis. Com um design marcante e tecnologia de ponta, a marca busca oferecer o melhor em mobilidade e conforto.</p>
    </section>

    <section id="ceo" class="ceo">
        <h2>Conheça o CEO</h2>
        <img src="CEO.jpeg" alt="Foto do CEO">
        <p>Simone Zua, fundador e CEO da Zun’s Auto, é apaixonado por inovação automotiva e está comprometido em trazer ao mercado veículos modernos e acessíveis para todos.</p>
    </section>

    <section id="pagamento" class="pagamento">
        <h2>Opções de Pagamento</h2>
        <p>Aceitamos pagamentos via:</p>
        <ul>
            <li>Cartão de Crédito (Visa, Mastercard, Multicaixa Express)</li>
            <li>Transferência Bancária</li>
            <li>Pagamento na Entrega</li>
        </ul>
    </section>
    
    <section id="contato" class="contato">
        <h2>Contato</h2>
        <p>Email: <a href="mailto:contato@zunsauto.com">contato@zunsauto.com</a></p>
        <p>Telefone: <a href="tel:+244924222612">+244 924 222 612</a></p>
        <p>Endereço: Luanda, Angola</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Zun’s Auto - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
