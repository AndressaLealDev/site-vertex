<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Vertex Construtora</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0; padding: 0;
            background-color: #f4f6f8;
            color: #333;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        nav {
            background-color: #005f99;
            padding: 15px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            max-width: 900px;
            margin: 30px auto;
            background: white;
            padding: 25px 30px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        section h2 {
            color: #007acc;
            margin-top: 0;
        }
        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        .contact-links a {
            display: inline-block;
            margin-right: 20px;
            text-decoration: none;
            color: #007acc;
            font-weight: 600;
            font-size: 1.1em;
            transition: color 0.3s ease;
        }
        .contact-links a:hover {
            color: #004a75;
        }
        /* Ícones simples */
        .contact-links a::before {
            content: '';
            display: inline-block;
            vertical-align: middle;
            margin-right: 8px;
            width: 20px;
            height: 20px;
            background-size: contain;
            background-repeat: no-repeat;
        }
        .contact-links a.instagram::before {
            background-image: url('https://cdn-icons-png.flaticon.com/512/87/87390.png');
        }
        .contact-links a.whatsapp::before {
            background-image: url('https://cdn-icons-png.flaticon.com/512/733/733585.png');
        }
        /* Responsividade simples */
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
            section {
                margin: 20px 10px;
                padding: 20px 15px;
            }
            .contact-links a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Vertex Construtora</h1>
    <p>Reformas e Pinturas com Qualidade</p>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Somos especialistas em reformas residenciais e comerciais, oferecendo serviços com qualidade e confiança.</p>
</section>

<section id="servicos">
    <h2>Serviços</h2>
    <ul>
        <li>Reformas completas</li>
        <li>Pintura interna e externa</li>
        <li>Acabamentos e reparos</li>
    </ul>
</section>

<section id="contato">
    <h2>Contato</h2>
    <p>Email: contato@vertexconstrutora.com.br</p>
    <p>Telefone: (41) 998545885</p>
    <div class="contact-links">
        <a href="https://www.instagram.com/vertexconstrutora" target="_blank" rel="noopener" class="instagram">Instagram</a>
        <a href="https://wa.me/5598545885" target="_blank" rel="noopener" class="whatsapp">WhatsApp</a>
    </div>
</section>

<footer>
    <p>© 2025 Vertex Construtora - Todos os direitos reservados</p>
</footer>

</body>
</html>

