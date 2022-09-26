# W7-Kaggle-Predict


## Objetivo del proyecto:
El proyecto de la semana 7 del Bootcamp de Data Analyst trata de una competición sobre 
los modelos de Machine Learning.
Competiremos entre los miembros del bootcamp buscando el modelo que mejor se generalice 
y prediga unos salarios dado un dataset:

    - Familirianizarnos con los modelos de ML
    - Transformar los datos y limpiarlos según sea necesario.
    - Predecir la columna "salaries_in_usd" para la muestra facilitada


### Requesitos:
    - El fichero con los resultados de las predicciones deberá respetar el orden que
    sigue el fichero de test.csv. 
    - El fichero también deberá mantener el mismo nº de filas.


## Dirección tomada:

Para ello, he tomado los siguientes pasos:

    - Primero exploramos la data que nos han facilitado. Signifcado de columnas, valores únicos, outliers... 
    - Una vez comprendido el significado de cada columna, enriqueceremos el dataframe con la 
    media de salarios por pais. 
    - Normalizaremos los datos y eliminaremos las columnas que guarden menor correlación con nuestra
    columna a predecir.
    - Entrenaremos varios modelos para decantarnos sobre el que menor RMSE y menor overfit tenga.
    

#### Resultados

-Tras realizar varios intentos, el mejor resultado que hemos obtenido es con un RMSE de ~58.000$:

<img width="700" alt="1" src="https://user-images.githubusercontent.com/107916116/192308470-01eed3b6-4425-434e-a596-738c14241750.png">

Ref: https://www.kaggle.com/competitions/bt-ironhack-agosto-2022-ml-competition/overview
