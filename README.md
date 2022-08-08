# AS
Repositorio de la materia Aprendizaje Supervisado
# Intro_AA

Repositorio de respuestas de la materia: Introducción al Aprendizaje Supervisado (2022), en el marco de la Diplomatura en Ciencia de Datos - Universidad Nacional de Córdoba.

# **DIPLOMATURA 2022**

# Introducción al Aprendizaje Automático

## GRUPO Nº24

## INTEGRANTES:
   - [x] Nico Rosales 
   - [x] Daniel Rubio
   - [x] Diana Fonnegra
   - [x] Clarisa Manzone

----   
En este repositorio se encuentran las entregas con resultados correspondientes a la asignatura de _Aprendizaje Supervisado_.

## **Requerimientos - Librerías necesarias**:
   - [x] matplotlib.pyplot
   - [x] pandas
   - [x] seaborn
   - [x] numpy
   - [x] sklearn
   - [x] random
   - [x] missingno
   - [x] scipy
   - [x] XGBoost

# Documentación:
## Laboratorio 1: Regresión en Boston

   - [x] En este laboratorio se desarrollaron modelos de clasificación en base al set de datos entregado para su estudio.
   - [x] Se trata de un dataset derivado de la competencia Spaceship Titanic de Kaggle. Los datos fueron tomados originalmente de la competencia y se generaron los datasets de entrenamiento y evaluación.
   - [x] En la etapa 1 se realiza en proceso de EDA.
   - [x] En la etapa 2 se completa la fase EDA y se procede al curado del dataset.
   - [x] En la etapa 3 se eevaluan diferentes tipos de clasificadores. Se evalua la precisión de cada clasificador seleccionando Random Forest para su optimización de hiperparámetros.
   - [x] Se aplica búsqueda aleatoria con cross validation y sobre el set de hiperparámetros obtenidos en esta etapa inicial se ajusta con mayor detalle aplicando un GridSearch
   - [x] Se obtiene un modelo optimo que predice con 0.8+ de precisión según evaluación en la competencia de Kaggle.
   - [x] En la etapa 4 se aborda el problema de clasificación mediante una red neuronal.
   - [x] Se optimiza la misma ajustando el layerDropout forma manual e iterativa, se prueban distintas capas densas logranse el modelo final. (0.80804 de precisión Kaggle).
   - [x] En la etapa 5 Se repite el mismo esquema de trabajo aplicado para RandomForest (etapa 3) utilizando XGBoost como clasifificador y la librería Hyperopt como optimizador de hiperparámetros.
