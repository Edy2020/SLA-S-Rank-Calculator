# S Rank Calculator — Solo Leveling: Arise

Una herramienta web de auditoría de estadísticas en tiempo real y guía de optimización para **Sung Jinwoo** y personajes DPS en *Solo Leveling: Arise*.

---

## Características Principales

* **Escáner OCR Integrado (`Tesseract.js`)**: Olvídate de introducir tus atributos manualmente. Sube, arrastra o pega (`Ctrl + V`) una captura de pantalla de tus estadísticas del juego y el sistema reconocerá y rellenará automáticamente los datos en la calculadora.
* **Diagnóstico Inteligente en Tiempo Real**: Evalúa tus atributos clave contra las metas actuales del juego para el Rango S:
  * **Ataque (ATQ)** y **Precisión (%)**
  * **Índice de Golpe Crítico (%)** y **Daño Crítico (%)**
  * **Penetración de Defensa (%)** y **Aumento de Daño (%)**
* **Consejos de Optimización Automáticos**: Genera tarjetas de diagnóstico dinámicas que te indican exactamente en qué estadísticas debes enfocar tus recursos y cómo mejorar tus artefactos.
* **Guías del Meta Actual**:
  * **Recomendación de Artefactos**: Detalle completo del set *Veneno Azul del Arquitecto* (4 y 8 piezas) y sincronización de clase para Sung Jinwoo.
  * **Desglose por Slot**: Qué estadísticas buscar en cada pieza del Set Izquierdo (Reliquias) y Set Derecho (Accesorios).
  * **Recomendación de Núcleos (Cores)**: Guía completa con las estadísticas principales para **Orbe (ATQ %)**, **Cubo (DEF %)** y **Rombo (PS %)**, junto con la lista de subestadísticas prioritarias para equilibrar tu personaje.
* **Diseño Ultra Ligero y Sin Dependencias Complejas**: Todo desarrollado en un único archivo de alto rendimiento utilizando HTML5, Vanilla CSS3 y JavaScript puro.

---

## Tecnologías Utilizadas

* **HTML5 Semántico**: Estructura accesible, clara y optimizada para SEO.
* **Vanilla CSS3**: Sistema de diseño basado en variables CSS (Tokens), efectos de *glassmorphism*, bordes luminosos y animaciones fluidas sin frameworks externos.
* **Vanilla JavaScript (ES6+)**: Lógica de cálculo, diagnóstico en tiempo real y gestión de eventos sin librerías pesadas.
* **Tesseract.js (v5)**: Procesamiento de imágenes y reconocimiento óptico de caracteres (OCR) 100% del lado del cliente en el navegador.

---

## Estructura del Proyecto

```text
SRANKCalculator/
│
├── index.html       # Aplicación principal (HTML, CSS y lógica JS en un solo archivo optimizado)
└── README.md        # Documentación y descripción del proyecto
```

---

## Notas de la Versión

* **v1.0**: Lanzamiento inicial con sistema OCR, calculadora en tiempo real, interfaz dark mode mejorada, paleta de colores de alta legibilidad y guías completas de artefactos y núcleos.

---

*Desarrollado como herramienta de análisis no oficial para la comunidad de Solo Leveling: Arise.*
