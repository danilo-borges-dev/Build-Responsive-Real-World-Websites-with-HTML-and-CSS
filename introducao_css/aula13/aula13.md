# Aula 13 – Entendendo a Importância de Classes e ID na Declaração de Estilos CSS

## 🎯 Objetivo

- Compreender que o atributo **id** permite a declaração de seletores **únicos** no CSS, porém seu uso deve ser limitado.  
- Reconhecer que as **classes** são mais indicadas, pois facilitam a manutenção e a escalabilidade em projetos maiores.  
- Entender que o uso de classes promove maior **organização** e **padronização** no arquivo CSS.  
- Reforçar a boa prática de manter um **arquivo CSS externo** vinculado ao HTML por meio da tag `<link>`.  

## 📚 Conteúdo Abordado

1. Diferença entre **id** e **class**.  
2. Boas práticas no uso de classes para manutenção de projetos.  
3. Organização do código CSS em arquivos externos.  

## 💻 Exemplo de Código

```css
#copyright {
  font-size: 16px;
}

.related-author {
  font-size: 18px;
  font-weight: bold;
}
