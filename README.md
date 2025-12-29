# 🏝️ Tenerife Municipalities Data Scraper

Un proyecto de automatización y extracción de datos centrado en la isla de Tenerife. Este proyecto surge de la necesidad de disponer de una lista estructurada y limpia de los municipios y entidades de la isla, información que a menudo se encuentra dispersa o en formatos no procesables (tablas web, PDFs, etc.).

🚀 **[DESCARGAR DATASET (CSV)](https://github.com/Zunraz/pueblos-de-tenerife/blob/main/pueblos_tenerife.csv)**

## 📊 El Dataset
El resultado principal es un archivo `pueblos_tenerife.csv` que contiene la información recolectada de forma sistemática. Este formato permite su importación directa en herramientas de análisis como Excel, Google Sheets, Power BI o librerías de programación como Pandas.

### Datos incluidos en el CSV:
- **Nombre del Municipio:** Nombre oficial procesado.
- **Población:** Datos demográficos obtenidos durante el scraping.
- **[Añade aquí otras columnas que tenga tu CSV, ej. Superficie, Altitud, etc.]**

## 🛠️ Proceso de Extracción (Web Scraping)
Para este proyecto se desarrolló un script que automatiza la navegación y extracción de datos:
- **Tecnología:** [JavaScript/Node.js o Python].
- **Lógica de Limpieza:** Se implementaron filtros para eliminar ruidos en el texto, normalizar nombres y asegurar que los datos numéricos sean interpretables por software de análisis.

## 🧠 Valor Técnico
Este repositorio demuestra habilidades en:
1. **Identificación de patrones:** Localización de datos en estructuras HTML inconsistentes.
2. **Transformación de datos (ETL):** El paso de "Web Raw Data" a un "Structured CSV".
3. **Productividad con IA:** El uso de herramientas de Inteligencia Artificial para acelerar la creación del scraper y la validación de los datos obtenidos.

## 📈 Aplicaciones Sugeridas
- **Desarrollo Web:** Base de datos para selectores de formularios o buscadores locales.
- **Data Science:** Análisis de distribución poblacional en las Islas Canarias.
- **GIS:** Integración con herramientas de mapas para visualización geográfica.

---
**Nota:** Los datos se han obtenido respetando las políticas de acceso de las webs de origen y se ofrecen con fines educativos y de portfolio.
