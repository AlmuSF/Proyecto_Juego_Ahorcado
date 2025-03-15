# proyecto-da-promo-50-modulo-1-team-III
Juego del ahorcado

Se ha solicitado el desarrollo de un juego clásico: el ahorcado. 
Se requiere tener en cuenta que habrá 2 jugadoras, una elige la palabra secreta y la otra jugadora, intentará adivinarla. 

Inicialmente, hemos analizado la estructura y lógica del juego, teniendo en cuenta las solicitudes del cliente. 
En primer lugar hemos desarrollado un código funcional y práctico. Posteriormente lo hemos mejorado incluyendo detalles y mejora que no habíamos desarrollado en la primera fase. 
A continuación, indicamos las fases del juego y de nuestro trabajo:
- Diseño de la bienvenida y reglas del juego. 
- Diseño de la estructura del código que permitirá ejecutar el juego. 
- Diseño del cierre del juego, permitiendo volver a jugar si así lo desean las jugadoras. 
- Realizar pruebas intermedias para detectar errores y comprobar que el código funciona. 
- Estudiar propuestas de mejora del código, por ejemplo, introduciendo funciones. 

Para el desarrollo del código, lo hemos estructurado en 4 bloques, que detallamos a continuación.
1. Bienvenida. 
Para comenzar, se da la bienvenida a las jugadoras, se muestran las reglas del juego y se da la opción de jugar o salir. 

2. Juego nuevo. 
Se trata de una función que permite volver a jugar tras finalizar una partida.

3. Desarrollo del juego. 
Es la estructura principal del juego. Se comienza por la solicitud a la jugadora 1 de la palabra secreta. 
A continuación, se solicita a la jugadora 2 que trate de adivinar la palabra secreta introduciendo letras. 
Según la jugadora 2 acierte o no, se va dibujando el muñeco ahorcado o se van mostrando los aciertos en el orden correspondiente. 
Si acierta la palabra, se mostrará completa. Si falla, se mostrará el muñeño ahorcado completo. 
Finalmente, podrá decidir si quieren jugar otra partida o si prefieren salir. 

4. Juego completo. 
Se trata de una función que permite ejecutar el juego completo, incluyendo la bienvenida, el desarrollo completo y la posibilidad de continuar jugando.

