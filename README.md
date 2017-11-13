# TFM_ML4sportsBets
Final Project: Master on DS (4th ed.)
## Introduction: ##
Las apuestas deportivas son las apuestas conocidas más antiguas, teniendo registro de ellas desde la Antigua Grecia. Desde ese momento han ido apareciendo muchos estudios con el objetivo de predecir el resultado de cualquier evento deportivo. Sin embargo no ha sido hasta la primera década del siglo XXI con el boom de internet cuando las apuestas deportivas han experimentado un dramático aumento de la popularidad. Las nuevas tecnologías aplicadas al procesamiento de informacin, han hecho que todos esos estudios se hayan quedado obsoletos y han abierto la puerta a la aplicación de nuevos métodos de predicción.
## Objetivo:
Inverstigar el amplio rango de posibilidades que nos ofrecen las técnicas de Machine Learning en este campo de estudio. El objetivo final es crear una serie de modelos de ML y analizar su capacidad predictiva haciendo un analisis detallado de sus principales parametros.
## Esquema de trabajo:
Introducción: Capítulo 1

Data Adquisition: Capítulo 2

Data Cleansing and preparation: Capítulo 3 y 4.

Analysis: Capítulo 5, 6 y 7.

Conclusiones y aplicación del Modelo: Capítulo 8 y 9
## Manual de usuario:
**Docs.** Raw data. Archivos con la información deportiva de los años 2000 a 2017, uno por año. Los archivos 00-16 se utilizan en los notebooks 3-8. El archivo 17 se utiliza exclusivamente para el notebook 9.

**Docs.DF.** Información elaborada. Se hacen distintas copias de la información en diversos puntos del proceso como backup y para poder alimentar otros notebooks, teniendo así la capacidad para dividir el trabajo en distintos apartados.

 El DF `framesDCWO2` está cargado en formato zip al superar el tamaño máximo permitido por GitHub (25MB)

**Img.** Copia de todas las imágenes generadas en el proyecto en formato `png`.

**The Story.** Contiene todos los notebooks en que se descompone el trabajo. Sigue el mismo orden de “Contents”.

**CONTENTS.** Índice del trabajo, desarrollado en los notebooks.

## Technology:
Software – `Python` (pandas, scikitlearn, Seaborn, Pyplot), `Bash`

Hardware – [`Mac Book Pro Retina i5 2.6 GHz, 8GB DDR3L`] 

### Install:
1. Descargar todos los archivos **Docs** y **Docs.DF.** Descomprimir `framesDCWO2`. 

2. Descargar todos los arvhivos `.py` en **The Story**. Revisar que las rutas de acceso a los ficheros son las adecuadas (`pd.read_csv`). Están siempre en las primeras líneas de cada notebook. 

3. A partir de aquí se pueden empezar a ejecutar los notebooks en cualquier orden. El notebook más pesado es el que contiene el Análisis (puntos 5, 6, 7), pudiendo llegar a tardar unos 20 minutos en ejecutarse por completo.

4. Utilizar **CONTENTS** como guía del proyecto. 
### Bugs (errores):
No hay errores conocidos en el programa
## Author:
Ignacio San Juan Cisneros

Desarrollo de Negocio en Mercedes-Benz Vans S.L.U.

ignacio.sanjuan@daimler.com 
 
