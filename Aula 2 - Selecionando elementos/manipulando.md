# Métodos - Selecionando e manipulando elementos no DOM! 

A estrutura de uma página HTML consiste em TAGS! 

*TAGS: 
<body> 
<h2>
<p>
<section>

*Atributos: 
id="titulo"
li
class="textos"


É possível fazer uma busca pelo elemento através do id ou tags ou até mesmo classes dele utilizando alguns métodos: 

*Métodos
document.getElementById("titulo");
document.getElementsByTagName("li")
document.getElementsByClassesName("textos")

Temos outros tipos de métodos seletores: 

document.querySelectorAll(".primeira-classe . segunda-classe")

Existem métodos para adicionar e deletar elementos: 
document.createElement(element) - Cria um novo elemento HTML
document.removeChild(element) - Remove um elemento
documento.appendChild(element) - Adiciona um elemento
document.replaseChild(new, old) - Substitui um elemento