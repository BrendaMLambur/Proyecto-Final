# Proyecto-Final
# Analisis de Calidad del Aire en Estados Unidos (2000 - 2016)
Este proyecto presenta un análisis exploratorio y limpieza de datos sobre la contaminación del aire en Estados Unidos utilizando un dataset público que contiene mediciones diarias de contaminantes atmosféricos como NO2, O3, SO2 y CO, desde el año 2000 hasta 2016.

El análisis incluye:  
- Preparación y limpieza de datos.  
- Visualización de tendencias anuales y distribuciones mensuales.  
- Interpretación de hallazgos preliminares.

# Dataset

- **Nombre:** Calidad del Aire e Impactos en la Salud (U.S. Pollution Data)
- **Fuente:** [Kaggle - U.S. Pollution Data](https://www.kaggle.com/datasets/sogun3/uspollution)
- **Tamaño:** 50,000 registros
- **Formato:** CSV

# Objetivos del Análisis

- Identificar ciudades con mayores niveles de PM2.5 y PM10.
- Observar la variación de la contaminación por mes y estación del año.
- Evaluar si existe una relación entre los niveles de contaminación y el número de hospitalizaciones.
- El informe final se encuentra disponible en formato HTML y está desarrollado en RMarkdown.


# Estructura del repositorio

- `analisis_calidad_aire.Rmd`: Código fuente del análisis en RMarkdown.  
- `analisis_calidad_aire.html`: Informe generado en formato HTML con resultados, gráficos y explicaciones.  
- `pollution_us_2000_2016.csv`: Dataset original utilizado para el análisis (debes descargarlo y añadirlo o proporcionar la fuente).  
- `README.md`: Este archivo.

# Requisitos para Reproducir el Análisis

1. Tener instalado R (recomendado R 4.1 o superior) y RStudio.
2. Instalar las siguientes librerías si no las tienes:
   ```r
   install.packages(c("tidyverse", "lubridate", "ggplot2", "knitr"))
