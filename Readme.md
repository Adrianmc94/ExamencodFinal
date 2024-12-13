# Examen 1ª Evaluación

---
 
Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente.

### Primer apartado, Diagrama de flujo:

![DiagramaExamen (1).jpg](DiagramaExamen%20%281%29.jpg).



### Explicación: 
1. **Inicializo el tablero de Damas 8x8**:  
   Creo una matriz de 8x8 donde cada casilla puede estar vacía o ocupada por una ficha de algún jugador ('X' o 'O').

2. **Cuento las fichas de cada jugador**:  
   Inicializo dos variables (`contador_X` y `contador_O`) en 0, para contar las fichas de cada jugador.

3. **Recorro el tablero**:  
   Utilizo dos bucles anidados para recorrer cada fila y columna del tablero (8x8).

4. **Verifico si la casilla está ocupada**:  
   Si la casilla contiene una ficha (es decir, no está vacía), imprimo la coordenada de la casilla y el tipo de ficha.

5. **Cuento las fichas**:  
   Si la casilla tiene una ficha del Jugador 1 ('X'), incremento el contador de Jugador 1. Si tiene una ficha del Jugador 2 ('O'), incremento el contador del Jugador 2.

6. **Determino quién va ganando**:  
   Comparo los contadores de fichas de ambos jugadores y muestro quién tiene más fichas, o si hay un empate.