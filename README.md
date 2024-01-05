# Rock-paper-scissors
Práctica del curso de especialización de Inteligencia Artificial y Big Data - IES de Teis
Realizado por: Samuel Andón Novo

# Entorno de tareas
Entorno de tareas | Observable| Agentes | Determinista | Episódico | Estático | Discreto | Conocido
:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
 RPS | Parcialmente observable | Multiagente | Determinista | Episódico | Estático | Discreto | Conocido |

- **Parcialmente observable:** debido a que a la hora de llevar a cabo la acción, no contamos con la visión total del entorno del juego. Es decir, no contamos con información acerca del adversario hasta que no realiza su acción de sacar una de las 3 posibilidades.
- **Multiagente:** para llegar al objetivo del juego, el cuál es ganar, es necesario jugar contra alguien.
- **Determinista:** conocemos las opciones que pueden realizar los jugadores (piedra, papel y tijera), sin existir ningún elemento aleatorio que permita la creación de una nueva opción.
- **Episódico:** centrándonos en que el entorno es cada una de las partidas, única y exclusivamente cada partida, las acciones realizadas hasta cumplir el objetivo del juego no dependen en nada para la siguiente partida.
- **Estático:** mientras que los jugadores deliberan las acciones que van realizar, no cambia el entorno.
- **Discreto:** hay número finito de posibilidades a realizar.
- **Conocido:** ya que es conocido y jugado por millones de personas.

## Estructura del agente

