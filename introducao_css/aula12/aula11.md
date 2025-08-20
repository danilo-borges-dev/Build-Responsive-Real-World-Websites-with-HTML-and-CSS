# Aula 12 – Combinando Seletores CSS para Aplicar Estilos Únicos a Determinados Elementos Mais Internos

## 🎯 Objetivo

- Aprender a **combinar seletores CSS** para aplicar estilos em elementos específicos sem comprometer o design de toda a página.  
- Declarar seletores alinhados (em cascata) para acessar a **tag mais interna** de um determinado elemento HTML e aplicar estilos personalizados.  
- Entender como **agrupar seletores** quando houver um mesmo estilo para vários elementos, evitando repetição de código.  

## 📚 Conteúdo Abordado

1. Seletores descendentes para atingir elementos internos.  
2. Agrupamento de seletores para aplicação de estilos comuns.  
3. Melhores práticas para organização e clareza no código CSS.  

## 💻 Exemplo de Código

```css
article header p {
  font-style: italic;
}

h1,
h2,
h3,
h4,
p,
li {
  font-family: sans-serif;
}
