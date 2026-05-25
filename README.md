# projeto-agrinh
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Agrinho | Conexão Campo e Cidade</title>
    <style>
        :root {
            --verde: #2e7d32;
            --verde-claro: #81c784;
            --amarelo: #fbc02d;
            --escuro: #333333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        header {
            background-color: var(--verde);
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: var(--verde-claro);
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: var(--escuro);
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
            text-align: center;
        }

        .alternar-fundo {
            background-color: #f1f8e9;
        }

        h2 {
            color: var(--verde);
            margin-bottom: 20px;
        }

        .botao {
            display: inline-block;
            background-color: var(--amarelo);
            color: var(--escuro);
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .botao:hover {
            background-color: #f57f17;
            color: white;
        }

        footer {
            background-color: var(--escuro);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Agrinho Tech: Conectando Campo e Cidade</h1>
        <p>Inovação e Tecnologia com Alura Start</p>
    </header>

    <nav>
        <a href="#sobre">Sobre o Projeto</a>
        <a href="#tecnologia">A Tecnologia</a>
        <a href="#jogo">Nosso Projeto</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="sobre">
        <h2>O que é o nosso projeto?</h2>
        <p>Nosso trabalho para o concurso Agrinho busca aproximar as realidades do campo e da cidade através da tecnologia. Desenvolvemos uma solução interativa para conscientizar as pessoas sobre a importância da agricultura sustentável e o papel dos alimentos na nossa mesa.</p>
    </section>

    <section id="tecnologia" class="alternar-fundo">
        <h2>Como criamos com Alura Start</h2>
        <p>Utilizamos a plataforma **
