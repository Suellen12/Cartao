# Cartao Virtual
>Projeto para trabalhar com HTML e CSS de forma inicial. O objetivo é criar um cartão virtual de contato. Referência : https://linktr.ee/
 cartão com as informações de contato

## Criando HTML
Todo arquivo html deve ter o nome .html, exemplo:
index.html

HTML significa: Hyper Text Markup Language
``` (CRIA UMA CAIXA PRETA)
HTML = CONTEÚDO
<destacado>TEXTO</destacado>
<comando></comando>
<comando> --> <tag>
<p></p> --> parágrafo
<br> --> quebrar linha
<h1></h1> ... <h6></h6> --> Títulos
<img src="foto.png"> --> adicionar imagem
<a href="https://sp.senac.br">Senac</a> --> Link
ALT+SHIFT+F = ORGANIZA OS CODIGOS
br = COMANDO PARA PULAR LINHAS
```

## Criando o CSS
> CSS = Cascading Style Sheet (folha de estilo em cascata). O CSS é o modo pelo qual iremos formatar (estilizar) o nosso conteúdo (HTML).

Existem 3 formas de estilizar o conteúdo:

1. inline - formatação é feita diretamente no elemento HTML.
2. na pagina - formatação é feita dentro de uma seção `<style>`
3. **arquivo externo** - criamos um arquivo exclusivo para formatação (.css)

A escolha do elemento HTML que será formatado, se dá através de seletores. Seletores são criados à partir de 3 possibilidades: Tag, classe e identificação (ID)

Por exemplo: imagine que queremos modificar o fundo do site para a cor laranja e a cor da letra para amarelo, podemos montar um seletor da seguinte forma:
```css
body {
    background-color: orange; color: yellow;
}
```
Explicação:
- body = seletor (onde será formatado)
- background-color = propriedade (o que será formatado)
- orange = valor (como será formatado)

ESTUDAR SOBRE:
- tipografia
- cores
- grid
- espaçamento
- gestalt
- contrast

** assistir o canal: Chief of designer**

CSS --> ESTILO / FORMATAÇÃO
JS --> INTERAÇÃO