cuidado com links falsos usando a[href="#"]
colocar font-sise no root de 62.5%
sempre usar normalize
margim-top auto empurra para baixo
stech estica os itens para deixa-los na mesma altura, e grom na largura.
Colocar padding 1 no container, para ele se basear, quando alguma tag estiver empurrando.
Flex 1 no container, não na imagem, na imagem coloca 100% width, depois é só ver se o tamanho do container está igual. 

PARA ENCONTRAR ERRORS, IR delentando o código pelo google aos poucos, e procurar em qual parte do código está o bug.

---
ESCONDER INPUTS SEM FERRAR COM O MOTOR DE BUSCA

.div-hero1_label_input {

  height: 1px;

  width: 1px;

  border: 0;

  margin: 0;

  outline: 0;

  overflow: hidden;

  position: absolute;

}
  
.div-hero1_label_input:focus + .div-hero1_label_span{

    outline: 1px solid black;

}

----
