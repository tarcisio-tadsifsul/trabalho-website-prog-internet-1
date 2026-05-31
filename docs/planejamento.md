# Projeto de Website - Disciplina Programação para Internet 1

## Requisitos:

- Website de qualquer tema ou área
- Desenvolver com HTML e CSS
- Website com mínimo de 5 páginas
- HTML semantico
- Componentes obrigatórios:
  - Menu navegacao
  - Formulario
  - Tabela
- Layout usando CSS Grid, CSS Flexbox, Menu Sticky
- Website responsivo

## Fluxo de Trabalho

- Esboço do website para definir layout, posicao de secoes, componentes. Usar Figma
- Definir estrutura de páginas
- Definir Designe e conteúdo
- Codificar
- Testar website

## Estrutura

### Paginas:

- Home
- Produtos/Serviços (Listagem)
- Produto/Serviço (Interna)
- Sobre
- Contato

### Navegação

- Menu com links para as paginas
- Menu Sticky

## Design

- Layout (tipo de grid, colunas)
- Cores
- Tipografia

## Testes

- Testar navegação, CTAs e links
- Testar responsividade

## Opcionais

- Refatorar CSS usando Variaveis
- Usar JS para carregar templates. Exemplo:

```html
<div id="header-template"></div>
<script>
  fetch("header.html")
    .then((response) => response.text())
    .then(
      (data) => (document.getElementById("header-template").innerHTML = data),
    );
</script>
```
