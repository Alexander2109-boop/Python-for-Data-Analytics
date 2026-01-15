# 🐍 Project Ridefare - Python for Data Analytics

## 📝 Descripción
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) exhaustivo sobre un dataset de más de 690,000 registros del sector de viajes compartidos (*ride-sharing*). El objetivo principal es identificar los factores críticos que influyen en la variabilidad de precios y la demanda, integrando datos transaccionales con variables climáticas.

---

## 🚀 Puntos Clave del Proyecto
Basado en el análisis técnico realizado con Python, se ejecutaron las siguientes fases:

* **Procesamiento de Big Data:** Limpieza y normalización de un dataset consolidado de 693,071 entradas, incluyendo la gestión de 55,905 valores nulos en la columna de precios.
* **Análisis de Outliers:** Identificación y tratamiento de valores atípicos en distancia y precio, determinando que los picos de demanda (*surge multiplier*) son los principales impulsores de la rentabilidad.
* **Ingeniería de Características:** Conversión y normalización de *timestamps* a formato datetime para correlacionar eventos climáticos por hora y ubicación.
* **Insights de Negocio:** Descubrimiento de que la escasez de vehículos y la hora pico impactan más en el precio que las condiciones ambientales directas.

---

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python.
* **Librerías:** Pandas (Manipulación de datos), NumPy (Cálculo numérico), Matplotlib/Seaborn (Visualización estadística).
* **Entorno:** Jupyter Notebooks para análisis reproducible.

---

## 📈 Estrategias Propuestas
* **Gestión de Flota:** Creación de incentivos dinámicos para conductores durante horas pico (7-9 a.m. y 4-7 p.m.) para estabilizar la oferta.
* **Optimización de Precios:** Diseño de estrategias centradas en la eficiencia de viajes cortos para maximizar la rentabilidad por kilómetro.
* **Modelado Predictivo:** Preparación del dataset para futuros modelos de Machine Learning mediante la eliminación de sesgos por valores extremos.
