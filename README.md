# Escaleras y Resbalderas
Juego versión Escaleras y Serpientes relacionado a Seguridad en Internet, es un videojuego en Scratch desarrollado con finalidades educativas.

## Objetivos
Al completar esta actividad los estudiantes podrán: 

Armar un juego completo tipo escaleras y serpientes.
Aprender manejo de funciones y condicionales de complejidad media.
Utilizar números randómicos y envío de mensajes para la construcción de un dado.
Hacer uso de variables para controlar las dinámicas del juego.

## Descripción de la actividad
Esta actividad es parte y complemento del juego de cartas “Escaleras y Resbaladeras”, diseñada para reflexionar sobre cuidados y buenas prácticas en Internet.

Para completar el juego, los estudiantes aprenderán muchos conceptos de fundamentos de programación para la construcción de un videojuego real.

La guía está construida para diferentes niveles, pero se recomienda que los estudiantes tengan un nivel medio en programación con Scratch.
Tiempo sugerido
120 minutos.

## Recursos
Escaleras y Resbaladeras en Scratch: https://scratch.mit.edu/projects/318775244/

## Puntos para la reflexión
¿Cómo funciona un dado de juego?
¿Cómo es el movimiento de fichas dentro de un tablero de juego de izquierda a derecha?
¿Qué acciones se puede abstraer y simplificar en funciones?

## Escaleras y Resbaladeras
Ingresar al recurso dentro de Scratch y hacer clic en reinventar.
Borrar todo el código sin borrar los personajes.

## Análisis del juego
Desarrollar junto a los estudiantes el siguiente análisis de diseño de juego.

## Personajes y objetos
Tortuga
Dado
Flecha arriba
Flecha izquierda
Flecha derecha
Tarjetas positivas
Tarjetas negativas

## Escenario
Tablero en cuadros con 20 espacios, las escaleras y resbaladera están previamente dibujados.

## Dinámicas
El jugador principal (la tortuga), gana la partida cuando llega a la posición número 20 y al quedarle un último movimiento logra salir del tablero.

Cada vez que el personaje llega a un espacio del tablero con un signo de aprobación verde y una escalera dibujada, se muestra una tarjeta positiva del mazo, y avanza posiciones adonde apunta la escalera.

Cada vez que el personaje llega a un espacio con una “X” roja y una resbaladera, se muestra una tarjeta negativa y el personaje retrocede hasta donde termina la resbaladera.

El personaje terminar el juego con el número de pasos exactos para salir del tablero.

## Mecánicas
El jugador lanza el dado y el resultado corresponde a la cantidad de pasos.

El personaje se mueve la cantidad de pasos marcada por el dado, a su vez se marca la posición del personaje en el tablero.

El personaje solo podrá moverse en el sentido determinado del tablero, de derecha a izquierda en algunas filaes, y de izquierda a derecha en otras, no podrá subir hacia arriba, salvo cuando esté en el final de la línea.

Si el personaje llega al final de la fila y aún conserva pasos disponibles, el personaje solo podrá subir hacia arriba.

Si el personaje llega al final de la última fila del tablero, y le sobran pasos mayores a los necesarios para salir, los pasos solo pueden ser gastados retrocediendo.
