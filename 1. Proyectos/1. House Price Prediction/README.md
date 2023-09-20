# Proyecto: Modelos para la Estimacion de Precios de Vivienda  

![House-modified](https://github.com/EvelynOr/Python/assets/82233779/504439eb-fbab-49a9-a799-20f339d1652c)

Picture: realtor.com

![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)


### Descripcion del Proyecto
El proyecto desarrolla modelos de machine learning que permita predecir los precios de casas en función de diversas características inmobiliarias. 


### Objetivo del proyecto: 
Aplicar técnicas de análisis de datos y aprendizaje automático (machine learning) con Python


### Pregunta de investigacion
¿Cuál es el mejor modelo para predecir el precio de la vivienda en Boston?

### Nivel
Principiante

# Etapas del Proyecto

### Etapa 1. Recopilación de datos:
El conjunto de datos "Boston Housing" fue recopilada originalmente por el [U.S. Census Service](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html), relativa a la vivienda en la zona de Boston Massachusetts. Los datos fueron publicados originalmente por [Harrison, D. y Rubinfeld, D.L. en 'Hedonic prices and the demand for clean air', en J. Environ. Economics & Management, vol.5, 81-102, 1978](https://www.researchgate.net/profile/Daniel-Rubinfeld/publication/4974606_Hedonic_housing_prices_and_the_demand_for_clean_air/links/5c38ce85458515a4c71e3a64/Hedonic-housing-prices-and-the-demand-for-clean-air.pdf). El estudio original investiga los problemas metodológicos asociados al uso de datos del mercado de la vivienda para medir la disposición a pagar por un aire limpio.   

El conjunto de datos contiene información sobre el valor de la vivienda. Depende la fuente consultada, indican que los registros corresponden a fuentes como: 
+ a) 506 secciones censales del Área Estadística Metropolitana de Boston (SMSA). El SMSA incluye Boston y varias ciudades y pueblos vecinos, por lo que el conjunto de datos abarca una zona más amplia que la propia ciudad de Boston.
+ b) 506 vecindarios especificos dentro de la ciudad de Boston. No se tienen disponibles los nombres de los vecindarios para mantener la privacidad de las personas y propiedades involucradas. 

Esta definicion es importante al momento que se quieran ajustar los precios de la vivienda (MEDV) a la inflación.

El conjunto de datos ha sido utilizado en una variedad de estudios de investigación, como: estudios sobre la economía del mercado inmobiliario, la discriminación en la vivienda, el impacto de la política pública en los precios de la vivienda y comúnmente como conjunto de datos de prueba para los algoritmos de aprendizaje automático.

La data se obutvo del repositorio de [scikit-learn](https://github.com/scikit-learn/scikit-learn/blob/main/sklearn/datasets/data/boston_house_prices.csv) y registra datos de las características de viviendas, resumidas en 14 variables: el número de habitaciones, la tasa de criminalidad, el precios de las viviendas, la proporción de estudiantes y maestros, entre otros.


### Etapa 2. Análisis exploratorio de datos (EDA por sus siglas en inglés):
+ Limpieza y preprocesamiento de datos, para tratar posibles valores faltantes, eliminar duplicados y corregir errores. También transformar algunas características para adecuarlas para el modelado.
+ Se realizan visualizaciones y análisis descriptivos para comprender la distribución de las variables y las relaciones entre ellas.
+ Se exploran correlaciones entre las características y los precios de las viviendas utilizando gráficos de dispersión y matrices de correlación.
+ Se identificaron valores atípicos o patrones inusuales que requieran atención.


### Etapa 3: Selección del modelo

#### Primer Modelo: Gradient Boosting [Regressor](https://github.com/EvelynOr/Python/blob/main/1.%20Proyectos/1.%20House%20Price%20Prediction/Etapa%203_%20SeleccionModelo_BostonHousing%20.ipynb) 

1. Se sutilizó la biblioteca LazyPredict para identificar el modelo más adecuado para el conjunto de datos. 

2. Entrenamiento y Ajuste del Modelo. se dividió la data en tres conjuntos: de entrenamiento (train), validación y prueba (test) para entrenar, validar y probar el modelo.  

3. Evaluación del Modelo: se utilizaron las metricas: R-Squared, Adjusted R-Squared, Error cuadrático medio (MSR) y Raíz cuadrática media (RMSE).

4. Implementación y Despliegue: 

5. Resultados
- Variables que podrían explicar el nivel de precios
- Factor de ajuste de inflación a los precios, 14.06
- A priori se puede decir que los precios de las viviendas tienen un determinante cultural
  
## Análisis 

## Beneficios del Proyecto
+ Adquirir experiencia en el desarrollo de modelos de machine learning para aplicaciones del mundo real.
+ Trabajar con datos del mundo inmobiliario, para comprender mejor el sector y sus dinámicas.
+ Aplicar habilidades como analista de datos en un contexto real.
  

## Recursos

#### Disclaimer 

El proyecto se realizó como proceso de autoaprendizaje de Python y conceptos básicos de Maching Learning, a la fecha no ha sido revisado por expertos en el tema.
