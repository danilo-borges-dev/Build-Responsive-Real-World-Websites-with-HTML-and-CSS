# Aula 07 – Aplicando semântica aos elementos HTML

## Objetivos da Aula

- Conhecer elementos semânticos como `<header>`, `<article>`, `<footer>` e `<nav>`.
- Aprender que é possível utilizar múltiplos `<header>` para organizar seções ou grupos de elementos.
- Implementar uma estrutura de página mais clara e padronizada.

## Conteúdo Abordado

1. Uso do elemento `<header>` para cabeçalhos principais e de seções.
2. Estruturação de conteúdo com `<article>` para representar blocos de informação.
3. Criação de rodapé da página utilizando `<footer>`.
4. Organização da navegação com `<nav>`.

## Exemplo de Código

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <title>Página Semântica</title>
  </head>
  <body>
    <header>
      <h1>Meu Site</h1>
      <nav>
        <a href="index.html">Início</a>
        <a href="sobre.html">Sobre</a>
        <a href="contato.html">Contato</a>
      </nav>
    </header>

    <main>
      <article>
        <header>
          <h2>Notícia 1</h2>
          <p>Publicado em 19 de agosto de 2025</p>
        </header>
        <p>Este é o conteúdo principal do artigo.</p>
        <footer>
          <p>Autor: João Silva</p>
        </footer>
      </article>
    </main>

    <footer>
      <p>&copy; 2025 Meu Site – Todos os direitos reservados.</p>
    </footer>
  </body>
</html>
```
