# 📊 Recursos y Herramientas para Economistas

![Estado](https://img.shields.io/badge/Estado-Activo-success) ![Tech](https://img.shields.io/badge/HTML5-CSS3-blue) ![Focus](https://img.shields.io/badge/Focus-Economics%20%26%20Data-orange)

Una colección curada y centralizada de recursos digitales esenciales para investigación económica, análisis de datos y finanzas. Este repositorio aloja una interfaz web rápida y accesible para navegar por bases de datos oficiales, herramientas de programación (Python/R) y literatura académica.

🔗 **[Ver la página en vivo aquí](https://tu-usuario.github.io/nombre-de-tu-repositorio/)**
*(Nota: Reemplaza este enlace una vez actives GitHub Pages)*

## 🚀 Características

* **Búsqueda Instantánea:** Filtra recursos por nombre, categoría o palabras clave (ej. "Inflación", "Python", "BCRP") en tiempo real.
* **Diseño Responsivo:** Optimizado para visualización en computadoras de escritorio y dispositivos móviles.
* **Modo Oscuro:** Interfaz adaptable con soporte para *Dark Mode* para sesiones de investigación nocturnas.
* **Categorización Lógica:** Separación clara entre datos nacionales (Perú), globales, herramientas de código y *papers* académicos.

## 🗂️ Contenido del Repositorio

[cite_start]La lista de recursos ha sido seleccionada pensando en la carrera de economía y trabajos de investigación[cite: 1, 78], abarcando:

### 🇵🇪 Datos Perú
Fuentes oficiales y microdatos nacionales:
* [cite_start]**BCRP:** Estadísticas monetarias y series históricas[cite: 18, 19].
* [cite_start]**INEI:** Microdatos, ENAHO y censos[cite: 111, 113].
* [cite_start]**Reguladores:** SBS, SMV y ministerios[cite: 18, 55].

### 🌍 Bases de Datos Globales
Los principales repositorios de data macroeconómica:
* [cite_start]**FRED (St. Louis Fed) & BEA**[cite: 7, 12].
* [cite_start]**Banco Mundial & FMI**[cite: 17, 123].
* [cite_start]**Penn World Table (PWT):** Para comparaciones de productividad internacional[cite: 13].

### 💻 Econometría y Ciencia de Datos
Herramientas para el economista moderno:
* [cite_start]**Python for Finance:** Librerías y *cookbooks*[cite: 35, 52].
* [cite_start]**Forecasting:** Recursos de Rob Hyndman y series de tiempo[cite: 51].
* [cite_start]**Econometría:** Guías de QuantEcon y repositorios de GitHub[cite: 26, 29].

### 📚 Investigación y Finanzas
* [cite_start]**Papers:** NBER, RePEc, SSRN[cite: 24, 38].
* [cite_start]**Finanzas:** Datos de mercado, factores de Fama-French y volatilidad[cite: 56, 67].

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
