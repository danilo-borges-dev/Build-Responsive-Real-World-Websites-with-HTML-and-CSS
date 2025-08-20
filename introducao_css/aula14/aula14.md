# Aula 14 – Duas Formas de Declaração de Cores Utilizando CSS

## 🎯 Objetivo

- Entender que existem duas formas principais de declarar cores em CSS: **RGB** e **Hexadecimal**.
- Reconhecer que a forma **RGB** é mais utilizada quando há necessidade de aplicar **transparência** ao elemento (usando `rgba`).
- Saber que a declaração **Hexadecimal** é a mais comum e deve ser priorizada em projetos para manter consistência.
- Aprender a declarar **bordas** em CSS de duas maneiras:
  - Através de uma única linha, especificando **espessura**, **tipo** (ex.: `solid`) e **cor**.
  - Através de declarações separadas, utilizando propriedades como `border-width`, `border-style` e `border-color`.

## 📚 Conteúdo Abordado

1. Declaração de cores em formato **Hexadecimal**.
2. Declaração de cores em formato **RGB / RGBA**.
3. Propriedades de **bordas** em CSS (declaração simplificada e detalhada).

## 💻 Exemplo de Código

```css
.main-header {
  background-color: #f7f7f7;
}

aside {
  background-color: #f7f7f7;
  border: 5px solid #1098ad;
}
```
