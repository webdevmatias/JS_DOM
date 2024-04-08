# Manipulação do DOM com JavaScript

Neste repositório, você aprenderá sobre a manipulação do DOM (Document Object Model) utilizando JavaScript. O DOM é uma interface de programação para documentos HTML, XML e SVG. Ele representa a estrutura do documento e permite que os programas alterem sua estrutura, estilo e conteúdo.

## O que é o DOM?

O DOM é uma representação em árvore do documento. Cada elemento no documento é um nó no DOM, e os relacionamentos entre os elementos (pai, filho, irmão) são representados por suas relações de nó.

## Manipulando o DOM com JavaScript

JavaScript fornece métodos poderosos para manipular o DOM. Alguns dos métodos comuns incluem:

- Selecionando elementos: `document.getElementById()`, `document.querySelector()`, `document.querySelectorAll()`.
- Manipulando conteúdo: `element.innerHTML`, `element.textContent`, `element.setAttribute()`, `element.removeAttribute()`.
- Manipulando estilos: `element.style`, `element.classList.add()`, `element.classList.remove()`.
- Criando e removendo elementos: `document.createElement()`, `element.appendChild()`, `element.removeChild()`.

## Selecionando elementos, exemplos:
- const elementById = document.getElementById('meuElemento');
- const primeiroElemento = document.querySelector('.minhaClasse');
- const todosElementos = document.querySelectorAll('p');

## Manipulando conteúdo, exemplos:
- elementById.innerHTML = ' &lt; Novo conteúdo HTML  &gt; ';
- element.textContent = 'Novo conteúdo de texto';
- element.setAttribute('id', 'novoId');
- element.removeAttribute('id');

## Manipulando estilos, exemplos:
- element.style.color = 'red';
- element.classList.add('novaClasse');
- element.classList.remove('minhaClasse');

## Criando e removendo elementos, exemplos:
- const novoElemento = document.createElement('div');
- element.appendChild(novoElemento);
- element.removeChild(novoElemento);
