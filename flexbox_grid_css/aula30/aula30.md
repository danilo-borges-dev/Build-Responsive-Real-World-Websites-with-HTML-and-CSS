# Aula 30 – Aplicando alinhamento Flexbox nos elementos

## 🎯 Objetivo

- Para aplicar **Flexbox**, é essencial definir ou criar um **container**, que será o elemento pai responsável por agrupar os demais elementos e permitir o alinhamento adequado.
- Quando necessário, crie **sub-containers** para os elementos filhos, garantindo uma melhor organização e controle do layout.
- Utilize a propriedade **`align-items: flex-start`** quando quiser que os elementos respeitem o tamanho interno de seus filhos, alinhando-os ao topo.
- Faça uso da propriedade **`flex`** (shorthand de `flex-grow`, `flex-shrink` e `flex-basis`) para controlar o tamanho e comportamento dos elementos dentro do container.

---

## 📚 Conteúdo Abordado

1. Estrutura de um container flexível.
2. Propriedades principais de alinhamento:
   - `justify-content` → Alinhamento **horizontal**.
   - `align-items` → Alinhamento **vertical**.
   - `align-content` → Alinhamento de múltiplas linhas.
3. Uso da propriedade **`flex`** para:
   - Definir se o item **cresce** (`flex-grow`).
   - Definir se o item **encolhe** (`flex-shrink`).
   - Definir o **tamanho base** (`flex-basis`).
4. Boas práticas na criação de containers e sub-containers.
5. Aplicação prática em layout com **`header`**, **`article`** e **`aside`**.

---

## 📝 Explicação da Propriedade `flex`

A propriedade **`flex`** é um atalho (_shorthand_) para **três valores**:

```css
.main-header {
  display: flex;
  align-items: center; /* Alinha verticalmente ao centro */
  justify-content: space-between; /* Espaça os elementos nas extremidades */
}

.author-box {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  margin-left: 15px;
}

.author {
  margin-bottom: 0;
  margin-left: 15px;
}

.related-post {
  display: flex;
  flex-direction: column; /* Organiza em coluna */
}

.related-item {
  display: flex;
  align-items: center;
  margin-left: 40px;
  gap: 20px; /* Espaçamento entre os itens */
}

.main-content-page {
  display: flex;
  align-items: flex-start; /* article e aside alinhados ao topo */
  gap: 100px;
  margin-bottom: 30px;
}

article {
  flex: 0 0 600px; /* largura fixa de 600px */
  margin-bottom: 0;
}

aside {
  /*
  Valores padrões do flex:
  flex-grow: 0;   -> não cresce
  flex-shrink: 1; -> pode encolher
  flex-basis: auto; -> tamanho automático
  */
  flex: 0 0 300px; /* largura fixa de 300px */
}
```
