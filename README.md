# pyGame-test-project
test project for kodland (python) by Julian Velandia

Por medio del archivo game.py podemos encontrar que, se usaron tres distintas clases como son Player(), Enemy(), Laser() y Game(), 
cada uno con sus respectivos atributos y métodos según lo requería, además de, haber implementado la libreria PyGame para la creación 
del proyecto en su totalidad no habiendo usado otra libreria además de random, el fondo fue creado a partir de circulos de pequeño tamaño
en posiciones aleatorías y su respectiva animación de caída, los enemigos con una animación de movimiento hacia sus lados a través del 
eje X y el jugador en la parte inferior de la ventana con movimiento completo en el eje X a través del mouse.

La dimensión de la ventana está establecida para un monitor de resolución 720p.

Para iniciar una partida se debe dar click a cualquier tecla, esto hará que se de inicio y se cargue en la misma ventana a los enemigos y
el fondo, a parte del jugador mismo, cada que se realice un click con el mouse se disparará un láser que al entrar en contacto con un enemigo
hara que tanto el láser como el enemigo desaparezcan y sume un punto al puntaje total que se mostrará al acabar la partida y para iniciar nuevamente
tan sólo se tendrá que precionar cualquier tecla de nuevo.

Los métodos funcionales creados fueron: process_events(), run_controller() y display_frame(), todos parte de la clase Game que
se ocupan de manejar los eventos durante la ejecución del programa, la lógica manejada por el programa y, el dibujo y actualización de la ventana, cada uno respectivamente.
