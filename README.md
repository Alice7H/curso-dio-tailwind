# Curso de introdução ao Tailwind CSS

Aula ministrada pelo João Paulo Miranda Matias, 1º Tenente Comandante da Divisão de Desenvolvimento de Software da Polícia Militar do Amapá.

## Objetivo

Apresentar o framework CSS Tailwind e seus principais fundamentos.

## Configurações iniciais

- Adição do tailwind por CDN, usado para fins de desenvolvimento não sendo a melhor escolha para produção.

- Inicialização de um pacote npm novo com o comando `npm init -y`.

- Instalação via terminal com o comando `npm install -D tailwindcss`

- Adição do arquivo de configuração do tailwind com o comando `npx tailwind init`

- Adição do caminho dos arquivos de modelo no arquivo de configuração do tailwind `content: ["./src/**/*.{html,js}"],`

- Criação as diretivas `@tailwind` ao css no arquivo input.css

- Execução da ferramenta CLI para verificar arquivos de modelo em buscas de classes e criação de CSS com o comando `npx tailwindcss -i ./src/css/input.css -o ./dist/output.css --watch`

- Adição do arquivo CSS à tag `<head>`.

- Uso das classes utilitárias do Tailwind para estilizar o conteúdo da página.

## Fundamentos

- Tailwind utility first - fornece classes de utilitário de baixo nível que permitem criar designs completamente personalizados sem sair do HTML.

- Mobile first - é uma abordagem que projeta um site para desktop começando com a versão móvel, que é então adaptada para telas maiores.

- Componentização - é baseada em isolar um conjunto de estilos, lógicas e partes visuais em pequenos blocos, visando a sua reutilização.

## Layout

- Container: é um componente para fixar a largura de um elemento ao ponto de interrupção atual.

  Ex: sm(640px), md(678px), lg(1024px), xl(1280px)

- Columns: utilitários para controlar o número de colunas em um elemento.

  Ex: column-1, columns-2, columns-auto, columns-sm , columns-xl...

- Box:

  - Box decoration break: utilitários para controlar como os fragmentos de elemento devem ser renderizados em várias linhas, colunas ou páginas.

    Ex: box-decoration-clone, box-decoration-slice.

  - Box sizing: utilitários para controlar como o navegador deve calcular o tamanho total de um elemento.

    Ex: box-border, box-content.

- Object:

  - Object fit: utilitários para controlar como o conteúdo de um elemento substituído deve ser redimensionado.

    Ex: object-contain, object-cover, object-fill

  - Object position: utilitários para controlar como o conteúdo de um elemento substituído deve ser posicionado em seu contêiner.

    Ex: object-bottom, object-left-bottom, object-top.

- Top, right, left, bottom: utilitários para controlar a colocação de elementos posicionados.

  Ex: inset-0, inset-x-0, top-0, right-0.

## Background

- background attachment: utilitários para controlar como uma imagem de fundo se comporta durante a rolagem.
  Ex: bg-fixed, bg-local, bg-scroll.

- background color e opacity: utilitários para controlar a cor de fundo de um elemento.

  Ex: bg-pink-900/60

- gradient color stops: utilitários para controlar as paradas de cor em gradientes de fundo.

  Ex: bg-gradient-to-l from-pink-700 via-violet-500 to-indigo-900

## Espaçamentos e Tamanhos

- Padding e margin: utilitários para controlar preenchimento e a margem de um elemento.

  Ex. de padding: p-0, px-0, py-0, pt-0, pb-0, pr-0, pl-0.

  Ex. de margin: m-0, mx-0, my-0, mt-0, mb-0, mr-0, ml-0.

- Space between: utilitários para controlar o espaço entre os elementos filho.

  Ex: space-x-0, space-y-0, space-x-4, space-y-4.

- Width e Height: utilitários para definir a largura e altura de um elemento.

  Ex. de width: w-0, w-px, w-1, w-2, w-1/2, w-full, w-screen, w-min, w-max, w-fit.

  Ex. de height: h-0, h-px, h-1, h-2, h-1/2, h-full, h-screen, h-min, h-max, h-fit.

## Tipografia

- Font family e font style: utilitários para controlar a família de fontes e o estilo de um texto.

  Ex de font-family: font-sans, font-serif, font-mono.

  Ex de font-style: italic, not-italic.

- Font size e font weight: utilitários para controlar o tamanho e o peso da fonte do texto.

  Ex. de font-size: text-xs, text-sm, text-base, text-lg, text-xl, text-2xl, text3xl.

  Ex de font-weight: font-thin, font-light, font-medium, font-bold, font-extrabold.

- Text alignment: utilitários para controlar o alinhamento do texto.

  Ex: text-left, text-center, text-right, text-justify

- Text color: utilitários para definir a cor do texto.

  Ex: text-gray-700, text-violet-900, text-red-300, text-lime-500

## Projeto

- Instalação
- Overview
- Divisão da tela em menu e conteúdo
- Menu de navegação 1
- Menu de navegação 2
- Conteúdo 1
- Conteúdo 2

## Mais informações:

[documentação do tailwind css](https://tailwindcss.com/docs/installation)

[github - joaopaulomirandamatias](https://github.com/joaopaulomirandamatias/dio-introducao-ao-tailwind/)

## Material de apoio

[Introdução ao Tailwind](https://docs.google.com/presentation/d/1KuAqxW8u3Xo450wjK_g-jcMxpfjMqg25/edit#slide=id.p62)
