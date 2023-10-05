# Curso_Python

Curso semipresencial de Big Data incluido en el programa "Hackea tu Futuro" organizado por la escuela de negocios The Valley Digital Business School (Granada, 2023)
-

__Contenidos de los archivos de Python realizados en Google Colab__

__En el archivo M4 - 01 (02/10/23):__
  - Tipo de datos (enteros, flotantes, texto, booleanos). 
  - Cómo se convierte un tipo de objeto a otro (ej.: de entero a cadena).
  - Ejemplos de operaciones (suma, resta, multiplicación, división y división de enteros).
  - Cómo se guarda el valor en una variable, imprimirla y operar con ella.


__En el archivo M4 - 02 (02/10/23):__
  - Esquema con los tipos de datos en Python.
  - Cómo guardar int, float, str en variables y operar con ellas.


__En el archivo M4 - 03 - Condicionales (02/10/23):__
  - Tabla con las operaciones de comparación.
  - Tabla con los elementos que Python considera falsos (ej.: [ ], ( ), { }, 0, 0.0).
  - Ejercicios:
      - Condicionales if a partir de un diagrama de flujo de superhéroes.
      - Identificar un año bisiesto a partir de condicionales __if__, __elif__ y __else__ y operaciones con módulo (__%__).
      - Identificar un palíndromo con funciones (_replace_, _lower.( )_, _upper( )_, _reverse_) y condicionales.

   
__En el archivo M4 - 06 - Bucles (03/10/23):__
  - Bucles __while__.
  - Bucles __infinito__ con la función _break_.
  - Continuar un bucle con la función _continue_.
  - Iterar con '__for__ variable_iteradora __in__'.
  - Generar secuencias de números con la función _range(start, stop, step)_.
  - Bucles __anidados__ con __for__ i __in__ range( ):
                                 __for__ j __in__ range( ):
  - Ejercicios sobre bucles '__for__ variable_iteradora __in__' y __while__.

    
  __En el archivo M4 - 10 - Pandas (03/10/23):__
  - Importar la librería _pandas_ as _pd_.
  - Ejercicios con un DataFrame:
      - Seleccionar filas (df[ ]) con notación de slicing.
      - Seleccionar columnas (df[[Columna1, Columna2...]]) con notación de slicing.
      - Comprobar si el df está vacío.
      - Comprobar si los datos del df son nulos.
      - Acceder y modificar a un valor del df con la función _df.loc_.
      - Sumar valores de las columnas con la función _sum_.

   
  __En el archivo Prophet v2 - Predecir el valor de Amazon (04/10/23):__
  - Instalar (__!python -m pip install prophet__) y descargar los datos (__!pip install yfinance__) de la librería Prophet para predecir series temporales desarrollada por Facebook 
    
    
  __En el archivo SpaceX - 4 - EDA with Data Visualization (04/10/23):__
  - Importar las librerías:
      - `pandas` as _pd_
      - _numpy_ as _np_
      - _matplotlib.pyplot_ as _plt_
      - _seaborn_ as _sns_
  - Importar los datos subiéndolos directamente o montando Drive.
  - __Categorical plot__(__sns.catplot__): regresión (seaborn y matplotlib).
  - __Gráfico de barras__(__sns.barplot__): _.groupby( )[ ].mean()_, _.sort_values( )_, _.reset_index( )_
  - __Gráfico de línea__(__sns.lineplot__): visualizar series temporales (_pd.DatetimeIndex( )_)
