# Proyecto Final — Pronóstico de Ventas con Series Temporales

## Introducción a la Ciencia de Datos

Proyecto final de la Especialización en Ciencia de Datos e Inteligencia Artificial de la Universidad de Medellín.

**Semestre:** 2026-II  
**Fecha de entrega:** 26 de septiembre de 2026

---

## Descripción del proyecto

Este proyecto realiza un análisis exploratorio y temporal de datos de ventas de una tienda minorista global.

El objetivo es comprender el comportamiento de las ventas, identificar tendencias, patrones temporales y variaciones en la demanda, para finalmente generar un pronóstico de ventas para los próximos 7 días.

El proyecto desarrolla un flujo reproducible de Ciencia de Datos que comprende:

**cargar → comprender → limpiar → transformar → explorar → visualizar → comunicar**

---

## Objetivos

### Objetivo general

Analizar el comportamiento histórico de las ventas y realizar un pronóstico de las ventas correspondientes a los siguientes 7 días a partir de la última fecha disponible en el conjunto de datos.

### Objetivos específicos

- Comprender la estructura y las características del conjunto de datos.
- Diagnosticar y tratar problemas de calidad de los datos.
- Realizar procesos de limpieza y transformación utilizando Pandas.
- Explorar relaciones entre variables numéricas y categóricas.
- Analizar tendencias, variabilidad y patrones temporales.
- Construir visualizaciones para comunicar los principales hallazgos.
- Aplicar técnicas de análisis de series temporales.
- Generar un pronóstico de ventas para los próximos 7 días.
- Comunicar los resultados mediante conclusiones sustentadas en los datos.

---

## Conjunto de datos

Para este proyecto se utiliza el **Superstore Sales Dataset**, que contiene información de ventas de una tienda minorista durante aproximadamente cuatro años.

### Fuente

El conjunto de datos fue obtenido de Kaggle:

**Sales Forecasting - Superstore Sales Dataset**

https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

### Archivo utilizado
`train.csv`

## 🔎 Procesamiento y análisis
El proyecto contempla las siguientes etapas:

### 1. Comprensión de los datos
- Carga del dataset.
- Inspección de la estructura.
- Identificación de tipos de datos.
- Análisis de las variables.

### 2. Limpieza y transformación
- Identificación de valores nulos.
- Detección de registros duplicados.
- Conversión de tipos de datos.
- Limpieza y transformación de variables.
- Preparación de la variable temporal.

### 3. Análisis exploratorio de datos (EDA)
- Análisis univariado.
- Análisis bivariado y multivariado.
- Estadística descriptiva.
- Análisis por categorías y regiones.
- Análisis de relaciones entre variables.

### 4. Análisis temporal
- Organización de los datos por fecha.
- Análisis de tendencias.
- Análisis de variabilidad.
- Comparación entre períodos.
- Análisis de patrones temporales.
- Pronóstico de ventas.

### 5. Visualización
Se utilizan herramientas de visualización para comunicar los principales resultados:

- Seaborn.
- Plotly.

### 6. Conclusiones
Los hallazgos y conclusiones se construyen a partir de la evidencia obtenida durante el análisis.

---

## 🛠️ Tecnologías utilizadas

- Python 3.13
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code
- Git
- Git LFS

---

## 🚀 Cómo ejecutar el proyecto

### 1. Clonar el repositorio

    git clone https://github.com/Saramm1237/Proyecto-Ciencia-de-Datos.git

### 2. Entrar al proyecto

    cd Proyecto-Ciencia-de-Datos

### 3. Crear el entorno virtual

En Windows:

    python -m venv .venv

### 4. Activar el entorno virtual

En PowerShell:

    .venv\Scripts\Activate.ps1

### 5. Instalar las dependencias

    pip install -r requirements.txt

### 6. Ejecutar el notebook

Abrir el archivo:

`Proyecto.ipynb`

Ejecutar las celdas en orden desde el inicio hasta el final.

El archivo de datos debe encontrarse en:

`data/train.csv`