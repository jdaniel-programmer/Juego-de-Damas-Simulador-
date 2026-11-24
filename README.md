# Damas - Juego de Mesa (Simulador)

Este proyecto es una aplicación de escritorio que simula el popular juego de mesa conocido como Damas. La lógica del programa está desarrollada en C++ estándar, completamente separada de la interfaz de usuario, permitiendo validar reglas, movimientos, capturas y condiciones de victoria de forma estructurada.

## Créditos

* Desarrollado por Jhonatan Rodríguez *(agrega aquí a tus compañeros de equipo si los hay)*.
* Proyecto académico para la materia *(coloca aquí el nombre de la materia)*.

## Características principales

* **Tablero interactivo de 8x8:** representación completa de casillas jugables y disposición inicial de fichas.
* **Modos de juego:** partida Jugador vs. Jugador (2 jugadores) *(o Jugador vs. IA, según hayas implementado)*.
* **Validación de movimientos reglamentarios:** desplazamientos en diagonal, restricciones de turno y verificación de casillas disponibles.
* **Sistema de capturas:** saltos simples y capturas múltiples encadenadas.
* **Coronación de Damas (Reinas):** promoción automática al alcanzar la fila opuesta del tablero.
* **Detección de fin de partida:** verificación automática de victoria por eliminación de fichas o bloqueo total de movimientos.

## Estructuras de Datos y Funciones Asociadas

* **Matrices / Arreglos bidimensionales:** representación lógica del tablero de juego y estado de cada celda.
* **Pilas / Listas enlazadas:** almacenamiento del historial de movimientos y registro de fichas capturadas *(ajusta esto según tu código)*.
* **Algoritmos de validación y búsqueda:** verificación de rutas diagonales válidas y detección de capturas consecutivas.

## Requisitos y Ejecución

1. Clonar este repositorio:
   ```bash
   git clone [https://github.com/jdaniel-programmer/Juego-de-Damas-Simulador-.git](https://github.com/jdaniel-programmer/Juego-de-Damas-Simulador-.git)
