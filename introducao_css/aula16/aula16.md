# Aula 16 – Conhecendo as Pseudo-classes Mais Utilizadas no CSS

## 🎯 Objetivo

- Conhecer as **LVHA**, que são respectivamente as pseudo-classes:
  - `:link` → link não visitado.
  - `:visited` → link já visitado.
  - `:hover` → quando o usuário passa o mouse sobre o link.
  - `:active` → link no momento em que está sendo clicado.
- Entender como essas pseudo-classes melhoram a **interatividade** e a **usabilidade** dos links em uma página web.

## 📚 Conteúdo Abordado

1. Pseudo-classe **`:link`** – estilizando links não visitados.
2. Pseudo-classe **`:visited`** – aplicando estilo a links já acessados.
3. Pseudo-classe **`:hover`** e **`:active`** – interações dinâmicas em tempo real.

## 💻 Exemplo de Código

```css
a:link {
  color: #1098ad;
  text-decoration: none;
}

a:visited {
  color: #1098ad;
}

a:hover {
  color: orangered;
  font-weight: bold;
  text-decoration: underline orangered;
}

a:active {
  background-color: #444;
  font-style: italic;
}
```
