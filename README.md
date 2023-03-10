# Repositório do Desafio de Projeto sobre Git/GitHub da DIO

Desafio do Projeto sobre Git/GitHub

## Links úteis

### Para edição do Readme
  
[Sintaxe Básica MarkDown markdownguide ] - https://www.markdownguide.org/basic-syntax/

[Sintaxe Básica MarkDown pipz] - https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open

[Editor MarkDown online] - https://stackedit.io/
 
### Sobre Git e seus comandos
  
[Guia de comandos básicos] https://comandosgit.github.io/
  
[Guia de referência] https://git-scm.com/docs
   
## Sintaxe Básica

### Títulos

``` 
# Título <h1>
## Título <h2>
### Título <h3>
#### Título <h4>
##### Título <h5>
###### Título <h6>
```

### Ênfase: Negrito / Itálico

Para adicionar ênfase ao conteúdo que será escrito, usa-se o asterisco  `*`  ou traço-baixo (_underline_)  `_`:

-   **Negrito**: adicione dois asteriscos ****texto**** ou dois traços-baixos __**texto**__ no início e no fim do conteúdo.
-   **Itálico**: adicione apenas um asterisco *_texto_* ou um traço-baixo __texto__ no início e no fim do conteúdo.

> Este é um exemplo de um texto que possui uma ênfase em ****negrito****, e outro em __itálico__.

### Links

    Este é um [link em formato de texto](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#), e este é um link direto [https://pipz.com/](https://pipz.com/).

### Listas 
Para listas não ordenadas, utilize um asterisco  `*`  na frente to item da lista:

```
* Item 1
* Item 2
* Item 3
```

Para listas ordenadas, utilize o número do item seguido de ponto  `.`  :

```
1. Item 1
2. Item 2
3. Item 3
```

### Imagens

O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação  `!`  no início do código.

```
![Alt ou título da imagem](URL da imagem)
```

### Tabelas  

Escolha os títulos das colunas e use `|` para delimitar as colunas. Depois, utilize hífen `-` na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o `|` para delimitar colunas. Veja um exemplo abaixo:

```

| Cabeçalho | Cabeçalho |

| ----------- | ----------- |

| Linha 1 - 1 | Linha 1 - 2 |

| Linha 2 - 1 | Linha 2 - 2 |

```

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize  `:`  ao lado do campo horizontal de hífens  `---`, na segunda linha da sua tabela. Veja abaixo:

-   **Alinhado a esquerda**: usar  `:`  no lado esquerdo (alinhamento padrão);
-   **Alinhado a direita**: usar  `:`  no lado direito;
-   **Centralizado**: usar  `:`  dos dois lados.

```
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
```

### Código

Há dois modos de adicionar trechos de código ao Markdown:

-   **Código em linha**  (_inline_): adicione um acento grave  `ˋ`  no início e no final do código.
-   **Múltiplas linhas de código**: envolva as linhas de código com três acentos graves  `ˋˋˋ`  ou três tils  `~~~`.

```
 Esta é uma linha que contém um ˋcódigoˋ.

ˋˋˋ
Esta é uma linha de código
 ˋˋˋ
```

Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o `ˋˋˋ` ou `~~~`, por exemplo `~~~javascript` ou `~~~ruby`. Veja nos exemplos abaixo:

### Notas de rodapé
Para criar uma referência de nota de rodapé, adicione um cursor e um identificador entre colchetes ( `[^1]`). Os identificadores podem ser números ou palavras, mas não podem conter espaços ou tabulações. Os identificadores apenas correlacionam a referência da nota de rodapé com a própria nota de rodapé — na saída, as notas de rodapé são numeradas sequencialmente.

```
Here's a simple footnote,[^1] 

[^1]: This is the first footnote.

```

###  Tachado

Você pode riscar palavras colocando uma linha horizontal no centro delas. Para tachar palavras, use dois símbolos de til ( `~~`) antes e depois das palavras ~~assim~~.

```
~~O mundo é Plano~~.Agora sabemos que o mundo é redondo.
```
