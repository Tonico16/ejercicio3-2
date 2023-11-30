1.Explicar cuantas maneras existen para vincular html con css
rsp 1. existen 3 maneras :
se puede vincular de mismo html con la etiqueta style
otra manera es haciendo un archivo .css y vinculandolo con la etiqueta <link> 
y la tercera es poniendole de frente a la la linea del elemnto que quieres darle el estilo

2. Explicar con sus palabras el conjunto de reglas de CSS (selector , propiedad , valor)

el selector es el elemento donde se aplcara el estilo
la propiedad es el elemento que se quiere ejecutar
y el valor es lo que va hacer que se modifique

3. Explicar los 4 conceptos importantes con ejemplos ( selectores, herencia , cascada , especificidad

los selectores son patrones y se usan para saber donde se aplicaran los estilos como <h1>,<h2>,<p>,etc
Las herencias hacen que se ejecuten estilos a todos los elementos dentro de ellas ya que el es el estilo principal.

la cascada es cuando cada selector se le pone un valor diferente y siempre el ultimo es el que se ejecuta.

h1{
    color: red;
}
h1{
    color: blue;     este sera el color que se usara ya que es el ultimo puesto
}

la especificidad es el nivel de importancia y peso que tiene cada selector y eso impondra cual es el que reconocera como principal el css existen las etiquetas,clases,id,inline e !important