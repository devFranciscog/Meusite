<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="htmlico.ico" type="image/x-icon">
    <title>Minha Lista de Leitura - Dev Gilvan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
        h1, h2, h3, h4 {
            color: #444;
        }
        hr {
            border: 0;
            height: 1px;
            background-color: #ccc;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #0066cc;
        }
        nav a:hover {
            text-decoration: underline;
        }
        img {
            display: block;
            margin: 10px auto;
            max-width: 100%;
            height: auto;
        }
        .content {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .book-section {
            margin-bottom: 40px;
        }
        details {
            margin: 20px 0;
            cursor: pointer;
        }
    </style>
</head>

<body>
    <header>
        <h1>Minha Lista de Leitura</h1>
        <h4>Dev Gilvan</h4>
        <hr>
        <nav>
            <p>Navegue entre as seções:</p>
            <a href="#titulo-1">Título 1</a>
            <a href="#titulo-2">Título 2</a>
            <a href="#titulo-3">Título 3</a>
        </nav>
    </header>

    <div class="content">
        <!-- Primeiro Livro -->
        <section class="book-section" id="titulo-1">
            <h2>Saga Senhor dos Anéis (J.R.R. Tolkien)</h2>
            <h3>O Senhor dos Anéis: A Sociedade do Anel</h3>
            <img src="sociedade-anel.jpg" alt="Capa do livro 'O Senhor dos Anéis: A Sociedade do Anel'">
            <p>
                <i>O Senhor dos Anéis: Sociedade do Anel</i>, escrito por <strong>J.J.R. Tolkien</strong>, é o primeiro volume da trilogia que narra a jornada épica na Terra-média. A história começa no Condado, onde Frodo Bolseiro, um hobbit, recebe um anel mágico de seu tio Bilbo. Este anel, na verdade, é o Um Anel, criado pelo Senhor do Escuro, Sauron. Frodo parte em uma jornada perigosa para destruir o anel.
            </p>
            <p>Acessar o trailer da adaptação:</p>
            <a href="https://youtu.be/0i86oM1nHjM?si=EBlTySCOaoCLzQ2P" target="_blank">O Senhor dos Anéis - A Sociedade do Anel</a>
            <details>
                <summary><strong>Comentário</strong></summary>
                <p><i>A Sociedade do Anel é uma obra-prima da fantasia que explora amizade, coragem e a luta entre o bem e o mal.</i></p>
            </details>
            <hr>
        </section>

        <!-- Segundo Livro -->
        <section class="book-section" id="titulo-2">
            <h3>O Senhor dos Anéis: As Duas Torres</h3>
            <img src="duas-torres.jpg" alt="Capa do livro 'O Senhor dos Anéis: As Duas Torres'">
            <p>
                <i>As Duas Torres</i>, o segundo volume da trilogia, continua a história épica após a separação da Sociedade do Anel. O livro é dividido em duas partes, acompanhando Frodo e Sam em sua jornada para Mordor e os outros membros enfrentando desafios e batalhas.
            </p>
            <p>Acessar o trailer da adaptação:</p>
            <a href="https://youtu.be/Al5iC4CnhYc?si=WRbwcfMptP6MsUwj" target="_blank">O Senhor dos Anéis: As Duas Torres</a>
            <details>
                <summary><strong>Comentário</strong></summary>
                <p><i>As Duas Torres é uma sequência intensa e envolvente, aprofundando personagens e desenvolvendo temas de coragem e lealdade.</i></p>
            </details>
            <hr>
        </section>

        <!-- Terceiro Livro -->
        <section class="book-section" id="titulo-3">
            <h3>O Senhor dos Anéis: O Retorno do Rei</h3>
            <img src="retorno-rei.jpg" alt="Capa do livro 'O Senhor dos Anéis: O Retorno do Rei'">
            <p>
                <i>O Retorno do Rei</i> é o terceiro volume que culmina a épica jornada pela Terra-média. O livro encerra a trilogia com batalhas grandiosas e a luta final contra Sauron.
            </p>
            <p>Acessar o trailer da adaptação:</p>
            <a href="https://youtu.be/LiKeQrChkTY?si=EPtNvy77sANyZYPG" target="_blank">O Senhor dos Anéis: O Retorno do Rei</a>
            <details>
                <summary><strong>Comentário</strong></summary>
                <p><i>O Retorno do Rei conclui a trilogia de forma épica, destacando o valor da amizade e do sacrifício.</i></p>
            </details>
            <hr>
        </section>

        <!-- Outras Sagas -->
        <h2><i>Em breve</i></h2>
        <section class="book-section">
            <h2>Saga Percy Jackson e os Olimpianos (Rick Riordan)</h2>
            <!-- Conteúdo da saga aqui -->
        </section>
    </div>
</body>
</html>

