# Data Project README file

### :raising_hand: **Nombre** 
<<<<<<< HEAD
Mis primeros spaguettis

### :baby: **Estado**
Ironhack Data Analytics Primer Proyecto Beta

### :running: **Utilidad**
Este proyecto consiste en obtener como resultado el bicimad o bicipark más cercano en función de los centros culturales de Madrid. Aparte de esta información también se añade la disponibilidad de las bicis actuales que hay en la estación cercana y un enlace directo a google maps para que el usuario pueda dirigirse a la estación.

### :computer: **Herramientas**
Python, visual studio, jupyter.


### :wrench: **Configuración**
Librerias que debes tener para que este programa funcione.
- import pandas as pd
- import requests
- import bs4
- from shapely.geometry import Point
- import geopandas as gpd
- import argparse
- from fuzzywuzzy import fuzz
- from fuzzywuzzy import process
- import os
- from dotenv import load_dotenv
- import argparse
- import papermill

### :see_no_evil: **Uso**
Al ejecutar el programa en una terminal se solicitarán dos o tres inputs().

- Primera opción(dos inputs): "Todos" + "bicimad o bicipark" esto generará un dataframe completo con centros culturales y bicimads o biciparks. 
Esto generara un dataframe completo con centros culturales y bicimads o biciparks
- Segunda opción(tres inputs): "Centro cultural" + "bicimad o bicipark" + "Si o No" esto ultimo nos dara un enlace a google maps si lo deseamos.
Esta opción generará un data frame de una única fila con el centro cultural seleccionado y el transporte elegido. Además, tendrás la opción de obtener un enlace a Google Maps.

Problema: tiempo de ejecución demasiado largo.

### :file_folder: **Estructura de carpetas**
```
└── ih_datamadpt0923_project_m1
=======
ML Diamonds Price
### :baby: **Estado**
Ironhack Data Analytics Tercer Proyecto Beta

### :running: **Utilidad**
En este proyecto empleamos ML para predecir el precio del diamante en función de diferentes features.
### :computer: **Herramientas**
Python, visual studio, jupyter, Dbeaver(SQL), Terminal


### :wrench: **Configuración**
Librerias que debes tener para que este programa funcione. (Se recomienda tener un entorno único con estas librerias).
lazypredict
sklearn
pandas
seaborn
numpy
matplotlib
Se ejecuta através de jupyter notebook en el archivo solución_final.
Usamos el archivo diamond_test.csv para probar nuestro entrenamiento de datos.


### :see_no_evil: **Pasos**
Abrimos el documento diamonds_train.db en dbeaver y hacemos un join de todas las tablas que tenemos para ver que podemos usar. Generamos un CSV y lo cargamos en jupyter notebook.

Exploramos nuestros datos y eliminamos lo que no necesitemos. En mi caso he usado la matriz de correlación con seaborn para ver que columnas no nos estaban aportando valor.

Una vez que tenemos los datos limpios he usado lazy predict para ver que modelos nos dan mejores métricas.
- Modelo usado finalmente: XGBRegressor
- Modelos Testeados: 
            LGBMRegressor (Mejor scoring en lazy predict pero a la hora de entrenar se quedaba detrás)
            LinearRegression, 
            RandomForestRegressor,
            HistGradientBoostingRegressor   
            GradientBoostingRegressor   
            XGBRegressor   
            RandomForestRegressor   
            ExtraTreesRegressor   
            MLPRegressor   
            BaggingRegressor   
            KNeighborsRegressorOrthogonalMatchingPursuitCV
            LassoLars
            Lasso 
Comparamos nuestros datos test frente a los datos entrenados y realizamos un predict.

Guardamos el csv, abrimos visual estudio y probamos a subirlo a kaggle 🤞


### :books: **Learnings**
Features que he metido para mejorar el training
Librerias que he probado nuevas
### :x: **Error Principal**
Quedarse dormido. Con todos estos test y diferentes modelos he podido comprender el funcionamiento basico del machine learning
y los diferentes pasos que se deben ir siguiendo. El orden es un factor importante en este proyecto.

### :file_folder: **Estructura de carpetas**
```
└── ih_datamadpt0923_project_m3
>>>>>>> 0dcc12a3b6d6f79b035635e846ee6a07c1941d14
    ├── .ipynb_checkpoints
    ├── _wip_
    └── data
    │   ├── final_filas_libm_live.csv
    │   └── final_filas_libp_live.csv
    ├── modules
    │   ├── funciones.py
    │   └── geocalculations.py     
    ├── notebooks
    │   └── importing_exporting_dfs.ipynb
    ├── LICENSE
    ├── .env
    ├── README.md
    └── main.py
```


### :shit: **ToDo**
<<<<<<< HEAD
Mejora del tiempo de ejecución.
=======
- Mejorar el guardado a CSV para evitar tener que abrir VS y modificar manualmente.
- Reestructurar el código para evitar tener que ordenar las columnas nuevamente.
- Matriz de correlación intentar llevar antes de realizar el drop para que no sea tan complicado usarlo.
- Limpiar imports
- Limpiar features
>>>>>>> 0dcc12a3b6d6f79b035635e846ee6a07c1941d14

### :love_letter: **Contact info**
John Bryan xxxxxxxx@gmail.com

---
