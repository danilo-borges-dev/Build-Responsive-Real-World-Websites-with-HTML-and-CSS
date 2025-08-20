# Aula 15 – Conhecendo as Pseudo-classes e sua Importância

## 🎯 Objetivo

- Compreender que as **pseudo-classes** trazem maior interatividade e controle sobre os elementos HTML, permitindo selecionar elementos em situações específicas.  
- Entender que é possível aplicar estilos a elementos conforme sua posição em uma coleção. Exemplo: aplicar um estilo somente ao **primeiro elemento filho** de uma lista (`:first-child`).  
- Reconhecer que os comandos de pseudo-classes são **predefinidos** e, por isso, é importante estudar sua documentação e comportamento para usá-los corretamente.  

## 📚 Conteúdo Abordado

1. Introdução às **pseudo-classes** em CSS.  
2. Seleção de elementos com base em **posição** (ex.: `:first-child`, `:last-child`).  
3. Boas práticas no uso de pseudo-classes para **reutilização de estilos**.  

## 💻 Exemplo de Código

```css
li:first-child {
  font-weight: bold;
}

li:last-child {
  font-style: italic;
}
