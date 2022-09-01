# APP para comunidade de Skate  :skateboard:  (Curso de CSS da Alura)


<h2>:label: Status do projeto:  ...:construction: Em construção :construction:...</h2>

# :page_facing_up: Sobre
O projeto tem como objetivo fazer a montagem de um página para utilizada por uma comunidade de skate, aplicando o conhecimento adiquirido no curso **"CSS: dispondo elementos com Flexbox e Grid**. </br>
Inicialmente ele é desenvolvido para mobile e posteriormente, com base na versão mobile, é desenvolvida a versão Desktop </br></br>
O projeto tem, como layout, telas desenvolvidas no Figma e podem ser acessadas neste [link](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358).
#

# :computer: Tecnologias utilizadas

* VS Code
* HTML
* CSS
* JavaScript
* Git/GitHub

# Guia de estilos

A estilização que será usada no projeto está dentro do figma [neste link](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`
