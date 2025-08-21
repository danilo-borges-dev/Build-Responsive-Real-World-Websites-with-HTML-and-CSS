# Aula 20 – Desafio: Aplicar Estilos CSS no Documento HTML

## 🎯 Objetivo

- Colocar em prática os conhecimentos adquiridos nas aulas anteriores, aplicando diversos estilos CSS em uma página que apresenta um **produto**.
- Organizar o código com **comentários**, separando os grupos de elementos relacionados para manter clareza e padronização.

## 📚 Conteúdo Abordado

1. Revisão dos principais conceitos de **seletores, classes e IDs**.
2. Aplicação prática de **tipografia, cores, bordas e pseudo-classes**.
3. Estruturação e **organização do código CSS com comentários**.

## 💻 Exemplo de Código

```css
body {
  font-family: sans-serif;
  line-height: 1.5;
}

/* PRODUCT */
.product {
  border: 4px solid black;
}

.product-header {
  text-transform: uppercase;
  background-color: #f7f7f7;
  text-align: center;
  font-size: 22px;
}

/* PRODUCT INFORMATION */
.product-title {
  text-transform: uppercase;
}

.sells-message {
  color: #777;
  font-weight: bold;
  text-transform: uppercase;
  font-size: 12px;
}

#product-value {
  font-size: 20px;
  font-weight: 900;
}

.more-information:link,
.more-information:visited {
  color: black;
}

.more-information:hover,
.more-information:active {
  text-decoration: none;
}

/* PRODUCT DETAILS */
ul {
  list-style-type: square;
}

/* PRODUCT BUTTON */
.button-paragrapher {
  padding: 0px;
  margin: 0px;
}

p button {
  color: white;
  text-transform: uppercase;
  padding: 10px;
  margin: 0px;
  border: none;
  background-color: black;
  cursor: pointer;
}

p button:hover {
  color: black;
  background-color: white;
}
```
