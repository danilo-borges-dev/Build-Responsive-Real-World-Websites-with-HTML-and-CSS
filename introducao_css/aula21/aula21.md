# Aula 21 – Conhecendo a Área de Preenchimento (Padding) e as Margins de um Elemento HTML

## 🎯 Objetivo

- Entender a importância da **Box Model** em elementos HTML, fundamental para compreender como os elementos se organizam e se relacionam entre si.
- Conhecer as partes que compõem a **Box Model**:
  - **Conteúdo interno** → o conteúdo real do elemento (texto, imagem, etc.).
  - **Padding** → espaço interno entre o conteúdo e a borda do elemento.
  - **Borda** → a linha que delimita o espaço do elemento, delimita a área de preenchimento.
  - **Margin** → espaço externo à borda, que define a distância do elemento em relação a outros.
- Aprender a manipular essas propriedades para alcançar o estilo visual desejado na página.

## 📚 Conteúdo Abordado

1. Estrutura da **Box Model** (conteúdo, padding, borda e margin).
2. Diferença entre **padding** e **margin**.
3. Manipulação prática da Box Model no CSS.

## 💻 Exemplo de Código

```css
.box {
  width: 200px;
  height: 100px;
  background-color: lightblue;

  /* Espaçamento interno */
  padding: 20px;

  /* Borda do elemento */
  border: 3px solid blue;

  /* Espaçamento externo */
  margin: 30px;
}
```
