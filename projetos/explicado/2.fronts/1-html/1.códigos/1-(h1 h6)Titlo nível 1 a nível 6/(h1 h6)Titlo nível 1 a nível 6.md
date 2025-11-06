## 🔤 O que são `<h1>` até `<h6>` em HTML?

Essas são **tags de cabeçalho (heading tags)** usadas em HTML para **definir títulos e subtítulos** em uma página web.  

Elas indicam a **importância** e a **hierarquia** dos títulos.
	
### 📌 Ordem de importância:

- `<h1>` → **Título mais importante** (como o título principal da página).
    
- `<h2>` → Subtítulo do `<h1>`.
    
- `<h3>` → Subtítulo do `<h2>`.
    
- ...
    
- `<h6>` → **Título menos importante**.
    

---

## 📐 Hierarquia de títulos (como se fosse um índice)

Imagine que você está escrevendo um livro:

```
Capítulo 1: Introdução      → <h1>
  Seção 1.1: O que é HTML   → <h2>
    Tópico 1.1.1: Tags      → <h3>
```

---

## 💡 Por que isso é importante?

- Ajuda os **leitores** a entenderem a estrutura da página.
    
- Ajuda **motores de busca** (como o Google) a entenderem o conteúdo.
    
- Ajuda na **acessibilidade**, como para leitores de tela.
    

---

##  📏 Como os navegadores exibem?

Por padrão:

- `<h1>` aparece com **fonte maior e em negrito**.

<!DOCTYPE html>
<html>
  <body>
    <h1>Nível 1</h1>
    <h2>Nível 2</h2>
    <h3>Nível 3</h3>
    <h4>Nível 4</h4>
    <h5>Nível 5</h5>
    <h6>Nível 6</h6>
    
  </body>
</html>

- Conforme vai de `<h2>` até `<h6>`, o texto fica **menor**.
---

## 🛑 Dicas importantes:

- Use **apenas um `<h1>` por página**, de preferência.
    
- Use os outros níveis para **organizar o conteúdo** como um índice.
    
- Não use `<h1>` apenas porque "é grande". Use pelo significado.