# 📊 transactional-demand-models

Este repositorio contiene el código y la documentación relacionados con el artículo:

> **Construcción de modelos predictivos en el sector ferretero a partir de datos transaccionales: efectos de la pandemia**  
> Isaias Cáceres, Maximiliano Amarilla, Luis Richer  
> Universidad Paraguayo Alemana, SRH University

---

## 📦 Descripción
El proyecto desarrolla y compara modelos de predicción de demanda utilizando datos históricos transaccionales de una empresa distribuidora del sector ferretero.  
Se analizaron distintos enfoques de regresión (lineal, polinómica de segundo grado y K-Nearest Neighbors) y se evaluó el impacto de incluir/excluir el periodo pandémico y de filtrar valores atípicos mediante el rango intercuartílico (IQR).

---

## 🔒 Acceso a los datos
Por razones de confidencialidad, **los datos utilizados no se publican** en este repositorio.  
Investigadores o revisores interesados pueden solicitar acceso, sujeto a la autorización de la empresa.

📩 **Contacto:**  
Isaias Cáceres – ignacio.caceres@upa.edu.py

---

## 📂 Estructura del repositorio
- `Sales_Forecasting.ipynb`: Notebook principal con el análisis y los modelos.
- `Dataset/`: Carpeta para ubicar los archivos de datos.  
- `Graficos/`: Carpeta para guardar resultados gráficos.
- `README.md`: Este archivo.
- `.gitignore`, `LICENSE`: Archivos de configuración y licencia.

---

## ⚙️ Reproducibilidad
Para reproducir los experimentos:
1. Solicitar los datos y colocarlos en la carpeta `Dataset/` siguiendo las instrucciones en su README.
2. Ejecutar el notebook `Sales_Forecasting.ipynb`.

---
## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT.
