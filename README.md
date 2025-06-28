# Proyecto-Final-Curso-basico-Python
Este repositorio contiene el ejercicio final que tuve que realizar en un curso basico de Python, el cual me ayudo a entender de mucho mejor manera el uso de diferentes funciónes. Mi tarea era escribir un simple programa que simule jugar a tic-tac-toe (nombre en inglés) con el usuario

Este Pull Request incluye la versión final del juego clásico "Tic Tac Toe" desarrollado en Python. El juego es jugado en consola, donde el usuario compite contra la máquina. La implementación incluye verificación de movimientos válidos, alternancia de turnos, detección automática de victorias y un formato visual del tablero.

## Funcionalidades implementadas:
- Tablero visual estructurado como cuadrícula 3x3
- Primer movimiento automático de la máquina en el centro
- Captura del movimiento del usuario con validación de entrada
- Selección aleatoria de movimiento para la máquina (sin IA)
- Verificación automática de ganador tras cada turno
- Control de empate cuando no hay más movimientos disponibles
- Finalización del juego con mensaje personalizado según el resultado

## Módulos principales:
- `display_board(board)`: muestra el estado actual del tablero
- `enter_move(board)`: gestiona el movimiento del usuario
- `draw_move(board)`: genera un movimiento válido para la máquina
- `victory_for(board, sgn)`: determina si hay un ganador
- `make_list_of_free_fields(board)`: identifica casillas disponibles

## Resultados esperados:
- Juego funcional y jugable desde consola
- Interacción clara con el usuario
- Flujo de juego limpio y modular

Este proyecto fue desarrollado con enfoque en la lógica y experiencia del usuario sin utilizar bibliotecas gráficas ni interfaces externas.
