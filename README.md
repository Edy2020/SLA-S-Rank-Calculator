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

## Cómo Usar la Calculadora

Tienes dos formas muy sencillas de evaluar a tu personaje:

### 1. Escaneo Automático con OCR (Recomendado)
1. **Captura tus Stats**: En *Solo Leveling: Arise*, ve a la pantalla de estadísticas de Sung Jinwoo (o tu personaje DPS) y toma una captura de pantalla (`Win + Shift + S` en Windows).
2. **Sube la Imagen**: Pega la captura directamente en la página presionando `Ctrl + V`, o arrástrala hacia el recuadro de escaneo.
3. **Análisis Instantáneo**: El sistema OCR leerá la foto en segundos y rellenará todas las casillas automáticamente.

### 2. Ingreso Manual
* Si lo prefieres, puedes hacer clic en cualquier casilla (Ataque, Precisión, Daño Crítico, etc.) y escribir o ajustar los valores manualmente con el teclado.

### 3. Interpreta tu Diagnóstico
* Revisa tus tarjetas de **Diagnóstico y Consejos de Optimización** para descubrir exactamente qué estadísticas están por debajo de la meta.
* Consulta la guía inferior de **Artefactos y Núcleos** para saber qué piezas y subestadísticas específicas debes buscar para alcanzar el **Rango S**.

---

## Estructura del Proyecto

```text
SRANKCalculator/
│
├── index.html       # Aplicación web completa (HTML, estilos CSS y lógica JS en un único archivo)
├── LICENSE          # Licencia CC BY-NC 4.0 (Libre uso no comercial con créditos)
└── README.md        # Documentación y descripción general del proyecto
```

---

## Licencia y Condiciones de Uso

Este proyecto está bajo la licencia **Creative Commons Atribución-NoComercial 4.0 (CC BY-NC 4.0)**.

* **Libre Uso y Modificación**: Puedes utilizar, copiar, adaptar y mejorar este código libremente para la comunidad.
* **Créditos Requeridos (Atribución)**: Es obligatorio otorgar los créditos correspondientes al creador original de **S Rank Calculator**, enlazando al repositorio y mencionando si se realizaron cambios.
* **Prohibida su Venta (No Comercial)**: Al ser una herramienta creada gratuitamente para la comunidad, **queda estrictamente prohibida su venta, comercialización o uso con fines de lucro**.

Consulta el archivo [LICENSE](LICENSE) para leer los términos legales completos.

---

*Proyecto creado para la comunidad de jugadores de Solo Leveling: Arise.*
