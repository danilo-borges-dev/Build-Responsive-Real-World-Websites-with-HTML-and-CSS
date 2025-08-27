# Aula 29 – Primeiros Passos com Flexbox

## Objetivo

- Compreender que o **Flexbox** trabalha com dois eixos principais: **main-axis** e **cross-axis**.
- **Main-axis** → eixo principal. Por padrão, é **horizontal (da esquerda para a direita)** e organiza os elementos lado a lado.
- **Cross-axis** → eixo transversal. Por padrão, é **vertical (de cima para baixo)** e organiza os elementos na altura.
- Entender que é possível **alterar a direção dos eixos** com a propriedade `flex-direction`:
  - `row` (padrão) → organiza os itens em linha (horizontal, da esquerda para a direita).
  - `row-reverse` → organiza em linha, mas da direita para a esquerda.
  - `column` → organiza em coluna (vertical, de cima para baixo).
  - `column-reverse` → organiza em coluna, mas de baixo para cima.
- Aprender que também é possível **alinhar e distribuir elementos** usando propriedades como:
  - `justify-content` → alinha no **main-axis**.
  - `align-items` → alinha no **cross-axis**.
  - `align-content` → controla o alinhamento em múltiplas linhas.

## Conteúdo Abordado

1. Diferença entre **main-axis** e **cross-axis**.
2. Alterando a direção dos eixos com `flex-direction`.
3. Distribuição e alinhamento de itens (`justify-content`, `align-items`, `align-content`).

## Exemplo de Código

```css
/* Container principal */
.container {
  display: flex; /* ativa o Flexbox */
  flex-direction: row; /* eixo principal na horizontal */
  justify-content: center; /* centraliza os itens no eixo principal */
  align-items: center; /* centraliza os itens no eixo transversal */
  height: 300px;
  border: 2px solid #333;
}

/* Itens */
.item {
  width: 80px;
  height: 80px;
  background: #4caf50;
  margin: 10px;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
```
