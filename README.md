# Proyecto transformación digital actuazlización Adalab Mónica Griselle y Cris

## Descripción
Este proyecto contiene el código en Python necesario para hacer una transformación digital de una empresa donde nos entregan unos datos sin limpiar para posteriormente poder sacar conclusiones a cuestiones que sean de relevancia para la actualización y marketing de la empresa según el estado del mercado actual.


## Integrantes
* Cristina Sangrador
* Griselle Alanís
* Mónica Serrano 

## Motivación para la realización de este proyecto

 Estamos trabajando para una empresa en pleno proceso de transformación digital. Quieren hacer un estudio de los datos que tienen, para ello nos piden que saquemos conclusiones utilizando gráficas a cuestiones de relevancia que puedan utilizar para actualizarse.

## Estructura de las carpetas 

 El presente repositorio está estructurado de la siguiente manera:

 - README

 - graficas: todas las graficas realizadas en el proyecto.

 - documentacion_adicional:
   * columnas_dataframe: todas las columnas del dataframe explicadas.
   * relacion_graficas_columnas: graficas realizadas con las columnas seleccionadas.

 - notebooks: carpeta que contiene todos los jupyter utilizados para la realización de este proyecto.
    * unificado: proceso de unificación de los 4 archivos facilitados por el cliente, incluidas las columnas relacionadas.
    * limpieza: incluye todo el proceso de limpieza del dataframe unificado.
    * estudio_df: todo el proceso de exploración del dataframe limpio.
    * dataframe_graficas: creación de dos dataframes relacionados a partir de un ID, que posteriormente se utilizarán para la obtención de gráficas.
    * preguntas_graficas: creación de todos las gráficas.
    * clases_funciones: creación de las clases a partir de todas las funciones realizadas en el resto de archivos.

 - Carpeta datos: en esta carpeta se encuentran todos los datos que el cliente nos ha ofrecido.

 - carpeta archivos_resultantes: en esta carpeta se encuentran los archivos resultados de cada paso realizado en el proyecto.
    * archivo_unificado: dataframe que incluye los 4 archivos facilitados por el cliente sin limpiar.
    * columnas_unificadas: dataframe con todas las columnas unificadas.
    * archivo_unificado_limpio: dataframe unificado y limpio preparado para entregar a cliente.
    * dataframe_graficas: dataframe con todas las columnas que no es necesario separar por filas. Se utilizará para la creación de gráficas.
    * dataframe_graficas_explode: dataframe con todas las columnas que es necesario separar por filas. Se utilizará para la creación de gráficas.


## Lenguajes utilizados
* Python

## Librerias utilizadas

* **Numpy**. Puedes encontrar la documentación oficial a través del siguiente [link](https://numpy.org/doc/stable/user/).
* **Pandas**. Puedes encontrar la documentación oficial a través del siguiente [link](https://pandas.pydata.org/docs/user_guide/index.html).
* **Matplotlib.pyplot**. Puedes encontrar la documentación oficial a través del siguiente [link](https://matplotlib.org/stable/users/index.html).
* **Seaborn**. Puedes encontrar la documentación oficial a través del siguiente[link](https://seaborn.pydata.org/tutorial.html).
* **Regex**. Puedes encontrar la documentación oficial a través del siguiente [link](https://docs.python.org/3/library/re.html).

## Estructuras utilizadas
* Python:
    * Clases
    * Funciones
    * Constructor
    * Rutas relativas
    * Condicionales If
    * Bucles for
    * Apertura y lectura de ficheros
    * Listas
    * Tuplas
    * Diccionarios
    * REGEX
    * Métodos de strings
    * Métodos de listas
    * Métodos de tuplas
    * Métodos de diccionarios
    * Try...except
    * mysql.connector
    * Contol de errores
    * Código defensivo
