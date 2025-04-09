# 👋 Mediapipe Pose Driver

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Demo](https://img.shields.io/badge/Demo-Live!-brightgreen)](https://soyunomas.github.io/mediapipe-pose-driver-game/index.html)

Una aplicación web que implementa un juego de conducción 🚗💨 simple controlado mediante la detección de pose de manos utilizando la webcam  Webcam y la librería Mediapipe Pose de Google. ¡Esquiva los coches enemigos y logra la máxima puntuación!

## 📝 Descripción Breve

Este proyecto es un juego de carreras 2D estilo arcade 👾 donde controlas un coche moviendo tus manos frente a la webcam. Mediapipe Pose detecta la inclinación de tus muñecas 🙌 para dirigir el coche hacia la izquierda o la derecha, con el objetivo de evitar colisiones 💥 con otros vehículos y conseguir la mayor puntuación posible.

## 🖼️ Captura de Pantalla / Demo

![Captura de Pantalla del Proyecto](URL_A_LA_IMAGEN_O_PLACEHOLDER)

Puedes probar una **[Demo en Vivo aquí](https://soyunomas.github.io/mediapipe-pose-driver-game/index.html)**.

## ✨ Características Principales

*   **👋 Control por Gestos:** Utiliza la inclinación de las muñecas (detectadas por Mediapipe Pose) para controlar el movimiento lateral del coche.
*   **💥 Juego de Esquivar:** El objetivo principal es evitar chocar contra los coches enemigos que aparecen en la carretera.
*   **📷 Visualización de Cámara y Pose:** Muestra la imagen de la webcam y superpone la detección de las muñecas para feedback visual.
*   **🛣️ Carretera Curvada Dinámica:** La carretera presenta curvas generadas proceduralmente.
*   **🌲 Elementos de Escenario:** Objetos decorativos (árboles/césped) a los lados de la carretera.
*   **📈 Dificultad Progresiva:** La velocidad y la frecuencia de los enemigos aumentan con la puntuación.
*   **💯 Puntuación:** Registra la puntuación basada en el tiempo sobrevivido.
*   **🖥️ Pantalla Completa:** Opción para jugar en modo inmersivo.
*   **🎨 Sprites:** Utiliza hojas de sprites para los gráficos.
*   **🎮 Interfaz Clara:** Indicadores de carga, pantalla de "Game Over" y botón de reinicio.

## 🛠️ Tecnologías Utilizadas

*   **HTML5:** Estructura de la página.
*   **CSS3:** Estilos, layout (Flexbox) y modo pantalla completa.
*   **Bootstrap 5.3.2:** Framework CSS para diseño y componentes.
*   **JavaScript (ES6+):** Lógica del juego, interacciones y detección de pose.
*   **Mediapipe Pose:** Detección de pose humana en tiempo real.
    *   `@mediapipe/camera_utils`
    *   `@mediapipe/control_utils`
    *   `@mediapipe/drawing_utils`
    *   `@mediapipe/pose`
*   **HTML Canvas:** Renderizado del juego y visualización de pose.

## 🚀 Instalación / Visualización Local

Para ejecutar este proyecto en tu máquina:

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/soyunomas/mediapipe-pose-driver-game.git
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd mediapipe-pose-driver-game
    ```
3.  **Abre el archivo `coches.html`:**
    Simplemente haz doble clic en el archivo `coches.html` o ábrelo desde tu navegador web (Chrome, Firefox, Edge, etc.).
4.  **🚨 Permisos de Cámara:** Tu navegador te pedirá permiso para acceder a la webcam. ¡Necesitas concederlo para jugar!
5.  **🌐 Conexión a Internet:** Necesaria para cargar las librerías de Bootstrap y Mediapipe desde sus CDNs.
6.  **🖼️ Recursos Locales:** Asegúrate de que `cars_sprite_sheet.png` y `scenery_sprite_sheet.png` estén en la misma carpeta que `coches.html`.

## 🕹️ Cómo Jugar

1.  Espera a que carguen los recursos (verás "Cargando Recursos...").
2.  El juego comenzará automáticamente. Verás tu coche abajo y la webcam al lado (o como mini-ventana en pantalla completa).
3.  Coloca tus manos frente a la cámara para que detecte tus muñecas (verás una línea turquesa).
4.  **➡️ Mover a la Derecha:** Inclina las manos (muñeca derecha más baja).
5.  **⬅️ Mover a la Izquierda:** Inclina las manos (muñeca izquierda más baja).
6.  **⬆️ Ir Recto:** Mantén las manos niveladas.
7.  ¡Esquiva los coches enemigos! 🏎️💨🚓
8.  Usa el botón "Pantalla Completa" para una mejor experiencia.
9.  Si chocas 💥, verás "GAME OVER". Haz clic en "Reiniciar" para volver a intentarlo.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

*(Puedes añadir un archivo `LICENSE` con el texto completo si lo deseas).*

## 🧑‍💻 Contacto

Creado por **soyunomas** ([@soyunomas en GitHub](https://github.com/soyunomas))
