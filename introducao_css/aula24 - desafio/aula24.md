# Aula 24 – Desafio: Ajustando o Card do Sapato com os Novos Conhecimentos

## Objetivo

Neste desafio, colocamos em prática os conceitos aprendidos até o momento no curso. O foco foi ajustar o **design do card de um produto**, garantindo melhor apresentação visual e usabilidade.

Ao final do exercício, o card ficou mais organizado, com espaçamento adequado entre os elementos, botão ajustado corretamente e todo o conteúdo centralizado de forma agradável para o usuário.

## Conteúdo Abordado

1. **Reset de estilos padrões**: remover `margin` e `padding` default utilizando o **seletor universal** (`*`).
2. **Botão de adicionar ao carrinho**: configurar largura total do card (`width: 100%`).
3. **Espaçamento entre elementos**: adicionar `margin-bottom` para separar os blocos na vertical.
4. **Listas não ordenadas**: aplicar `margin-left` para exibir os marcadores de forma alinhada.
5. **Centralização do card**: posicionar o card no centro da página, mantendo um espaço superior de `50px`.

## Exemplo de Código

```css
/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.card {
  width: 300px;
  margin: 50px auto; /* centraliza horizontalmente e adiciona espaço no topo */
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
  text-align: center;
}

.card ul {
  margin-left: 20px; /* exibe os marcadores da lista */
  text-align: left;
}

.card button {
  width: 100%; /* botão ocupa toda a largura */
  margin-top: 15px; /* separa o botão dos demais elementos */
  padding: 10px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.card button:hover {
  background-color: #0056b3;
}
```
