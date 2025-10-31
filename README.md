## Descripción General

Este proyecto recrea el juego **Pacman** utilizando Python.  
El objetivo es mover a Pacman por el laberinto para recolectar puntos blancos mientras evita ser atrapado por los fantasmas.  

Cada fantasma se desplaza por el tablero según un algoritmo de movimiento mejorado, lo que hace el juego más desafiante.  

---

## Contenido del Repositorio

- **pacman.py** → Código principal del juego.  
  Contiene la lógica para el movimiento de Pacman, el comportamiento de los fantasmas, el dibujo del tablero y el sistema de puntuación.

---

## Controles del Juego

| Tecla | Acción            |
|:------|:------------------|
| **↑** | Mover hacia arriba |
| **↓** | Mover hacia abajo  |
| **←** | Mover hacia la izquierda |
| **→** | Mover hacia la derecha  |

---

## Cambios Realizados

Se realizaron las siguientes modificaciones al código original del juego **Pacman (FreeGames)**:

1. **Fantasmas más listos**  
   - Se mejoró la lógica de movimiento para que los fantasmas sigan rutas más inteligentes, persiguiendo a Pacman de forma más eficiente y evitando giros inútiles.  
   - Esto incrementa la dificultad y hace el juego más realista.

2. **Cambio del tablero**  
   - Se modificó la estructura de la matriz `tiles`, rediseñando el laberinto con nuevos pasillos, muros y zonas de escape.  
   - Esto permite un entorno de juego diferente y más dinámico.

3. **Fantasmas más rápidos**  
   - Se aumentó la velocidad de movimiento de los fantasmas reduciendo el intervalo del temporizador (`ontimer`) y ajustando sus vectores de desplazamiento.  
   - Resultado: partidas más intensas y menor margen de error.

---
**Autores**

Lizeth Jaqueline Balderas Sánchez
Felipe Gutiérrez Herrera
