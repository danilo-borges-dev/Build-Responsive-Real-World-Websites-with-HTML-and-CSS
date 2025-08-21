# Aula 22 – Removendo Todo Estilo Default do Documento CSS

## 🎯 Objetivo

- Entender a importância de **remover os estilos padrão (default)** aplicados pelos navegadores aos elementos HTML.
- Reconhecer que ao zerar margens e paddings iniciais, temos maior **controle e consistência** na aplicação de estilos personalizados.
- Aprender a utilizar o **seletor universal (`*`)** no início do arquivo CSS para padronizar a base do layout.

## 📚 Conteúdo Abordado

1. O que são os **estilos default do navegador**.
2. Como zerar margens e paddings iniciais com o seletor universal.
3. Boas práticas para iniciar a estilização de um projeto CSS.

## 💻 Exemplo de Código

```css
* {
  margin: 0px;
  padding: 0px;
}
```
