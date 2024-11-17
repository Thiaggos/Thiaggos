<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Fotografia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="logo">
            <h1>Mr Fotografia</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Seção Home -->
    <section id="home" class="banner">
        <h2>Capturando Momentos Incríveis</h2>
        <p>Transformando suas memórias em arte.</p>
        <a href="#contato" class="btn">Peça um orçamento</a>
    </section>

    <!-- Seção Sobre -->
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Sou o Mr Fotografia, especializado em ensaios externos e eventos. Minha missão é eternizar momentos com criatividade e paixão pela fotografia.</p>
    </section>

    <!-- Seção Portfólio -->
    <section id="portfolio">
        <h2>Portfólio</h2>
        <div class="galeria">
            <img src="foto1.jpg" alt="Foto de casal">
            <img src="foto2.jpg" alt="Aniversário">
            <img src="foto3.jpg" alt="15 anos">
            <img src="foto4.jpg" alt="Ensaio sensual">
        </div>
    </section>

    <!-- Seção Serviços -->
    <section id="servicos">
        <h2>Serviços</h2>
        <ul>
            <li>Ensaio Externo</li>
            <li>Fotografia de Casamento</li>
            <li>Aniversário</li>
            <li>15 anos</li>
            <li>Batizados e Formaturas</li>
        </ul>
    </section>

    <!-- Seção Contato -->
    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato para agendar seu ensaio ou tirar dúvidas:</p>
        <form>
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="E-mail" required>
            <textarea placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>© 2024 Mr Fotografia - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
