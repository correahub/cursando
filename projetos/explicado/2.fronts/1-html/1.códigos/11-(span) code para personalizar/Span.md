
---

## ✅ O que é a tag `<span>`?

A `<span>` é uma **tag inline**, ou seja, **não cria uma quebra de linha** como `<div>` ou `<p>`. Ela é usada para **marcar uma parte específica de um conteúdo**, normalmente **dentro de outras tags**, para que você possa aplicar **estilos** ou **ações** somente naquela parte.

> Pense nela como um **marcador invisível** que você pode estilizar com `class`, `id` ou JavaScript.

---

## 🧠 Para que serve o `<span>`?

- **Aplicar estilos a uma palavra ou frase dentro de um texto.**
    
- **Destacar partes específicas de um conteúdo.**
    
- **Usar com JavaScript para manipular textos de forma dinâmica.**
    

---

## 📘 Exemplo prático: estilizando uma palavra com `span`

### HTML + CSS

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .vermelho {
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <p>Eu gosto de <span class="vermelho">morango</span> e de chocolate.</p>

</body>
</html>
```

### O que acontece aqui?

- Temos um parágrafo com a frase: “Eu gosto de **morango** e de chocolate.”
    
- A palavra **morango** está dentro de um `<span class="vermelho">`.
    
- Essa classe aplica **cor vermelha** e **negrito** **somente à palavra "morango"**, sem alterar o resto do parágrafo.
    

---

## 🧪 Outro exemplo com mais de um estilo

```html
<style>
  .azul {
    color: blue;
    font-style: italic;
  }

  .sublinhado {
    text-decoration: underline;
  }
</style>

<p>
  Esta é uma <span class="azul">palavra azul</span> e esta é uma
  <span class="sublinhado">palavra sublinhada</span>.
</p>
```

Você pode até usar **várias classes ao mesmo tempo**:

```html
<span class="azul sublinhado">texto estilizado</span>
```

---

## 🚨 Importante

- A tag `<span>` **não altera nada visualmente sozinha**. Ela **precisa de um `class`, `id` ou estilo inline** para fazer alguma diferença.
    
- Use `<span>` quando quiser **modificar partes pequenas do texto** sem quebrar a estrutura.
    

---

Se quiser, posso te mostrar como usar `span` com eventos de clique ou mudar o estilo com JavaScript. Quer explorar isso também?