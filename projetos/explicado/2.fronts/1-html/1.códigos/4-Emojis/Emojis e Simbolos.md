
# &#x é um elemento usada para marcar emojis  no conteúdo.





















### ✨ Como usar com emojis?

Cada emoji tem um **código Unicode**, que pode ser representado em hexadecimal. Você pode usar esse código com `&#x...;`.
### 🧠 O que é `&#x;`?

Essa é uma forma de escrever **caracteres Unicode** usando **HTML entities** no formato **hexadecimal**:

- `&#x` = início do código hexadecimal do caractere.
    
- `;` = fim da entidade.
---

### ✅ Passo a passo:

#### 1. **Encontre o código Unicode do emoji**

Por exemplo: 😊 (carinha sorridente)

- Unicode: `U+1F60A`
    

#### 2. **Transforme o `U+` em `&#x`**

- Unicode: `U+1F60A` → HTML: `&#x1F60A;`
    

#### 3. **Use no HTML**

`<p>Você está feliz? &#x1F60A;</p>`

➡️ Resultado:

> Você está feliz? 😊

---

### 🔍 Outro exemplo

Emoji: 🐱 (gato)

- Unicode: `U+1F431`
    
- HTML: `&#x1F431;`

`<p>Eu amo gatos! &#x1F431;</p>`

➡️ Resultado:

> Eu amo gatos! 🐱

---

### ⚠️ Observações:

- Sempre use **letras maiúsculas ou minúsculas**, ambas funcionam: `&#x1f60a;` ou `&#x1F60A;`.
    
- Isso funciona em **quase todos os navegadores modernos**.
    
- Certifique-se de que o HTML está com a codificação `UTF-8` (padrão na maioria dos casos).
    

---

### 🛠 Dica: Onde encontrar o código Unicode de emojis?

Você pode usar sites como:

- [emojipedia.org](https://emojipedia.org/)
    
- Ou pesquisar no Google: "unicode emoji 😊"

