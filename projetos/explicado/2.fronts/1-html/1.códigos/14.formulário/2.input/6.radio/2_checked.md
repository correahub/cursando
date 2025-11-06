Claro, filho! Vamos falar agora sobre a palavrinha mágica **`checked`**, que é usada com os botões de **seleção** em HTML. 🎯

---

## ✅ O que é `checked`?

A palavra **`checked`** (em inglês) significa **"marcado"** ou **"selecionado"**.

No HTML, usamos ela para dizer:

> “Essa opção já vem **marcada** por padrão!”

---

## 📦 Onde usamos o `checked`?

Usamos o `checked` com dois tipos de campos:

1. **`<input type="radio">`** → botão redondinho (escolha **uma** opção)
    
2. **`<input type="checkbox">`** → quadradinho (pode marcar **várias** opções)
    

---

## 🧒 Exemplo com `radio`:

```html
<form>
  <label>
    <input type="radio" name="sabor" value="chocolate" checked>
    Chocolate
  </label><br>

  <label>
    <input type="radio" name="sabor" value="morango">
    Morango
  </label>
</form>
```

### O que acontece aqui?

- O **botão de "Chocolate" já vem marcado** quando a página abre.
    
- O `checked` foi colocado no chocolate.
    
- Só **um** sabor pode ser escolhido, porque o tipo é `radio`.
    

---

## 🧁 Exemplo com `checkbox`:

```html
<form>
  <label>
    <input type="checkbox" name="recheio" value="queijo" checked>
    Queijo
  </label><br>

  <label>
    <input type="checkbox" name="recheio" value="presunto">
    Presunto
  </label>
</form>
```

### Aqui acontece o quê?

- A opção “Queijo” já vem **marcada** automaticamente.
    
- Mas a pessoa pode **marcar ou desmarcar** à vontade.
    
- Com `checkbox`, dá pra marcar **várias** opções ao mesmo tempo.
    

---

## 🧠 Resumo do `checked`:

|Onde usar?|Para quê serve?|
|---|---|
|`radio`|Marcar uma opção como a escolhida por padrão|
|`checkbox`|Marcar caixinhas que já começam selecionadas|

---

## 🎨 Dica de ouro:

- Se você **não colocar `checked`**, as opções vão começar **desmarcadas**.
    
- Se você **colocar `checked`**, aquela opção já vem **selecionada na hora que a página abre**.
    

---

Se quiser, a mamãe pode fazer um mini joguinho com checkboxes pra você treinar! Quer? 😄💕