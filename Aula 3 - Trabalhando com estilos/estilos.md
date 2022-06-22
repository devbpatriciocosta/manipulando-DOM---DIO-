# Aula 3 - Trabalhando com estilos

Como falamos de projetos front-end sempre vamos falar de HTML CSS e JS;

Através de ids, classes e pseudo-elementos nós conseguimos modificar e selecionar esses elementos e colocar estilo neles através do CSS. 



Mas como acionar essas classes no JS? 
Bom, utilizamos o método: 

Element.classList - O classList é uma propriedade desse elemento. 
Podemos colocar: 

const meuElemento = document.getElementById("meu-elemento");

meuElemento.classList.add("novo-estilo") - ADD uma classe ao "meu estilo";

meuElemento.classList.remove("classe") - Remove a classe!

meuElemento.classList.toggle("dark-mode") - Adiciona a classe "dark-mode" caso ela não fala parte da lista e remove caso ela faça parte dessa lista! 


Mas se quisermos acessar diretamente o CSS de um elemento para mudar o estilo?
Podemos usar:

document.getElementsByTagName("p").style.color="blue";