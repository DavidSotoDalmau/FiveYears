# Documentación del Proyecto: Sala Recreativa Web

## Descripción
Este proyecto consiste en una sala recreativa en línea donde los usuarios pueden acceder a diferentes juegos clásicos a través de una interfaz de máquinas arcade. Al hacer clic en una máquina, el juego se carga en un frame inferior dentro de la misma página.

## Tecnologías Utilizadas
- **HTML**: Para la estructura de la página web.
- **CSS**: Para el diseño y la presentación visual.
- **JavaScript (opcional)**: Puede ser utilizado para mejorar la interactividad.

## Estructura del Proyecto
```
/sala-recreativa
│── index.html  # Página principal de la sala recreativa
│── froggy.html  # Juego de Froggy
│── checkers.html  # Juego de Checkers
│── sudoku.html  # Juego de Sudoku
│── connect-four.html  # Juego de Connect Four
│── 2048.html  # Juego de 2048
│── tic-tac-toe.html  # Juego de Tic Tac Toe
│── pacman.html  # Juego de Laberinto con Fantasmas
│── tetris.html  # Juego de Tetris
│── space-invaders.html  # Juego de Space Invaders
│── snake.html  # Juego de Snake
│── hanged-man.html  # Juego de Ahorcado
│── minesweeper.html  # Juego de Buscaminas
│── styles.css  # Archivo CSS opcional
│── /images  # Carpeta con imágenes de las máquinas arcade
│── README.md  # Documentación del proyecto
```

## Funcionalidad
1. **Interfaz de Máquinas Arcade**:
   - Cada máquina arcade tiene su propia imagen personalizada.
   - Al hacer clic en una máquina, el juego correspondiente se carga en un iframe inferior.
2. **Iframe para Juegos**:
   - Se usa un `iframe` de 1000px de altura para cargar los juegos sin salir de la página.
3. **Diseño Adaptativo**:
   - Se utilizan estilos CSS para que la sala recreativa se vea bien en diferentes dispositivos.

## Instalación y Uso
1. Clona este repositorio en tu máquina local:
   ```sh
   git clone https://github.com/DavidSotoDalmau/FiveYears.git
   ```
2. Abre `index.html` en un navegador web.
3. Haz clic en una máquina para cargar el juego.

## Personalización
- Para agregar nuevos juegos, crea un nuevo archivo HTML en la raíz del proyecto y agrégalo en `index.html`.
- Puedes cambiar las imágenes de las máquinas arcade reemplazando los archivos en la carpeta `/images`.

## Próximas Mejoras
- Agregar efectos de sonido al seleccionar una máquina.
- Mejorar la interfaz con animaciones en CSS o JavaScript.
- Implementar un sistema de puntuaciones guardado en localStorage.

## Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes modificarlo y compartirlo libremente.
