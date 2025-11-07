| Syntax                | Tipo de valor aceito                      | Exemplos válidos                                         | Descrição detalhada                                   |
| :-------------------- | :---------------------------------------- | :------------------------------------------------------- | :---------------------------------------------------- |
| `<color>`             | Cores CSS                                 | `red`, `#00ff00`, `rgb(255, 0, 0)`, `hsl(200, 50%, 50%)` | Aceita qualquer formato de cor CSS.                   |
| `<length>`            | Medidas fixas                             | `10px`, `2rem`, `5em`, `1vh`                             | Usado para tamanhos, margens, espaçamentos, etc.      |
| `<number>`            | Números sem decimais                      | `0`, `1.5`, `-10`, `3.1416`                              | Para cálculos, transformações, animações, etc.        |
| `<percentage>`        | Valores percentuais                       | `50%`, `100%`, `12.5%`                                   | Usado em larguras, alturas e gradientes.              |
| `<integer>`           | Números inteiros                          | `1`, `2`, `-5`                                           | Versão inteira de `<number>`.                         |
| `<angle>`             | Ângulos                                   | `45deg`, `0.5turn`, `1rad`, `200grad`                    | Usado em rotações, gradientes angulares.              |
| `<time>`              | Tempo                                     | `2s`, `300ms`                                            | Usado em transições e animações.                      |
| `<length-percentage>` | Combinação de `<length>` e `<percentage>` | `10px`, `50%`                                            | Aceita tanto pixels quanto porcentagens.              |
| `<image>`             | Imagens e gradientes                      | `url('img.png')`, `linear-gradient(red, blue)`           | Usado em backgrounds e máscaras.                      |
| `<url>`               | Caminho de recurso                        | `url('/img/fundo.svg')`                                  | Refere-se a um recurso externo.                       |
| `<string>`            | Texto entre aspas                         | `"Hello"`, `'CSS Rocks'`                                 | Útil para conteúdos dinâmicos.                        |
| `<transform-list>`    | Lista de transformações                   | `rotate(45deg) scale(1.2)`                               | Define várias transformações em sequência.            |
| `<custom-ident>`      | Identificador (sem aspas)                 | `primary`, `main`, `dark-mode`                           | Usado em propriedades personalizadas de tipo nomeado. |
| `<dimension>`         | Combinação `<number><unit>`               | `10px`, `5em`, `2vh`                                     | Tipo genérico de valor com unidade.                   |
| `<length-percentage>` | Mistura entre `<length>` e `<percentage>` | `10px`, `20%`                                            | Aceita medidas absolutas ou relativas.                |
| `<position>`          | Coordenadas 2D                            | `top left`, `center center`, `10px 20px`                 | Define posição de imagens, gradientes, etc.           |
