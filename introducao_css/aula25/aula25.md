# Aula 25 – Posicionamento Relativo e Absoluto no CSS

## 🎯 Objetivo

- Compreender a diferença entre **posicionamento relativo** e **absoluto** no CSS.
- Aprender a **sobrepor elementos**, posicionando-os de forma controlada, sem depender apenas do fluxo tradicional (_inline_ ou _block_).
- Utilizar **pseudo-elementos** (`::before` e `::after`) para criar e estilizar conteúdo extra diretamente via CSS, sem necessidade de alterar o HTML.

---

## 📚 Conteúdo Abordado

1. **Diferença entre position: relative e position: absolute**

   - `relative`: desloca o elemento em relação à sua posição original.
   - `absolute`: posiciona o elemento em relação ao **primeiro ancestral posicionado** (aquele que tem `position: relative|absolute|fixed|sticky`).

2. **Controle de sobreposição com z-index**

   - Usado para definir quem “fica na frente” em caso de elementos sobrepostos.

3. **Uso de pseudo-elementos (::before e ::after)**
   - Inserção de conteúdo extra sem necessidade de novos elementos HTML.
   - Combinados com `position`, permitem criar rótulos, ícones, decorações, destaques e muito mais.

---

## 🧩 Exemplo de Código

```css
h2 {
  position: relative; /* Torna o h2 o "pai de referência" para o ::after */
}

h2::after {
  content: "TOP";
  background-color: #ffe70e;
  font-size: 16px;
  font-weight: bold;
  display: inline-block;
  padding: 5px 10px;
  color: #000;

  position: absolute; /* Posiciona em relação ao h2 */
  top: -10px;
  right: -25px;

  border-radius: 5px;
  z-index: 10; /* Garante que ficará acima de outros elementos */
}
```
