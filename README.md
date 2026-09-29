# blog-html-atividade


[blog.html](https://github.com/user-attachments/files/32800611/blog.html)
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog</title>
</head>

<body>

    <header>
        <h1>Meu Blog</h1>

        <nav>
            <a href="#inicio">Início</a>
            <a href="#artigos">Artigos</a>
            <a href="#inscricao">Inscrição</a>
        </nav>
    </header>

    <main id="artigos">

        <article>
            <h2>A importância da tecnologia</h2>

            <p>
                A tecnologia está cada vez mais presente em nosso cotidiano,
                facilitando tarefas e criando novas oportunidades.
            </p>

            <img src="https://picsum.photos/400/250?random=1"
                 alt="Imagem representando tecnologia">
        </article>

        <article>
            <h2>Aprendendo desenvolvimento Web</h2>

            <p>
                Aprender HTML é um dos primeiros passos para quem deseja
                começar a desenvolver páginas para a Web.
            </p>

            <img src="https://picsum.photos/400/250?random=2"
                 alt="Imagem relacionada ao desenvolvimento Web">
        </article>

    </main>

    <aside id="inscricao">

        <h2>Inscreva-se no blog</h2>

        <form method="get">

            <fieldset>
                <legend>Dados para inscrição</legend>

                <label for="nome">Nome:</label>
                <input
                    type="text"
                    id="nome"
                    name="nome"
                    minlength="3"
                    required
                >

                <br><br>

                <label for="email">E-mail:</label>
                <input
                    type="email"
                    id="email"
                    name="email"
                    required
                >

                <br><br>

                <label for="idade">Idade:</label>
                <input
                    type="number"
                    id="idade"
                    name="idade"
                    min="18"
                    max="120"
                    required
                >

                <br><br>

                <label for="assunto">Assunto de interesse:</label>
                <select id="assunto" name="assunto" required>

                    <option value="">Selecione uma opção</option>
                    <option value="html">HTML</option>
                    <option value="css">CSS</option>
                    <option value="javascript">JavaScript</option>

                </select>

                <br><br>

                <label>
                    <input
                        type="checkbox"
                        id="termos"
                        name="termos"
                        required
                    >
                    Aceito os termos
                </label>

                <br><br>

                <button type="submit">Enviar inscrição</button>

            </fieldset>

        </form>

    </aside>

    <footer>
        <p>&copy; 2026 - Meu Blog. Todos os direitos reservados.</p>
    </footer>

</body>

</html>
