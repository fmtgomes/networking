Maratona Explorer 2.0 - Rocketseat

Aula 01

## Como estudar programação com eficiência

- Aprendizado ativo x passivo
    - **Ativo**: Tudo que faz você agir e pensar;
    - **Passivo**: você não toma ações
    (ouvir, ler, assistir)
- **Metodologia** **PARE** (aprendizado ativo)
    - Perguntar
    - Anotar
    - Revisar
    - Explicar
    - PARE



### Não estou entendendo tudo, o que faço?

- É normal
- Não tem problema não entender tudo de primeira, **continue**.

<aside>
💡 Leva tempo e mais conhecimento para que as coisas façam sentido.
</aside>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Aula 02

## Fundamentos  da programação

Programação nada mais é do que ensinar o computador



### Ensinar o computador

- **Algoritmos**
    
    → Sequência de passos, conjunto de regras
    
- **Lógica de programação**
    
    → Maneira de pensar
    
- **Sintaxe**
    
    → Maneira correta de escrever
    



## Front-end e Back-end

> É uma comunicação.
> 

→ Imagina uma farmácia onde você vai pedir um remédio para o atendimento.

### Cliente x Servidor

- Cliente;
- Navegador (browser);
- Servidor;
- Computador em algum lugar do mundo que tem os códigos;
- Troca de dados;
- Cliente faz o pedido e Servidor escuta e responde ao pedido;
- Cliente é o front-end, servidor é o back-end.

### Tecnologias Front-end

- **HTML**
    
    → Linguagem de marcação de texto para estrutura os textos, criar links, imagens, etc.
    
- **CSS**
    
    → Linguagem de estilo para deixar o HTML bonito.
    
- **JavaScript**
    
    → Linguagem de programação que funciona no Navegador.
    

### Tecnologias Back-end

- Node.js
    
    → Rodar o JavaScript no computador.
    
- SQL
    
    → Banco de dados para proteger os dados do seu programa.
    



## HTML

- Estruturar textos, criar links, imagens, vídeo, etc.
- Hypertext Markup Language.
- Linguagem de marcação de texto.

### HypertText

- Hiper texto
- Texto que contém links

### Markup

- Marcação do texto
- Elemento HTML ou tag

<aside>
💡 Existem inúmeras tags e cada uma deles irá servir para um determinado propósito.
Ex.: imagem, texto grande, link, parágrafo, etc.
</aside>

### Sintaxe de uma tag

- Sinal de menor, nome da tag, sinal de maior, conteúdo, sinal de menor, barra, nome da tag, sinal de maior.

```html
<p>conteúdo</p>
```

### Atributos

- Adicionam informações e configurações à uma tag
- Sintaxe
    
    → Nome do atributo, sinal de igual, aspas duplas (abre), valor, aspas duplas (fecha)
    

```html
<a href="#">link</a>
```

### Comentários

- Ignorar linhas de código
- Adicionar informação
- Somente acessível por quem coda

```html
<!-- Aqui vem um comentário -->
<!--
    Várias linhas de código 
    poderão ser ignoradas 
    ao utilizar comentário
-->
```


## GitHub

### O que é?

- Plataforma online para colocar seus códigos;
- Trabalha com o Git;
- Versionamento de código;
- Trabalhar em diversos projetos e times de código;
- Perfil para mostrar seu trabalho (portfólio).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Aula 03

## CSS

### O que é CSS?

- Apresentação visual para o cliente
- Estilos para o HTML
- Cascading Style Sheets
    
    → Folha de Estilo em Cascata
    

### Declaration

- Pedaço de código que irá ditar as propriedades e valores a serem
aplicadas a um elemento HTML
- Sintaxe
    
    → Seletor, chave (abre), propriedade, dois pontos, valor, ponto vírgula,
    chave (fecha)
    

```css
body {
  background: red;
}
```

### Comentários

- Ignorar parte do código
- Adicionar informações que serão visíveis somente pra quem coda

```css
/* Essa linha será ignorada */

/*
Poderemos ignorar várias 
linhas de código
dessa forma
*/
```

### Cascading

- Cascata
    
    → Quando há 2 (ou mais) declarações a última será mais relevante.
    

```css
body {
  background: red;
}

body {
  background: blue;
}
```

### Specificity

- Especificidade
    
    → Cada seletor tem um peso e a soma dos pesos, será levada 
    em conta para que determinada declaração seja mais específica.
    

```css
#id {
  /* peso 100 */
}

.class {
  /* peso 10 = Colocar a CLASS nos elementos que quero a mesma cor*/
}

element {
  /* peso 1 */
}
```

> A cascata perde prioridade e é priorizada a especificidade da declaração
> 

### Box Model

- Tudo são caixas
- Todos os elementos HTML serão considerados uma caixa, assim como uma 
caixa de papelã
- Caixas possuem determinadas propriedades, veja:
    
    → Conteúdo, Largura, Altura, Borda, Preenchimento (espaço interno), 
    Espaçamento (espaço externo)
    → Margin = Espaço externo
    → Padding = Preenchimento
    → Border = Borda da caixa
    → Width = Largura da caixa
    → Height = Altura da caixa
    → Box-sizing = Qual tamanho vai ficar a caixa
    → Text-align = Alinhamento do texto da caixa/conteúdo
    → Display = Destravar a caixa (flex)
     → Align-items = Alinha a linha dos itens na caixa
     → Justify-content = Alinha a coluna do conteúdo da caixa
    → Weight = Peso da fonte
    <br>
    <img src="https://nikitahl.com/images/dev-tools/box-model.png">
