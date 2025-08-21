# Aula 18 – Conhecendo a Priorização Hierárquica dos Seletores CSS

## 🎯 Objetivo

- Entender que o CSS possui **hierarquia de prioridade** na aplicação de estilos sobre os elementos HTML.
- Compreender a ordem de precedência:
  - **Estilos in-line** possuem a prioridade máxima, mas **não são recomendados** (boa prática é manter em um arquivo CSS externo).
  - **IDs (`#id`)** estão logo abaixo dos estilos in-line e têm maior peso que classes e seletores comuns.
  - **Classes (`.classe`)** e **pseudo-classes (`:hover`, `:first-child`, etc.)** possuem o mesmo nível de prioridade. Em caso de conflito, o **último estilo declarado** será aplicado.
  - **Seletores de elementos comuns** (`p`, `h1`, `body`, etc.) têm prioridade menor. Em duplicidade, prevalece o último declarado.
  - O **seletor universal (`*`)** tem a menor prioridade de todas.
- Reconhecer o uso do modificador **`!important`**, que força a aplicação de um estilo, mas deve ser evitado e usado apenas como último recurso.

## 📚 Conteúdo Abordado

1. Hierarquia de prioridade no CSS (inline, ID, classe, seletor comum e universal).
2. Regras de desempate em estilos duplicados.
3. Uso (e riscos) do modificador **`!important`**.

## 💻 Exemplo de Código

```css
p {
  color: blue;
}

.texto {
  color: green;
}

#principal {
  color: red;
}

p {
  color: purple !important;
}
```
