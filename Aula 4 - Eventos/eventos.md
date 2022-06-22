# Aula 4 - Tipos de eventos e acionando eventos através do DOM!

Eventos são qualquer tipo de ação que o usuário faz na página da WEB quando ele interage com aquela página; 

Tipos de evento: 

Eventos de mouse
- Mouseover;
- Mouseout;

Eventos de click:
- Click
- DBclick

Eventos de atualização: 
- Change
- Load

Mas, como acionar esses eventos?

Nós utilizamos a função EVENT LISTENER: 
Ela é uma função utilizada diretamente no JS, cria um evento que vai ser acionado no momento em que o usuário realizar determinada ação. 

const botao = document.getElementById("meuBotao");

botao.addEventListener("click", outraFuncao);

É basicamente um "escutar" de evento.



Outra forma é colocar dentro do HTML. 
Exemplo: 

<h1> onclick="mudaTexto(this)"Clique aqui! </h1>

<script> 
  function mudaTexto(id) {
    id.innerHTML = "Mudei"
  }
</script>

Ou seja, especifica a função a ser chamada diretamente no elemento HTML;