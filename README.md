# Transactional Demand Models

Repositorio oficial para el código y documentación del artículo de investigación:

**Título:** Construcción de modelos predictivos en el sector ferretero a partir de datos transaccionales: efectos de la pandemia.
**Autores:** Isaias Cáceres, Maximiliano Amarilla, Luis Richer.
**Afiliación:** Universidad Paraguayo Alemana, SRH University.

## Resumen del Proyecto

Este proyecto desarrolla y evalúa modelos de predicción de demanda utilizando datos históricos transaccionales de una empresa distribuidora del sector ferretero. El estudio se centra en la comparación de distintos enfoques de regresión para optimizar la planificación de inventario.

El análisis abarca:
- **Modelos:** Regresión Lineal, Polinómica (2º grado) y K-Nearest Neighbors (KNN).
- **Variables:** Evaluación del impacto de la inclusión/exclusión del periodo pandémico.
- **Preprocesamiento:** Filtrado de valores atípicos mediante Rango Intercuartílico (IQR).

## Tecnologías Utilizadas

El proyecto fue desarrollado utilizando Python 3.x y las siguientes librerías principales:

- **Procesamiento de datos:** Pandas, NumPy.
- **Modelado y Machine Learning:** Scikit-learn.
- **Visualización:** Matplotlib, Seaborn.
- **Entorno:** Jupyter Notebook.

## Estructura del Repositorio

```text
├── Dataset/               # Directorio para archivos de datos (ver nota de confidencialidad)
├── Graficos/              # Resultados visuales generados por los modelos
├── Sales_Forecasting.ipynb # Notebook principal con pipeline de ETL y modelado
├── .gitignore             # Archivos ignorados por git
├── LICENSE                # Licencia MIT
└── README.md              # Documentación del proyecto
