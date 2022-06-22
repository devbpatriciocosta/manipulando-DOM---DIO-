# Aula 1 - O que é DOM e o que é BOM! 


*DOM - Documento Object Model: 

O DOM HTML é um padrão de como acessar e modificar os elementos HTML de uma página WEB. 
Todos os BROWSERS vão ter um DOM; 

Dentro do BROWSER você tem o elemento DOCUMENTO que se desenrola em vários nós menores, como o elemento raíz (ROOT ELEMENT - <html>) dentro desse elemnto nós temos várias tags filhas, como por exemplo: Element (<head>), Element (<body>) e por aí vai. 

É como uma árvore de hierarquia repleta de nós (galhos) que podem ter atributos, tags filhas ou não... e até mesmo elementos irmãos. 


*BOM - Browser Object Model:

O BOM é tudo que está dentro da WINDOW. 

Sempre que abrimos um browser nós temos uma janela (window) que é a mãe de tudo, que demonstra para nós uma árvore de dependências. É dentro dela que está o nosso DOM (o document). 

Na  janela nós teremos: 
- history;
location
screen
navigator

