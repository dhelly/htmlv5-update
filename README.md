# HTML v5 e a nova semântica

> Não é tão nova assim, mas eu não estava por dentro de todas*

Atualizando meus conhecimentos em html. Entendendo a aplicação das *tags*.

Pontos importantes:

- Apenas usar uma única *tag* `<h1>` por página, pois só podemos ter um conteúdo mais importante por página.
- Substituir as marcações de ênfase `<b>` e `<i>` que apenas altera visualmente por `<strong>` e `<em>`
- As imagens possuem *tags* específicas e agora usaremos elas assim

```html
<figure>
    <img src="assets/images/figura.png" alt="Foto do Matriz Curricular do Curso">
    <figcaption>Matriz Curricular do Curso</figcaption>
</figure>
```

## Estrutura de um arquivo html mais simples com a semântica do Html5

```html
<!DOCTYPE html>
<html lang="pt-br">
   <head>
       <meta charset="utf-8"/>
       <title>Estrutura do HTMLv5</title>
   </head>
   <body>
       <header>
            #LOGO
            #MENU
       </header>

       <main>
            #CONTEÚDO
       </main>
       
       <footer>
            #PÁGINAS DO SITE
            #LINKS LEGAIS
       </footer>

   </body>
</html>
```

## Novas Semântica
![](https://miro.medium.com/max/562/0*yi18C1GKlWY4l6Ef.png)

fonte: [HTML5: entendendo a estrutura e a semântica - Edu Agni](https://medium.com/@eduagni/html5-entendendo-a-estrutura-e-a-sem%C3%A2ntica-db5f17808c7)

Principais dúvidas estão no uso do `section` do `article`. Quando podemos usar?
Podemos pensar no `section` com um container de conteúdo semântico, assemelhando a `div`. Já o `article` tem realmente o conteúdo. Ambos podem ser usados mais de uma vez.

## Outras atualizações importantes.

- Uso do atributo `title`
Fornece informações específicas sobre um elemento. Importante para a apresentação de conteúdo dos usuários que usam leitores de tela.

```html
<p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
<p title="Free Web tutorials">W3Schools.com</p> 
```
fonte: [HTML title Attribute - W3School](https://www.w3schools.com/tags/att_global_title.asp)
