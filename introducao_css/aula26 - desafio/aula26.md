# Aula 26 – Adicionando o “Sale” no produto

## Objetivos de aprendizagem

- Adicionar um **elemento “Sale”** (badge/fitinha) ao cartão de produto.
- Entender a diferença entre **elementos de linha vs. bloco** e quando usar `display: inline-block`, `block` ou **Flexbox**.
- **Posicionar elementos de bloco lado a lado** com Flexbox.
- Aplicar **múltiplas classes** em um mesmo elemento HTML para reaproveitar estilos.

## Conteúdo abordado

1. Elementos inline, bloco e `inline-block`
2. Layout com Flexbox para itens lado a lado
3. Badges e ribbons com `position: relative/absolute`
4. Reutilização de estilos com classes utilitárias (múltiplas classes)
5. Acessibilidade e contraste do badge “Sale”

---

## Conceitos-chave (rápido)

- **Inline** não aceita `width/height` (na prática, ignorados).
- **Block** ocupa toda a largura e respeita `width/height`.
- **inline-block** respeita `width/height` e fica “em linha” com outros.
- **Flexbox** é a forma mais simples de alinhar e distribuir itens em linha.
- Para um badge no canto, use `position: relative` no container e `position: absolute` no badge.

---

## Exemplo 1 — Múltiplas classes e elementos quadrados

### HTML

```html
<div class="square-elements">
  <div class="square square-black"></div>
  <div class="square square-blue"></div>
  <div class="square square-red"></div>
  <div class="square square-yellow"></div>
  <div class="square square-green"></div>
  <div class="square square-brown"></div>
</div>
```
