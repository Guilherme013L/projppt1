# projppt1
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AluraBooks</title>
  <link rel="stylesheet" href="reset.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <header class="cabeçalho">
    <div class="container">
      <input type="checkbox" id="menu" class="container__botao">
      <label for="menu">
        <span class="cabeçalho__menu-hamburguer container__imagem"></span>
      </label>
      <ul class="lista-menu">
        <li class="lista-menu__titulo">Categorias</li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Programação</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Front-end</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Infraestrutura</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Business</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Design & UX</a>
        </li>
      </ul>
      <img src="img/Logo.svg" alt="Logo da Alurabooks" class="container__imagem">
    </div>
    <div class="container">
      <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
      <a href="#"><img src="img/Compras.svg" alt="Carrinhos de compras" class="container__imagem"></a>
      <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
    </div>
  </header>

  <section class="banner">
    <h2 class="banner__titulo">Já sabe por onde começar?</h2>
    <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
    <input type="search" class="banner__pesquisa" placeholder="Qual será sua próxima leitura?">
  </section>

  <section class="carrossel">
    <h2 class="carrossel__titulo">Novos lançamentos</h2>
    <!-- Slider main container -->
    <div class="swiper">
      <!-- Additional required wrapper -->
      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide"><img src="img/Apachekafka.svg"
            alt="Livro sobre apache kafka e spring boot da alura books"></div>
        <div class="swiper-slide"><img src="img/Liderança.svg"
            alt="Livro sobre liderança em design design da alura books"></div>
        <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alura books">
        </div>
        <div class="swiper-slide">
          <img src="img/Guia Front-end.svg" alt="Livro Guia front end" />
        </div>
        <div class="swiper-slide">
          <img src="img/Portugol.svg" alt="Livro sobre portugol" />
        </div>
        <div class="swiper-slide">
          <img src="img/Acessibilidade.svg" alt="Livro sobre acessibilidade" />
        </div>
      </div>

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>

    </div>

    <div class="card">
      <div class="card__descrição">
        <div class="descrição">
          <h3 class="descrição__titulo">Talvez você também se interesse por...</h3>
          <h2 class="descrição__titulo-livro">Angular 11 e Firebase</h2>
          <p class="descrição__texto">
            Construindo uma aplicação integrada com a plataforma do Google.
          </p>
        </div>
        <img src="img/Angular.svg" class="descrição__imagem" />
      </div>
      <div class="card__botões">
        <ul class="botões">
          <li class="botões__item">
            <img src="img/Favoritos.svg" alt="Favoritar livro" />
          </li>
          <li class="botões__item">
            <img src="img/Compras.svg" alt="Adicionar no carrinho de compras" />
          </li>
        </ul>
        <a href="#" class="botões__ancora">Saiba mais</a>
      </div>
    </div>

  </section>

  <section class=”carrossel”>
    <h2 class="carrossel__titulo">Mais vendidos</h2>
    <div class="swiper">
      <!-- Additional required wrapper -->
      <!-- If we need pagination -->
      <div class="swiper-pagination"></div>

      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide"><img src="img/ApacheKafka.svg"
            alt="Livro sobre apache kafka e spring boot da alura books"></div>
        <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design da alura books">
        </div>
        <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alurabooks">
        </div>
        <div class="swiper-slide"><img src="img/Guia Front-end.svg" alt="Livro Guia front end"></div>
        <div class="swiper-slide"><img src="img/Portugol.svg" alt="Livro sobre portugol"></div>
        <div class="swiper-slide"><img src="img/Acessibilidade.svg" alt="livro sobre acessibilidade"></div>
      </div>

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
    </div>

    <div class="card">
      <!-- 1º linha -->
      <div class="card__descrição">
        <!-- 1º coluna -->
        <div class="descrição">
          <img src="img/Estrelinhas.svg" alt="Avaliação 5 estrelas">
          <h3 class="descrição__titulo">Autora do Mês</h3>
          <h2 class="descrição__titulo-livro">Juliana Agarikov</h2>
          <p class="descrição__texto">Analista de sistemas e escritora, Juliana é especialista em Front-End.
          </p>
        </div>
        <!-- 2º coluna -->
        <img src="img/Escritora.svg" class="descrição__imagem">
      </div>

      <!-- 2º linha -->
      <div class="card__botões">
        <!-- 1º coluna -->
        <ul class="botões">
          <li class="botões__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
          <li class="botões__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
        </ul>
        <!-- 2º coluna -->
        <a href="#" class="botões__ancora">Saiba mais</a>
      </div>
    </div>



  </section>

  <section class="tópicos">
    <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
      <li class="tópicos__item"><a href="#" class="tópicos__link">Android</a></li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Marketing Digital</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Agile</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Startups</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">HTML & CSS</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Python</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">OO</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Java</a>
      </li>
    </ul>
  </section>

  <section class="contato">
    <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
    <p class="contato__texto">
      Atualizações de e-books, novos livros, promoções e outros.
    </p>
    <input type="email" placeholder="Cadastre seu e-mail" class="contato__email" />
  </section>

  <hr />

  <footer class="rodapé">
    <h2 class="rodapé__titulo">Grupo Alura</h2>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
  <script>
    const swiper = new Swiper(".swiper", {
      spaceBetween: 10,
      slidesPerView: 3,
      pagination: {
        el: ".swiper-pagination",
        type: "bullets",
      },
    });
  </script>
</body>

</html>
