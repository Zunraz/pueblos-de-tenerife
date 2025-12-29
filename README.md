# 🏝️ Tenerife Data Scraper & Dataset

Un proyecto de automatización y extracción de datos enfocado en la isla de Tenerife. Este script permite transformar información no estructurada de la web en una base de datos limpia y lista para usar en aplicaciones web, análisis estadísticos o visualización de datos geográficos.

🚀 **[VER DATASET (JSON)](https://github.com/Zunraz/pueblos-de-tenerife/blob/main/pueblos_tenerife.csv)**

## 📊 El Proyecto
El objetivo principal fue recopilar información detallada de los municipios y pueblos de Tenerife, incluyendo datos que no están disponibles de forma consolidada en una API pública.

### Datos extraídos:
- Nombre del municipio/pueblo.
- Población (datos actualizados).
- Superficie geográfica.
- Enlaces a fuentes oficiales.
- [Añade aquí cualquier otro dato que hayas extraído].

## 🛠️ Stack Tecnológico
- **Python / JavaScript:** (Elige el lenguaje que usaste) para la lógica de extracción.
- **BeautifulSoup / Puppeteer:** (Elige la librería usada) para el parseo del DOM.
- **JSON/CSV:** Formatos de salida para la persistencia de datos.

## 🧠 Desafíos de Extracción
- **Navegación por el DOM:** Identificación de patrones en tablas HTML complejas y selectores CSS variables.
- **Limpieza de Datos (Data Cleaning):** Procesamiento de strings para eliminar caracteres especiales, espacios innecesarios y normalizar los formatos numéricos.
- **Eficiencia:** Implementación de tiempos de espera para respetar el `robots.txt` del sitio fuente y evitar sobrecargas.

## 📁 Estructura de Archivos
- `scraper/`: Código fuente del script de extracción.
- `data/`: Contiene el dataset final en formato `.json` y `.csv`.
- `examples/`: Pequeños snippets de cómo importar estos datos en un proyecto JS/Python.

## 📈 Casos de Uso
Este dataset puede ser utilizado para:
1. Crear mapas interactivos de la isla con **Leaflet** o **Google Maps API**.
2. Desarrollar aplicaciones de turismo o buscadores de servicios locales.
3. Análisis demográficos de la evolución de la población en las islas.

---
**Nota Legal:** Este proyecto se ha realizado con fines puramente educativos y de investigación, cumpliendo con las buenas prácticas de web scraping.
