# Aula 31 – Aplicando Flexbox no Projeto **Produto Card**

## Objetivo

- Substituir o alinhamento antigo feito com `float` por Flexbox.
- Definir corretamente o **container pai** e os **elementos filhos**.
- Aplicar `display: flex` para alinhar os itens de forma moderna e responsiva.
- Utilizar `gap` para criar espaçamento uniforme entre os elementos filhos.
- Configurar o **segundo e terceiro elementos** para ocuparem igualmente o espaço restante, utilizando `flex: 1`.
- Criar um **segundo container interno** dentro do primeiro filho, para alinhar outros dois elementos com Flexbox.
- Usar `justify-content: space-between` para distribuir os itens internos nas extremidades.
- Aplicar `align-items: center` para alinhar verticalmente os elementos dentro do container interno.

## Conteúdo Abordado

1. Estrutura básica do Flexbox (`display: flex`)
2. Uso de `gap` para espaçamento entre elementos
3. Propriedade `flex: 1` para distribuir espaço igualmente
4. Containers internos com alinhamentos específicos
5. Propriedades `justify-content` e `align-items` no dia a dia

## Exemplo de Código

```css
/* FLEXBOX - Container principal */
.container-product {
  display: flex;
  gap: 30px;
}

.product-information,
.product-details {
  padding-top: 10px;
  flex: 1; /* divide igualmente o espaço entre os dois */
}

.product-information p {
  word-wrap: break-word;
}

.main-product-description {
  margin-bottom: 20px;
}

.product-details {
  margin-right: 30px;
}

/* Container interno para preço + mensagem */
.price-message {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}

/* Exemplo de alinhamento interno com elementos quadrados */
.square-elements {
  display: flex;
  gap: 20px;
}
```
