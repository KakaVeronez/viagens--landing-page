# viagens--landing-page
Projeto de certificação 1 – Agência de Viagem
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vilarejo Europeu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        nav {
            background-color: #2c3e50;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: #ecf0f1;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #f39c12;
        }

        main {
            margin: 20px;
        }

        #banner {
            background-image: url('[https://via.placeholder.com/1500x400](https://cdn.abjnoticias.com.br/abjnoticias-home/2023/11/viagem_america-scaled.jpg)'); 
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            position: relative;
        }

        #banner h1 {
            font-size: 48px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            margin: 0;
        }

        section {
            padding: 40px 20px;
            margin-bottom: 20px;
        }

        #tripme {
            background-color: #ecf0f1;
        }

        #meetus {
            background-color: #f7f7f7;
        }

        #advice {
            background-color: #ecf0f1;
        }

        footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        .section-title {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .section-content {
            font-size: 18px;
            line-height: 1.6;
        }

        .back-to-top {
            display: block;
            margin-top: 20px;
            text-align: center;
            color: #2c3e50;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .back-to-top:hover {
            color: #f39c12;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#tripme">MinhaViagem</a>
        <a href="#meetus">NosEncontre</a>
        <a href="#advice">Conselhos</a>
    </nav>

    <main>
        <section id="banner">
            <h1>Explore o Vilarejo dos Seus Sonhos</h1>
        </section>

        <section id="tripme">
            <h2 class="section-title">MinhaViagem</h2>
            <p class="section-content">Descubra as melhores rotas e passeios neste vilarejo encantador.</p>
            <a href="#banner" class="back-to-top">Voltar ao topo</a>
        </section>

        <section id="meetus">
            <h2 class="section-title">NosEncontre</h2>
            <p class="section-content">Veja como chegar ao vilarejo e entre em contato conosco para mais informações.</p>
            <a href="#banner" class="back-to-top">Voltar ao topo</a>
        </section>

        <section id="advice">
            <h2 class="section-title">Conselhos</h2>
            <p class="section-content">Dicas de viagem, o que levar, e como aproveitar ao máximo sua estadia.</p>
            <a href="#banner" class="back-to-top">Voltar ao topo</a>
        </section>
    </main>

    <footer>
        &copy; 2024 Vilarejo Europeu - Todos os direitos reservados.
    </footer>
</body>
</html>
