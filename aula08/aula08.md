# Aula 08 – Conhecendo o elemento `<aside>` e sua utilidade

## Objetivos da Aula

- Aprender como utilizar a tag `<aside>` e compreender sua finalidade semântica.  
- Explorar o uso do `<aside>` para conteúdos complementares, como listas, links ou informações adicionais.  
- Criar uma lista não ordenada dentro do `<aside>` com imagens e links simbólicos.  

## Conteúdo Abordado

1. Uso do elemento `<aside>` para destacar informações laterais ou complementares.  
2. Estruturação de uma lista não ordenada `<ul>` dentro do `<aside>`.  
3. Inserção de elementos filhos como `<li>`, `<img>` e `<a>`.  

## Exemplo de Código

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Exemplo com Aside</title>
</head>
<body>
  <main>
    <article>
      <h1>Notícia Principal</h1>
      <p>Este é o conteúdo principal da página, com informações relevantes.</p>
    </article>

    <aside>
      <h2>Links Relacionados</h2>
      <ul>
        <li>
          <img src="icon1.png" alt="Ícone 1" width="20" height="20">
          <a href="#">Artigo Complementar 1</a>
        </li>
        <li>
          <img src="icon2.png" alt="Ícone 2" width="20" height="20">
          <a href="#">Artigo Complementar 2</a>
        </li>
        <li>
          <img src="icon3.png" alt="Ícone 3" width="20" height="20">
          <a href="#">Artigo Complementar 3</a>
        </li>
      </ul>
    </aside>
  </main>
</body>
</html>
