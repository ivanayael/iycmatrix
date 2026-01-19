# 🟢 IYC Matrix - Digital Rain Effect

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tech](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Una recreación visualmente impactante del icónico efecto "Digital Rain" de la película **The Matrix**. Este proyecto utiliza el elemento `<canvas>` de HTML5 para renderizar de forma eficiente miles de caracteres cayendo en tiempo real.

---

## 📸 Demo Visual

> **[Configura aquí tu enlace de GitHub Pages si lo tienes activo]**
> *Simulación del flujo de datos de la Matrix directamente en tu navegador.*

---

## ⚡ Características

* **Alto Rendimiento:** Renderizado fluido mediante `requestAnimationFrame` y manipulación directa de `CanvasRenderingContext2D`.
* **Diseño Responsivo:** El efecto se ajusta automáticamente al tamaño de la ventana del navegador.
* **Personalización:** Fácil de modificar (colores, velocidad de caída, densidad de caracteres y tipos de símbolos).
* **Ligero:** Código puro (Vanilla JS), sin dependencias externas ni frameworks pesados.

---

## ⌨️ Cómo usarlo

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/ivanayael/iycmatrix.git](https://github.com/ivanayael/iycmatrix.git)
    ```
2.  **Abre el proyecto:**
    Solo necesitas abrir `index.html` en cualquier navegador moderno.

3.  **Personalización rápida:**
    Dentro del archivo JavaScript principal, puedes ajustar las siguientes variables:
    * `fontSize`: Cambia el tamaño de la fuente.
    * `color`: Modifica el clásico verde (`#0F0`) por cualquier otro.
    * `speed`: Ajusta los intervalos de actualización.

---

## 🛠️ Tecnologías

* **HTML5** (Canvas)
* **CSS3** (Estilizado de fondo y contenedores)
* **JavaScript (ES6+)** (Lógica de animación y generador de caracteres aleatorios)

---

## 🧪 Conceptos de Programación Aplicados

Este proyecto demuestra el uso de:
* **Bucles de animación:** Control de FPS en el navegador.
* **Arrays & Mapping:** Gestión de las posiciones verticales de cada columna de caracteres.
* **Matemáticas aplicadas:** Uso de `Math.random()` para generar la aleatoriedad de los glifos.

---

## 👤 Autor

**Ivana Yael**
* GitHub: [@ivanayael](https://github.com/ivanayael)

---
*"Welcome to the desert of the real."* 🕶️
