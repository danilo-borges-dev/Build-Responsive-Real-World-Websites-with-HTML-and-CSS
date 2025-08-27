# Aula 28 – Desafio: Aplicando `float` no Card de Produto

## Objetivo

- Utilizar a propriedade **float** para alinhar corretamente os elementos dentro do card de produto.
- Definir larguras (`width`) proporcionais para que todos os elementos caibam no espaço total do card.
- Estruturar os elementos em três divisões principais:
  - **`.product-img`** → imagem do produto
  - **`.product-info`** → informações principais
  - **`.product-details`** → detalhes adicionais
- Ajustar o posicionamento interno do conteúdo (textos) manualmente com `padding` e `margin`.

## Conteúdo Abordado

1. Uso da propriedade `float` para alinhamento de elementos.
2. Definição de `width` para organização horizontal.
3. Ajustes de espaçamento com `padding` e `margin`.
4. Uso de `clear` para evitar sobreposição de elementos.

## Exemplo de Código

```css
/* Imagem do produto */
.product-img {
  float: left;
}

/* Informações principais */
.product-info {
  float: left;
  width: 400px;
  height: 200px;
  padding: 10px 40px; /* topo + laterais */
}

/* Valor e outras informações */
.product-value-paragrapher {
  display: inline-block;
  margin-bottom: 10px;
}

/* Mensagem de vendas */
.sells-message {
  float: right;
  margin-top: 5px;
}
```
