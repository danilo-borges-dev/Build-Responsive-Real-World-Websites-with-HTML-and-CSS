# Aula 09 – Crie um pequeno projeto de exibição de um produto

## Objetivos da Aula

- Aprender a estruturar um pequeno projeto em HTML para exibir os detalhes de um produto.
- Utilizar elementos semânticos como `<article>`, `<header>`, `<figure>`, `<aside>` e `<footer>` para organizar a página.
- Aplicar boas práticas de acessibilidade e responsividade em páginas HTML simples.

## Conteúdo Abordado

1. Estruturação de uma página HTML com `<main>` e `<article>`.
2. Uso de `<img>` para exibir imagem e descrição do produto.
3. Inclusão de informações complementares com `<aside>`.
4. Criação de botões de ação para interação do usuário.

## Exemplo de Código

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Projeto: Exibição de Produto</title>
  </head>
  <body>
    <main>
      <article>
        <header>
          <h2>Tênis Converse Chuck Taylor All Star Low Top</h2>
        </header>

        <figure>
          <img
            src="img/challenges.jpg"
            alt="Par de tênis Converse Chuck Taylor All Star Low Top em lona"
            width="200"
            height="200"
            loading="lazy"
          />
          <figcaption>Clássico tênis de lona, modelo cano baixo</figcaption>
        </figure>

        <p><strong>R$ 65,00</strong></p>
        <p>Frete grátis</p>

        <p>
          Pronto para qualquer ocasião, os clássicos Chucks de lona são um item
          essencial do guarda-roupa.
        </p>

        <p>
          <a href="#detalhes">Mais informações →</a>
        </p>

        <aside id="detalhes" aria-labelledby="detalhes-titulo">
          <h3 id="detalhes-titulo">Detalhes do Produto</h3>
          <ul>
            <li>Lona leve e durável</li>
            <li>Palmilha levemente acolchoada para maior conforto</li>
            <li>Patch icônico Chuck Taylor no tornozelo</li>
          </ul>
        </aside>

        <p>
          <button type="button">Adicionar ao carrinho</button>
        </p>

        <footer>
          <p>&copy; 2025 Minha Loja – Todos os direitos reservados.</p>
        </footer>
      </article>
    </main>
  </body>
</html>
```
