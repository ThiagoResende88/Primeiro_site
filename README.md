## Agência de Marketing Digital XYZ

Temos aqui uma página exemplo para uma agência de Marketing Digital. 
A página possui banner, três sessões (Serviços, Portifólio e Contatos), além da header, footer e botões clicáveis.

Link: https://thiagoresende88.github.io/Primeiro_site/ 

---

# Estrutura do Código HTML e CSS 🚀

Aqui está uma explicação da estrutura do código HTML e CSS usado neste projeto:

## HTML:

- `<!DOCTYPE html>`: Declara o tipo de documento HTML sendo usado, que é o HTML5.

- `<html lang="pt-BR">`: Define o elemento raiz da página HTML e especifica o idioma como português do Brasil.

- `<head>`: Contém informações sobre o documento, como metadados, links para folhas de estilo CSS e o título da página.

  - `<meta charset="UTF-8">`: Define o conjunto de caracteres como UTF-8, que permite a exibição de caracteres especiais.

  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Define as configurações de visualização da página para dispositivos móveis.

  - `<title>Marketing Digital XYZ</title>`: Define o título da página que aparece na barra de título do navegador.

  - `<link rel="stylesheet" href="style.css">`: Importa uma folha de estilo externa chamada "style.css" para estilizar a página.

- `<body>`: Contém todo o conteúdo visível da página.

  - `<header>`: Geralmente contém o cabeçalho da página, que pode incluir o logotipo e a navegação.

    - `<nav>`: Define a navegação principal da página.

      - `<div class="container">`: Cria um contêiner para agrupar o conteúdo do cabeçalho.

        - `<h1>Marketing Digital XYZ</h1>`: O cabeçalho principal da página, que normalmente é o logotipo ou um título.

        - `<ul>`: Uma lista não ordenada que geralmente contém links de navegação.

          - `<li><a href="#services">Serviços</a></li>`: Um item da lista que contém um link para a seção "Serviços" da página.

  - `<section class="banner">`: Uma seção de banner, que pode conter informações adicionais ou imagens de destaque.

  - `<section class="hero">`: Uma seção herói, geralmente usada para destacar um título principal e uma chamada para ação.

  - `<section class="services" id="services">`: Uma seção de serviços que contém informações sobre os serviços oferecidos.

    - `<div class="container">`: Um contêiner para agrupar os serviços individuais.

      - `<h2>Nossos Serviços</h2>`: Um título para a seção de serviços.

      - `<div class="service">`: Cada serviço é representado por um elemento div com a classe "service".

        - `<img src="SEO.jpg" alt="Serviço 1">`: Uma imagem representando o serviço de otimização de SEO.

        - `<h3>Otimização de SEO</h3>`: Um título para o serviço.

        - `<p>Maximize sua visibilidade nos motores de busca e alcance um público maior.</p>`: Uma descrição do serviço.

  - `<section class="portfolio" id="portfolio">`: Uma seção de portfólio que mostra projetos anteriores.

    - `<div class="container">`: Um contêiner para agrupar os itens do portfólio.

      - `<h2>Portfólio</h2>`: Um título para a seção de portfólio.

      - `<div class="portfolio-item">`: Cada item do portfólio é representado por um elemento div com a classe "portfolio-item".

        - `<img src="cliente1.avif" alt="Projeto 1">`: Uma imagem representando o primeiro projeto.

        - `<h3>Cliente A</h3>`: O nome do cliente ou título do projeto.

        - `<p>Veja como ajudamos o Cliente A a alcançar um aumento de 50% nas vendas.</p>`: Uma descrição do projeto.

  - `<section class="contact" id="contact">`: Uma seção de contato que fornece informações de contato.

    - `<div class="container">`: Um contêiner para agrupar as informações de contato.

      - `<h2>Entre em Contato</h2>`: Um título para a seção de contato.

      - `<p>Estamos prontos para ajudar a impulsionar o seu negócio. Entre em contato conosco hoje mesmo.</p>`: Uma descrição ou mensagem de contato.

      - `<a href="mailto:contato@marketingxyz.com" class="cta-button">Email: contato@marketingxyz.com</a>`: Um link de e-mail para contato.

      - `<a href="tel:+5555555555" class="cta-button">Telefone: (55) 5555-5555</a>`: Um link de telefone para contato.

  - `<footer>`: Geralmente contém informações de rodapé.

    - `<div class="container">`: Um contêiner para agrupar o conteúdo do rodapé.

      - `<p>&copy; 2023 Marketing Digital XYZ</p>`: Informações de direitos autorais.

      - `<p>Thiago Dias Resende</p>`: Nome do autor e desenvolvedor da página.

