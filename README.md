# ecommerce-syntaxwear

## Visão geral

Este repositório contém um site estático de demonstração para a marca fictícia de sneakers "SintaxWear". O projeto é composto por uma única página HTML (`index.html`) e um conjunto de arquivos CSS organizados por responsabilidade, com foco em design responsivo, navegação mobile-friendly e apresentação visual de produtos.

## O que está incluído

- Página inicial com cabeçalho fixo, hero section, categorias de produtos e grid de destaque.
- Estilos CSS segmentados em reset, variáveis e componentes.
- Imagens de produto e ícones para layout visual.
- Design responsivo usando media queries para telas menores.
- Uso de fontes via Google Fonts através de `css/variables.css`.

## Recursos principais

- Cabeçalho fixo com navegação principal e ícones de acesso rápido.
- Seção hero com imagem em destaque, título, subtítulo e botões de chamada para ação.
- Cards de categoria para diferentes estilos: Casual, Esporte, Moderno e Futurista.
- Grid de produtos com imagens e foco no modelo "Krypton One".
- Rodapé com formulário de newsletter, links de redes sociais e navegação adicional.

## Estrutura de arquivos

- `index.html` - página principal do site.
- `css/reset.css` - reset de estilos base para maior consistência entre navegadores.
- `css/variables.css` - declaração de variáveis CSS e import das fontes.
- `css/base.css` - estilos globais, tipografia básica e estilos de botões.
- `css/components/header.css` - estilos do cabeçalho, menu e navegação responsiva.
- `css/components/hero.css` - estilos para a seção hero e botões CTA.
- `css/components/product-category.css` - estilos dos cards de categoria com imagens de fundo.
- `css/components/product-grid.css` - estilos do layout em grid para os produtos.
- `css/components/footer.css` - estilos do rodapé, newsletter e links.
- `images/` - pasta com imagens de banners, produtos, ícones e logo.

## Imagens do projeto

- `images/banners/hero.jpg` e `images/banners/hero-mobile.jpg`
- `images/logo/Logo.png`
- `images/icons/` - ícones de WhatsApp, Facebook, Instagram, TikTok, carrinho, usuário, ajuda e menu.
- `images/products/` - imagens de produtos, incluindo `casual.jpg`, `esporte.jpg`, `moderno.jpg`, `futurista.jpg`, além de imagens de grid como `modelo-masculino.jpg`, `modelo-feminino.jpg`, `moderno-grid.jpg`, `futurista-grid.jpg`, `preto-azul-grid.jpg` e `roxo-verde-grid.jpg`.

## Observações importantes

- O site é totalmente estático e não contém JavaScript.
- Links e botões em `index.html` usam `#` como destino e não executam ações reais.
- A página referencia `css/layout.css`, mas este arquivo não existe no repositório atualmente. Para evitar erros ou melhorar o projeto, remova essa referência ou crie `css/layout.css` com regras de layout adicionais.

## Como abrir o projeto

1. Clone ou baixe o repositório.
2. Abra `index.html` diretamente em um navegador.

Para desenvolvimento local, use um servidor estático:

```bash
cd ecommerce-syntaxwear
python -m http.server 8000
```

Acesse `https://github.com/gabrielegeremia/ecommerce-syntaxwear.git` no navegador.

## Sugestões de melhoria

- Adicionar um arquivo `css/layout.css` para regras de layout globais e organizar melhor a estrutura.
- Implementar JavaScript para navegação mobile, formulário de newsletter e interações de carrinho.
- Substituir links `#` por páginas reais ou seções da mesma página.
- Melhorar a acessibilidade com atributos ARIA adicionais e foco visível.
- Otimizar imagens para web e adicionar lazy-loading, se necessário.

## Uso recomendado

- Protótipo de landing page para e-commerce.
- Base para um projeto de front-end em HTML/CSS.
- Exemplo de layout responsivo com grid e hero section.

## Créditos

Desenvolvido como demonstração de design de site estático para loja de tênis e sneakers.
