# Resumen Práctica 3
## Análisis Datos COVID
Para la realización de esta primera parte de la práctica, hemos instalado la librería pandas para poder tener la herramienta de análisis de código abierto. A continuación, hemos establecido la variable con la que vamos a trabajar que es una base de datos en formato JSON sobre los datos de COVID en diferentes países. 
A partir de ella, hemos creado el dataframe con el hemos visualizado el contenido de esta tabla de datos con el comando df. Hemos explorado la tabla mostrando la cabecera (.head) y la cola (.tail). 
A continuación se ha mostrado el dataframe como objeto de pandas y a partir de ahí, con diferentes funciones hemos ido mostrando la tabla según qué datos, por ejemplo mostrando solo las columnas o una fila de una columna en específico, en este caso la 66. 

El siguiente paso que hemos realizado ha sido coger otra variable que ha sido la de casos covid en tiempo real y hemos creado un nuevo dataframe, en función de España. Y hemos visualizado el mismo contenido que el anterior dataframe (cabecera y cola). Después hemos indexado todos los datos mostrando solo los datos de la columna "Date" y luego lo hemos hecho en función de "Cases". Luego hemos creado un gráfico con estos datos. 
Además, se han vuelto a repetir todos los pasos con el país Italia. Después, hemos concatenado las dos variables para crear un gráfico comparativo. 

Luego lo hemos guardado en csv y la imagen del gráfico en png. 

Este archivo de Jupyter se ha guardado en formato html y ipynb. 

## Análisis Datos accidentes Zaragoza

Para esta segunda parte de la práctica hemos instalado la librería folium para poder visualizar un mapa en Jupyter. Hemos establecido las variables "url_zrgz" y "geo_zrgz".A continuación hemos creado el mapa de zaragoza. Se ha establecido un nuevo dataframe con los accidentes producidos en Zaragoza, luego como objeto de pandas y por último se ha visualizado solo la columna "reason" y la columna "geometry"
