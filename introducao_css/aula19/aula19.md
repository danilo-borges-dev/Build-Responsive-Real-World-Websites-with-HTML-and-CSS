# Aula 19 – Entendendo Herança em Seletores CSS

## 🎯 Objetivo

- Compreender que **elementos filhos podem herdar propriedades** de seus elementos pai.
- Entender que o **seletor universal (`*`)** aplica estilo a todos os elementos da página, mas suas propriedades **não são herdadas automaticamente** pelos elementos filhos.
- Reconhecer que propriedades herdáveis (como `color` e `font-family`) passam do pai para o filho.
- Exemplo: se o elemento `body` possui cor azul, o elemento filho `<p>` herdará automaticamente essa cor, sem necessidade de nova declaração.

## 📚 Conteúdo Abordado

1. Conceito de **herança em CSS**.
2. Propriedades herdáveis (ex.: `color`, `font-family`, `line-height`).
3. Diferença entre **aplicação direta** e **herança implícita**.

## 💻 Exemplo de Código

```css
body {
  color: blue;
  font-family: sans-serif;
}

p {
  /* color: blue - Herdada do elemento pai body */
  font-size: 18px; /* Aplicação direta */
}
```
