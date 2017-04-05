# Introdução

- Qualquer navegador da suporte ao JavaScript
- Usado para dar dinamismo e iteratividade nas páginas melhorando a usabilidade do usuário
- Node.js é uma plataforma que permite usar JavaScript do cliente no servidor
- Para ser interpretado como JavaScript tem que escrever o código dentro da tag script.Se colocarmos scripts diretamente no corpo da mensagem ele será interpretado como texto.

### Mensagem no navegador
- Duas maneiras de mostrar uma mensagem no navegador:
```html
<script>
  1- aparecer uma mensagem de alerta pop-up
  alert("Ola mundo");
  2- aparecer mensagem no console
  console.log("Oi mundo");
</script>
```
### DOM - Document Object Model
- Representação do HTML para o JavaScript
- Para ter acesso a ele precisamos de dentro do script utilizar o document

#### Manipulação do DOM - Query Selector
- Para pesquisar alguma coisa do document usa-se a função querySelector() no final da página, como por exemplo:
```html
 console.log(document.querySelector("h1"));
```
- Para salvar a parte do document encontrada em uma variavel:
```html
   var titulo = document.querySelector("h1");
```
- Para imprimir o conteudo de uma variavel:
```html
   console.log(titulo.textContent);
```
- Para manipular o conteudo de uma tag é só igualar a um outro conteudo:
```html
titulo.textContent = "Banana";
```

## Erros do console
- Unexpected Identifier = não entende o conteudo que está dentro da tag script como uma de suas funções.
