# MFT_error_detection
Este repositorio contiene un proyecto exploratorio enfocado en la preparacion de datos que contribuya a la detección de anomalías en transferencias de archivos.

## Requisitos Previos
1. El archivo "01_MFT_Prep_Data_.ipynb" requiere que las siguientes bibliotecas de Python estén instaladas previamente: numpy, pandas, seaborn y matplotlib.
2. Es necesario descomprimir el archivo "01_data_initial.zip", el cual contiene el archivo CSV "01_data_initial.csv". Este archivo debe ubicarse en el mismo directorio que el notebook "01_MFT_Prep_Data_.ipynb" al momento de su ejecución.
3. Si desea ubicar el archivo CSV en un directorio distinto, deberá modificar la variable path dentro del notebook, la cual por defecto está declarada como: path = './01_data_initial.csv'   
Esta línea se encuentra en la sección 1.1 del archivo "01_MFT_Prep_Data_.ipynb"


## Ejecución
1. Verifica que se cumplan todos los requisitos previos mencionados.
2. Abra el archivo "01_MFT_Prep_Data_.ipynb" en tu entorno de trabajo (por ejemplo, Jupyter Notebook o VSCode).
3. Ejecuta el notebook para comenzar con el análisis de datos y la detección de anomalías.

## Descripción de Archivos
A continuación se detallan los archivos principales incluidos en este repositorio y su función dentro del flujo de trabajo:
- "01_data_initial.zip": 
Archivo comprimido que contiene el dataset original: "01_data_initial.csv": conjunto de datos inicial utilizado para el análisis y preparación de los mismos. Contiene información anonimizada sobre las transferencias de archivos, necesaria para entrenar y evaluar los modelos de detección de anomalías.

- "01_MFT_Prep_Data_.ipynb": Notebook de Jupyter que realiza el procesamiento y análisis de los datos.

- "02_data_prepared.csv": Resultado de la preparación de los datos realizada en el notebook anterior.
Este archivo contiene los datos limpios y estructurados, listos para ser utilizados en etapas posteriores del proyecto.
