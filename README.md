# Curso_Python

__Curso semipresencial de Big Data incluido en el programa "Hackea tu Futuro" organizado por la escuela de negocios The Valley Digital Business School (Granada, 2023)__

__Contenidos de los archivos de Python realizados en Google Colab__

__En el archivo M4 - 01 (02/10/23):__
  - Tipo de datos (enteros, flotantes, texto, booleanos). 
  - Cómo se convierte un tipo de objeto a otro (ej.: de entero a cadena).
  - Ejemplos de operaciones (suma, resta, multiplicación, división y división de enteros).
  - Cómo se guarda el valor en una variable, imprimirla y operar con ella.


__En el archivo M4 - 02 (02/10/23):__
  - Esquema con los tipos de datos en Python.
  - Cómo guardar `int`, `float`, `str` en variables y operar con ellas.



__En el archivo M4 - 03 - Condicionales (02/10/23):__
  - Tabla con las operaciones de comparación.
  - Tabla con los elementos que Python considera falsos (ej.: [ ], ( ), { }, 0, 0.0).
  - Ejercicios:
      - Condicionales if a partir de un diagrama de flujo de superhéroes.
      - Identificar un año bisiesto a partir de condicionales `if`, `elif` y `else` y operaciones con módulo (__%__).
      - Identificar un palíndromo con funciones (`replace`, `lower.( )`, `upper( )`, `reverse`) y condicionales.

   
__En el archivo M4 - 06 - Bucles (03/10/23):__
  - Bucles `while`.
  - Bucles __infinito__ con la función `break`.
  - Continuar un bucle con la función `continue`.
  - Iterar con `for` variable_iteradora `in`'.
  - Generar secuencias de números con la función `range(start, stop, step)`.
  - Bucles __anidados__ con `for` i `in` `range( )`:
                                 `for` j `in` `range( )`:
  - Ejercicios sobre bucles '`for` variable_iteradora `in`' y `while`.

    
  __En el archivo M4 - 10 - Pandas (03/10/23):__
  - Importar la librería `pandas` as `pd`.
  - Ejercicios con un DataFrame:
      - Seleccionar filas (df[ ]) con notación de slicing.
      - Seleccionar columnas (df[[Columna1, Columna2...]]) con notación de slicing.
      - Comprobar si el df está vacío.
      - Comprobar si los datos del df son nulos.
      - Acceder y modificar a un valor del df con la función `df.loc`.
      - Sumar valores de las columnas con la función `sum`.


   
  __En el archivo Prophet v2 - Predecir el valor de Amazon (04/10/23):__
  - Instalar (`!python -m pip install prophet`) y descargar los datos (`!pip install yfinance`) de la librería Prophet para predecir series temporales desarrollada por Facebook.
  - Importar las librerías:
      - `pandas` as `pd`
      - `yfinance` as `yf`
      - `plotly.graph_objects` as `go`
  - Descargar la serie temporal de Amazon desde Yahoo Finance y se comprueba si hay nulos.
  - Crear la gráfica con la fecha y el valor de entrada.
  - Entrenar el modelo:
      1) Guardar el modelo predictivo (Prophet) en una variable (`variable = Modelo()`).
      2) Entrenar el modelo con el df (`variable.fit(df)`). Fase de aprendizaje.
      3) Predecir los valores en un periodo de tiempo futuro (`future = m.make_future_dataframe()`).
  - Predecir el nuevo df con el modelo entrenado (`nuevo_df = variable_entrenada.predict(fechas)`)
  - Representar el modelo entrenado y los valores predecidos (`plot_plotly(variable, nuevo_df)`)


  __En el archivo SpaceX - 4 - EDA with Data Visualization (04/10/23):__
  - Importar las librerías:
      - `pandas` as `pd`
      - `numpy` as `np`
      - `matplotlib.pyplot` as `plt`
      - `seaborn` as `sns`
  - Importar los datos subiéndolos directamente o montando Drive.
  - __Categorical plot__(`sns.catplot`): regresión (seaborn y matplotlib).
  - __Gráfico de barras__(`sns.barplot`): `.groupby( )[ ].mean()`, `.sort_values( )`, `.reset_index( )`
  - __Gráfico de línea__(`sns.lineplot`): visualizar series temporales (`pd.DatetimeIndex( )`)

  __En el archivo M5 - 09 - Folium (04/10/23):__




  __En el archivo SpaceX - 1 - Data Collection Api v2 (05/10/23):__
  - Importar las librerías:
      - `requests`
      - `pandas` as `pd`
      - `numpy` as `np`
      - `datetime`
  - Hacer peticiones a páginas web con `requests.get(url)`
  - Transformar la respuesta a un diccionario `.json()`
  - Transformar los datos en un df de Python `pd.json_normalize()`
  - 
