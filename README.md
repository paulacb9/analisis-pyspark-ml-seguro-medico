# Práctica PySpark ML - Dataset de Seguros (Azure Databricks)

## Descripción
Este proyecto corresponde a una práctica de Machine Learning utilizando PySpark ejecutado en Azure Databricks.

Se realiza:
- Análisis Exploratorio de Datos (EDA) con la API de pandas en PySpark
- Preprocesamiento de datos
- Entrenamiento de un modelo de regresión lineal

## Dataset
Dataset utilizado:
https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv

Variables:
- age: edad del beneficiario
- sex: género
- bmi: índice de masa corporal
- children: número de hijos/dependientes
- smoker: fumador o no
- region: región en EE.UU.
- charges: costes médicos (variable objetivo)

## Tecnologías utilizadas
- Azure Databricks
- PySpark
- pandas API on Spark
- pyspark.ml

## Proceso
1. EDA con `pyspark.pandas`
2. Conversión a DataFrame de Spark
3. Transformaciones:
   - StringIndexer
   - OneHotEncoder
   - VectorAssembler
   - StandardScaler
4. Modelo:
   - Regresión Lineal
5. Evaluación:
   - RMSE
   - MAE
   - R²

## Estructura del proyecto
- `pyspark_ml_insurance.ipynb`: notebook principal exportado desde Azure Databricks

## Nota
El notebook fue desarrollado en Azure Databricks.

##  Autor
Paula C. Blanch