## 📋 CSS

Aqui está a explicação da estrutura dos seletores CSS usados neste projeto:

### Reset de Estilos:

- `*`: Seleciona todos os elementos na página. Os estilos definidos aqui são usados para zerar margens, preenchimentos e definir a caixa de modelo como "border-box" para todos os elementos. Isso ajuda a garantir uma base consistente para o layout.

### Estilos Gerais:

- `body`: Seleciona o elemento `<body>` e define a família de fontes para o corpo do documento.

- `.container`: Seleciona elementos com a classe "container". Define a largura máxima, margem e preenchimento para elementos com essa classe. Isso é frequentemente usado para criar layouts responsivos e centralizar o conteúdo.

### Estilos do Header:

- `header`: Seleciona o elemento `<header>`. Define o fundo, cor do texto e preenchimento para o cabeçalho da página.

- `nav ul`: Seleciona listas não ordenadas dentro de elementos `<nav>`. Remove os marcadores de lista padrão.

- `nav ul li`: Seleciona itens de lista dentro da lista de navegação. Define-os como elementos em linha com margem direita.

- `nav a`: Seleciona links dentro do elemento de navegação. Define a cor do texto e remove a decoração de texto (sublinhado).

### Estilos da Seção Banner:

- `.banner`: Seleciona elementos com a classe "banner". Define o fundo do banner, o tamanho da imagem de fundo e o preenchimento para criar um banner destacado.

### Estilos da Seção Hero:

- `.hero`: Seleciona elementos com a classe "hero". Define a cor do texto e o preenchimento para a seção "hero" da página.

- `.hero h2`: Seleciona elementos `<h2>` dentro da seção "hero" e ajusta o tamanho da fonte.

### Estilo dos Botões:

- `.cta-button`: Seleciona elementos com a classe "cta-button", que são usados para criar botões de chamada para ação em várias seções do site.

   - `display: flex;`: Define a exibição como flexível para permitir o alinhamento e a distribuição de elementos filho dentro do botão.

   - `padding: 10px 20px;`: Define o preenchimento do botão, ou seja, o espaço interno entre o texto do botão e suas bordas.

   - `background-color: #f00;`: Define a cor de fundo do botão como vermelho (#f00).

   - `color: #fff;`: Define a cor do texto dentro do botão como branco (#fff).

   - `text-decoration: none;`: Remove a decoração de texto, como sublinhado, dos botões.

   - `margin-top: 20px;`: Define uma margem superior de 20 pixels para separar os botões de outros elementos acima deles.

   - `border-radius: 50px;`: Define um raio de borda de 50 pixels, criando cantos arredondados para os botões.

   - `font-weight: bold;`: Define o peso da fonte como negrito para o texto do botão.

   - `justify-content: center;`: Centraliza o conteúdo dos botões horizontalmente.

### Estilos da Seção Services:

- `.services`: Seleciona elementos com a classe "services". Define o fundo da seção de serviços e o preenchimento.

- `.services h2`: Seleciona elementos `<h2>` dentro da seção de serviços e centraliza o texto.

- `.service`: Seleciona elementos com a classe "service", que são usados para representar cada serviço oferecido. Define o alinhamento do texto e margem ao redor dos elementos de serviço.

- `.service img`: Seleciona imagens dentro dos elementos de serviço e ajusta a largura máxima das imagens para que se ajustem ao contêiner.

### Estilos da Seção Portfolio:

- `.portfolio`: Seleciona elementos com a classe "portfolio". Define o preenchimento para a seção de portfólio.

- `.portfolio h2`: Seleciona elementos `<h2>` dentro da seção de portfólio e centraliza o texto.

- `.portfolio-item`: Seleciona elementos com a classe "portfolio-item", que representam itens individuais no portfólio. Define margem ao redor dos itens.

- `.portfolio-item img`: Seleciona imagens dentro dos itens do portfólio e ajusta a largura máxima das imagens.

### Estilos da Seção Contact:

- `.contact`: Seleciona elementos com a classe "contact". Define o fundo, cor do texto e preenchimento para a seção de contato.

- `.contact h2`: Seleciona elementos `<h2>` dentro da seção de contato e centraliza o texto.

- `.contact p`: Seleciona parágrafos dentro da seção de contato e centraliza o texto.

### Estilos do Footer:

- `footer`: Seleciona elementos `<footer>`. Define o fundo, cor do texto e alinhamento do texto para o rodapé da página.

---

⌨️ com ❤️ por [Thiago Dias Resende](https://github.com/ThiagoResende88) 😊