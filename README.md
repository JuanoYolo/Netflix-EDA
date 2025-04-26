# Netflix Data Analysis 🎬📈

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un dataset de títulos de Netflix, incluyendo películas y series.

## 📚 Objetivos del proyecto

- **¿En qué años Netflix produjo más contenido?**
- **¿Se enfocaron más en películas o en series?**
- **¿Cuál es la duración típica de películas en Netflix?**

## 🛠️ Metodología aplicada

- **Limpieza de datos:** 
  - Conversión de columnas como `duration` de texto a números.
  - Manejo de valores nulos en campos importantes.
- **Transformaciones:**
  - Filtrado de películas y series.
  - Agrupación por años, tipos de contenido, y duración.
- **Visualización:**
  - Gráficos de línea para evolución de contenido.
  - Gráficos de barras para distribución de tipo (`Movie` vs `TV Show`).
- **Análisis:**
  - Cálculo de moda y media de duración de películas.
  - Cálculo de porcentajes de distribución de contenido.

## 📊 Resultados principales

- Netflix produjo más contenido en **2018**, alcanzando un pico de **1147 títulos** agregados.
- Aproximadamente **69% del contenido** disponible son **películas**, y **30%** son **series**.
- La duración **típica** de las películas en Netflix es de **90 minutos**, mientras que el promedio general es de **99.5 minutos**.

## 📁 Archivos incluidos

- `netflix_analysis.ipynb` — Notebook con todo el análisis, limpieza, visualización y conclusiones.
- `netflix_titles.csv` — Dataset original de Netflix usado para el análisis.

## 🚀 Cómo usar este proyecto

1. Clonar o descargar este repositorio.
2. Asegurarte de tener Python 3, pandas, matplotlib y seaborn instalados.
3. Abrir el notebook `netflix_analysis.ipynb`.
4. Ejecutar todas las celdas para replicar el análisis.

---
