# Guia Turístico - Itália
---
Este projeto tem como principal objetivo a construção de um site de turismo/informativo sobre cidades italianas e a Itália, como um todo.

## Linguanges e Frameworks Utilizados:
---
- Html
- Css
- JavaScript
- Bootstrap

## O BootStrap
---
Segundo o site do próprio bootstrap:
"Boostrap é um **framework** gratuito e *open-source* do CSS, voltado para o desenvolvimento de aplicações responsivas, *mobile-first* e o front-end de aplicações web."
Contém templates para:
- Tipografias
- Formulários
- Botões
- Navegação(Navbar)
- E outros componentes para construção de interfaces
Utiliza HTML, CSS e JavaScript para a construção destes templates.
Além destes templates, nos permite "escrever css no html" por meio das classes.
**Exemplo:**
```
#CSS
.rodape {
	background-color: light;
	display: flex;
	justify-content: center;
	align-items: center;
	padding-top: 2px;
}

#Bootstrap
<footer class="bg-light d-flex justify-content-center align-items-center pt-2">
```

## O Projeto
---
O Projeto possui:
- 8 páginas html
- 1 página css
- Pasta de imagens e pastas
Os arquivos do projeto foram divididos em pastas a fim de melhorar a organização e facilitar a manutenção do código.
Todas as páginas foram construídas com HTML **semântico**, recursos de **acessibilidade** e com foco na **usabilidade**.

## Páginas
Todas as páginas possuem uma **navbar** e um **footer**.
Todas as páginas possuem as tags:
- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<meta>`
- `<link>`
- `<title>`
- `<body>`
- `<header>`
- `<nav>`
- `<main>`
- `<script>`
- `<footer>`
Todas as tags, quando necessário, com seus pares para fechamento.
Outras tags também são usadas, como:
- `<div>`
- `<a>`
- `<img>` -> Com o parametro **"alt"** para acessibilidade
- `<button>`
- `<span>`
- `<ul>`
- `<li>`
- `<p>`
- `<h1>`
Todas as páginas focadas na exposição das regiões, possuem as tags:
- `<aside>`
- `<main>`
- `<article>`
- `<header>`
- `<figure>`
- `<hr/>`
---
### Index / Home
Esta página possui um carrossel construído com o auxilio do bootstrap.
Utilizei *background-images* a fim de não perder a qualidade da imagem, por isso para fazer os reursos de acessibilidade utilizei o parametro `title`.

### Inscreva-se! / Form
Esta página contém um formulário com 9 campos e 1 botão.
Todas os campos possuem um `<input>` e um `<label>`. Sempre que possível, o **input** possui um *placeholder*, um *type* e um *id* para ser utilizado no *for* do **label**. 


### Itália
Esta página expõe as príncipais informações sobre a Itália. Contém os tópicos:
- Itália
- História
- Geografia

### Ligúria
Esta página expõe as príncipais informações sobre a Ligúria. Contém os tópicos:
- Ligúria
- Administração
- Anexos

### Alpes
Esta página expõe as príncipais informações sobre a Alpes. Contém os tópicos:
- Alpes
- Geografia
- Anexos

### Lombardia
Esta página expõe as príncipais informações sobre a Lombardia. Contém os tópicos:
- Lombardia
- Administração
- Anexos

### Sicília
Esta página expõe as príncipais informações sobre a Sicília. Contém os tópicos:
- Sicília
- Administração
- Anexos

### Sardenha
Esta página expõe as príncipais informações sobre a Sardenha. Contém os tópicos:
- Sardenha
- Administração
- Anexos