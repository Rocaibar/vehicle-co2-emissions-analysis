# 🚗 Análisis de Emisiones de CO<sub>2</sub> en Vehículos

Proyecto de Análisis Exploratorio de Datos (EDA) y Machine Learning enfocado en identificar los factores determinantes de las emisiones de dióxido de carbono en vehículos livianos.

## 📋 Descripción del Proyecto
Este proyecto procesa un conjunto de datos estandarizado de la industria automotriz para evaluar cómo influyen las especificaciones técnicas del motor (como cilindrada, tamaño y tipo de combustible) en el nivel de emisiones contaminantes.

## ⚙️ Flujo de Trabajo y Pasos Realizados
1. **Auditoría e Inspección Inicial:** Carga y revisión estructural del dataset (7,385 registros y 12 columnas), confirmando la ausencia de valores nulos.
2. **Limpieza de Datos:** Identificación y depuración de **1,103 registros duplicados exactos**, optimizando el set de datos a 6,282 observaciones limpias.
3. **Análisis Exploratorio (EDA):** Detección de valores atípicos (*outliers*) mediante diagramas de caja (*boxplots*) y análisis de correlaciones lineales.
4. **Modelado Predictivo:** Implementación de un modelo de Regresión Lineal para estimar las emisiones de CO<sub>2</sub> a partir de las variables técnicas.

## 🛠️ Tecnologías Utilizadas
* **Python** (Entorno Google Colab)
* **Pandas & NumPy** (Manipulación y limpieza de datos)
* **Matplotlib & Seaborn** (Visualización de datos y boxplots)
* **Scikit-Learn** (Modelado predictivo)

## 📁 Archivos del Repositorio
* `CO2_Emissions_EDA_Model.ipynb`: Jupyter Notebook con todo el código paso a paso.
* `CO2 Emissions.csv`: Dataset original analizado.

* ## 👤 Autoría
**Rocío Castro**  
*Ingeniera Química & Data Analyst*  
📍 Bahía Blanca, Argentina  
[LinkedIn](www.linkedin.com/in/rocío-castro-a8254930) | [GitHub](https://github.com/Rocaibar)
