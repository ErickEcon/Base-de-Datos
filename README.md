# 📊 Recursos y Herramientas para Economistas

![Estado](https://img.shields.io/badge/Estado-Activo-success) ![Tech](https://img.shields.io/badge/HTML5-CSS3-blue) ![Focus](https://img.shields.io/badge/Focus-Economics%20%26%20Data-orange)

Una colección curada y centralizada de recursos digitales esenciales para investigación económica, análisis de datos y finanzas. Este repositorio aloja una interfaz web rápida y accesible para navegar por bases de datos oficiales, herramientas de programación (Python/R) y literatura académica.

🔗 **[Ver la página en vivo aquí](https://erickecon.github.io/Base-de-Datos/)**


## 🚀 Características

* **Búsqueda Instantánea:** Filtra recursos por nombre, categoría o palabras clave (ej. "Inflación", "Python", "BCRP") en tiempo real.
* **Diseño Responsivo:** Optimizado para visualización en computadoras de escritorio y dispositivos móviles.
* **Modo Oscuro:** Interfaz adaptable con soporte para *Dark Mode* para sesiones de investigación nocturnas.
* **Categorización Lógica:** Separación clara entre datos nacionales (Perú), globales, herramientas de código y *papers* académicos.

## 🗂️ Contenido del Repositorio

La lista de recursos ha sido seleccionada pensando en la carrera de economía y trabajos de investigación, abarcando:

### 🇵🇪 Datos Perú
Fuentes oficiales y microdatos nacionales:
* **BCRP:** Estadísticas monetarias y series históricas.
* **INEI:** Microdatos, ENAHO y censos.
* **Reguladores:** SBS, SMV y ministerios.

### 🌍 Bases de Datos Globales
Los principales repositorios de data macroeconómica:
* **FRED (St. Louis Fed) & BEA**.
* **Banco Mundial & FMI**.
* **Penn World Table (PWT):** Para comparaciones de productividad internacional.

### 💻 Econometría y Ciencia de Datos
Herramientas para el economista moderno:
* **Python for Finance:** Librerías y *cookbooks*.
* **Forecasting:** Recursos de Rob Hyndman y series de tiempo.
* **Econometría:** Guías de QuantEcon y repositorios de GitHub.

### 📚 Investigación y Finanzas
* **Papers:** NBER, RePEc, SSRN.
* **Finanzas:** Datos de mercado, factores de Fama-French y volatilidad.

## 🛠️ Cómo agregar nuevos enlaces

Este proyecto es un sitio estático simple (`index.html`). Para agregar un nuevo recurso:

1.  Abre el archivo `index.html` en un editor de texto o directamente en GitHub.
2.  Busca la categoría donde quieres añadir el enlace (ej. ``).
3.  Copia y pega el siguiente bloque de código dentro del `div` con clase `links-grid`:

```html
<div class="link-card">
    <a href="URL_DEL_RECURSO" target="_blank">NOMBRE DEL RECURSO</a>
    <p>Breve descripción de por qué es útil.</p>
    <span class="tag">ETIQUETA</span>
</div>
