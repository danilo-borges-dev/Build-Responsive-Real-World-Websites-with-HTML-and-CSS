# Aula 23 – Centralizando o Documento HTML com uma Dica Incrível

## Objetivo

Nesta aula, você aprenderá uma técnica simples e poderosa para centralizar o conteúdo de uma página HTML, garantindo:

- **Melhor experiência visual**: elementos centralizados tornam o design mais equilibrado e agradável ao usuário.
- **Organização do layout**: ao utilizar margens automáticas, o documento mantém simetria nos lados esquerdo e direito.
- **Boas práticas com CSS**: uso de propriedades abreviadas (`shorthand`) que deixam o código mais limpo, fácil de manter e compreender.

Além disso, revisaremos o papel de elementos **não semânticos**, como a `<div>`, que apesar de não trazer significado ao conteúdo, são extremamente úteis para organizar e manipular o layout da página via CSS.

## Conteúdo Abordado

1. A importância da centralização em layouts responsivos.
2. Utilização da `<div>` como contêiner de estrutura.
3. Uso da propriedade `margin: auto;` para centralização.
4. Boas práticas ao utilizar declarações abreviadas de CSS.

## Exemplo de Código

```css
.container {
  width: 800px;
  /* Forma longa de escrever:
  margin-left: auto;
  margin-right: auto; */

  /* Forma abreviada (shorthand) */
  margin: 0 auto;
}
```
