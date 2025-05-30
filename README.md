# TABD_TraficoVehicular
Proyecto de clase para el tráfico vehicular 
# 🚦 Análisis de Tráfico Vehicular en Colombia

Este repositorio contiene el desarrollo del proyecto final del curso **Tópicos Avanzados de Bases de Datos**, el cual tiene como objetivo analizar grandes volúmenes de datos sobre el tráfico vehicular en Colombia mediante herramientas de análisis exploratorio, Google BigQuery y visualización con herramientas de BI.


---

## 🎯 Objetivo General

Analizar la evolución del tráfico vehicular y el estado de las vías en Colombia a lo largo del tiempo, utilizando tecnologías de procesamiento masivo de datos, con el fin de generar visualizaciones que apoyen la toma de decisiones en movilidad e infraestructura vial.

---

## ⚙️ Herramientas Utilizadas

- Google Colab
- Google BigQuery
- pandas
- ydata_profiling
- auth y to_gbq para autenticación y carga de datos
- json para consolidado de exportaciones
- Tableau para visualización de resultados

---

## 🔍 Análisis Realizados

- **Exploración de datos**: revisión de calidad, tipos y valores faltantes.
- **Carga a BigQuery**: mediante `pandas-gbq` y autenticación con Google Cloud.
- **Consultas SQL**:
  - Consolidado mensual y anual de tráfico por peaje
  - Ranking de peajes más transitados
  - Comparativo por categorías tarifarias
- **Exportaciones**:
  - JSON para visualización rápida
  - CSV para análisis externo
- **Visualizaciones en Tableau**:
  - Tráfico por año
  - Ranking top 10 peajes
  - Evolución por estado de vía y tipo de calzada

---

## 📊 Resultados Destacados

- Identificación de peajes con mayor flujo vehicular anual.
- Comparativo entre calzadas sencillas y dobles en relación con el volumen de tránsito.
- Análisis de evasores y exentos.
- Análisis histórico de tarifas y su impacto potencial en el tráfico.

---

## 📥 Datos Abiertos Utilizados

- [Tráfico vehicular ANI - Datos.gov.co](https://www.datos.gov.co/Transporte/Tr-fico-Vehicular-ANI/8yi9-t44c)
- [Estado de vías - INVÍAS]([https://www.datos.gov.co/Transporte/Estado-de-las-v-as-en-Colombia/xyz](https://inviasopendata-invias.opendata.arcgis.com/search?collection=Dataset)) 

---

## 🧑‍💻 Autores

Este trabajo fue realizado por estudiantes de la **Pontificia Universidad Javeriana** en el marco del curso *Tópicos Avanzados de Bases de Datos*:

- **Victoria Lasso**  

- **Germán Ospina**  

- **Josman Ramírez**  

---

## 📄 Licencia

Este repositorio ha sido creado con fines educativos y académicos.  
**Pontificia Universidad Javeriana - 2025**

