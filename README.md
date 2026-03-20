#  Notificador de Tiempo por Voz

Este es un mini proyecto desarrollado para mejorar la **gestión del tiempo y la productividad**. Se trata de un reloj digital con estética futurista que, al activarse, notifica mediante voz cada 15 minutos la hora actual.

Ideal para personas que pierden la noción del tiempo mientras trabajan o estudian y necesitan un recordatorio auditivo para mantenerse en foco.

![Licencia](https://img.shields.io/badge/license-GPL--3.0-blue)
![Tecnologías](https://img.shields.io/badge/tech-HTML5%20%7C%20CSS3%20%7C%20JS-00fff7)

## Funcionalidad

* **Visualización en Tiempo Real:** Reloj digital con formato de 24 horas y segundero.
* **Avisos cada 15 Minutos:** El sistema utiliza la **Web Speech API** para anunciar la hora exacta de forma automática en los minutos :00, :15, :30 y :45 de cada hora.
* **Interfaz Galáctica:** Diseño con efectos de neón, gradientes radiales y animaciones de pulso inspiradas en interfaces de ciencia ficción.
* **Interactividad:** Botón de activación/desactivación de voz con retroalimentación visual inmediata.

## Stack Tecnológico

* **HTML5:** Estructura de la aplicación.
* **CSS3 (Efecto Neón):** * Uso de `text-shadow` dinámicos para el efecto de brillo.
    * Animaciones `@keyframes` para el efecto de pulsación.
    * Tipografía personalizada mediante Google Fonts (`Orbitron`).
* **JavaScript (Vanilla):**
    * **Web Speech API:** Utilización de `SpeechSynthesisUtterance` para la síntesis de voz.
    * **Gestión del Tiempo:** Uso de `setInterval` para la actualización del reloj y la lógica de los avisos cada cuarto de hora.

## Por qué hice este proyecto

A menudo, al programar o diseñar, es fácil entrar en estado de *flow* y perder la noción del paso de las horas. Creé esta herramienta para:
1.  **Cuantificar el tiempo** sin necesidad de mirar el reloj constantemente.
2.  **Reducir la fatiga visual**, al recibir la información por audio.
3.  **Practicar la integración de APIs nativas del navegador** de forma creativa.

## Cómo usarlo

1.  Clona el repositorio o descarga el archivo `alerta.html`.
2.  Abre el archivo en tu navegador.
3.  Haz clic en el botón **"Activar Voz"** (el navegador requiere una interacción del usuario para habilitar el audio).
4.  ¡Listo! El sistema te avisará cada 15 minutos.

## Licencia

Este proyecto está bajo la licencia **GNU General Public License v3.0**.

---
*Desarrollado para conquistar el tiempo, un cuarto de hora a la vez.*
