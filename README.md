# Jquery-ProgBr

- $("Elemento").hide() - Ira Esconder o Elemento Passado

- .show() - Exiba os elementos correspondentes.

```

$(".titulo").hide() // por Padrão ira estar Escondido

setTimeout(() => {

}, 2000)

```

- $.noConflict();  caso eu esteja Utilizando um FrameWork, Que o $ e retirar o possível conflitos. Apos Utilizar ele vai acontecer um Erro no console, porque é preciso passar Invés de $, Jquery(".titulo")....


### Eventos

- $(".titulo").click() - Para Eventos de Click
  
- $(".titulo").mouseenter() - Evento para Passar o Mouse Por Cima

- $(".titulo").mouseleave() - Evento de Saida, por Exemplo selecionei o titulo, vou passar o mouse por cima, apos retirar essa função Dispara

- $(".titulo").dbclick() - Para Capturar Eventos de Dois Click