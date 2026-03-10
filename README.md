Análisis de Factores del Desempeño Académico en las Pruebas Saber 11 (ICFES)
Descripción del proyecto

Este proyecto analiza los factores socioeconómicos, demográficos e institucionales que influyen en el desempeño académico de los estudiantes colombianos en las pruebas Saber 11, utilizando datos abiertos del ICFES.

El objetivo es identificar patrones y relaciones entre variables como el estrato socioeconómico, la educación de los padres, los hábitos de estudio y las características institucionales de los colegios, con el fin de comprender mejor las brechas educativas en Colombia.

Para lograrlo, se implementó un pipeline de datos completo, que incluye extracción desde una API pública, procesamiento y limpieza de datos, almacenamiento en la nube y visualización mediante dashboards interactivos.

🏗 Arquitectura del proyecto

El flujo de datos implementado fue el siguiente:# Proyecto_ICFES
API Datos Abiertos (ICFES)
        │
        ▼
Extracción y limpieza de datos con Python
        │
        ▼
Carga de datos en BigQuery (Data Warehouse)
        │
        ▼
Conexión y modelado en Power BI
        │
        ▼
Dashboard interactivo para análisis de datos
Este enfoque permite manejar grandes volúmenes de datos y facilitar el análisis exploratorio y la visualización de información relevante.

⚙️ Tecnologías utilizadas

Python

requests

pandas

API Datos Abiertos de Colombia

Google BigQuery (Data Warehouse)

Power BI (Visualización de datos)

SQL para consultas analíticas
