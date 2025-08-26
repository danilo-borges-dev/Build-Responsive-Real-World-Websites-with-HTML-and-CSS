# Aula 27 – Box Model e Float

## 🎯 Objetivos

- **Compreender o Box Model:** como o tamanho de um elemento é calculado a partir de **conteúdo, padding, border e margin**.
- **Delimitar o tamanho total da caixa:** utilizando `box-sizing` para que `width` e `height` incluam padding e border.
- **Conhecer o uso de `float`:** técnica antiga para alinhar elementos horizontalmente.
- **Entender limitações do `float`:** necessidade do `clear` para evitar sobreposição e manter a estrutura correta dos elementos.
- **Aplicar boas práticas:** uso do seletor universal `*` para aplicar `box-sizing: border-box;`.

---

## 📚 Conteúdo Abordado

1. O modelo de caixas (Box Model): `content`, `padding`, `border`, `margin`.
2. Diferença entre `content-box` (padrão) e `border-box`.
3. O uso de `float` para alinhar elementos na horizontal.
4. O problema do colapso de elementos com `float`.
5. A técnica `clearfix` (`::after { clear: both; }`) para corrigir o fluxo.
6. Alternativas modernas ao `float` → `flexbox` e `grid`.

---

## 📝 Exemplo de Código

```css
/* Reset de box-sizing para evitar cálculos inesperados */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* Técnica clearfix */
.clearfix::after {
  content: "";
  display: block;
  clear: both;
}

/* Layout com float */
article {
  width: 725px;
  float: left;
}

aside {
  width: 400px;
  float: right;
  padding: 50px;
}

/* Garante que o footer fique abaixo dos elementos flutuantes */
footer {
  clear: both;
}
```
