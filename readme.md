---

## 🎯 Objetivo del Análisis

Este proyecto se enfoca en abordar la **elevada tasa de cancelación de servicios** que enfrenta **Telecom X**, una empresa ficticia del sector de las telecomunicaciones de la empresa Telecom X. 

---

## 📂 Estructura del Repositorio

* `README.md`: El archivo que estás leyendo, con una descripción general del proyecto.
* `Telecom_X_Gabriel.ipynb`: El archivo principal del proyecto, que contiene todo el código Python, el análisis detallado, las visualizaciones generadas y el informe final.
* `TelecomX_Diccionario.md`: El conjunto conceptos necesarios.

---

## 🛠️ Herramientas y Librerías Utilizadas

El análisis se llevó a cabo íntegramente en el entorno de Python, empleando las siguientes librerías principales:

* **`pandas`**: Esencial para la manipulación y el procesamiento de los datos.
* **`numpy`**: Utilizada para operaciones numéricas eficientes.
* **`matplotlib`**: Para la creación de gráficos estáticos y visualizaciones.
* **`seaborn`**: Empleada para generar visualizaciones estadísticas más atractivas y complejas.

---

## 🚀 Pasos del Análisis

El proyecto se desarrolló siguiendo estas fases clave:

1.  **Recopilación y Carga de Datos:** Importación del conjunto de datos inicial (en formato JSON) a un entorno de trabajo en Python.
2.  **Limpieza y Preprocesamiento de Datos:**
    * Normalización de la estructura JSON de los datos.
    * Gestión de valores nulos o vacíos para asegurar la calidad del dataset.
    * Conversión de tipos de datos a los formatos adecuados para el análisis.
    * Transformación de valores categóricos (ej., 'Yes'/'No' a 1/0 para facilitar el análisis numérico).
    * Unión de DataFrames para consolidar toda la información en un único conjunto de datos.
3.  **Análisis Exploratorio de Datos (EDA):**
    * Cálculo de la tasa general de rotación.
    * Análisis de la distribución de la rotación por variables categóricas, identificando patrones.
    * Análisis de la distribución de la rotación por variables numéricas, utilizando estadísticas descriptivas, histogramas y diagramas de caja para detectar tendencias y anomalías.
