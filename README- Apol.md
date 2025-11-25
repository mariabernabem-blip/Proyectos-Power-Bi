# Proyecto 2:
## El equipo directivo requiere conocer los indicadores de Beneficios ($) y de % Porcentaje respecto a Ingresos, para así poder medir el desempeño de los productos y regiones, para poder desarrollar estrategias.

## Obtener datos de Excel
Se realiza la conexión a la fuente de datos (archivos de Excel) utilizando la opción Obtener datos y se cargan las tablas al modelo de datos de Power BI Desktop. 

## Preparación de datos
De las dos tablas de datos obtenidas hay que limpiar y organizar en Power Query:

· Modelado de datos

De las tablas de datos hay que crear estructuras que permitan relacionar los datos. Realizamos transformaciones de datos específicas dentro de Power Query, como la limpieza de filas no deseadas (ej. títulos fuera de la tabla), división de columnas (ej. separando país y continente) y el manejo de formatos de datos. Navegamos a la Vista de Modelo para establecer y gestionar las relaciones entre las diferentes tablas cargadas, asegurando un modelo de datos correcto para el análisis.

Nos introducimos en el DAX (Data Analysis Expressions) para calcular las métricas que queremos, en nuestro caso: ganancias y porcentaje de ganancia (división de ganancia entre ingresos). Para ello realizamos medidas dentro de la tabla de datos, dentro del inicio, y no creando columnas nuevas.

## Visualización de datos 
En esta práctica, tomamos los datos de una empresa ficticia llamada Apol, que cuenta con un extensivo volumen de datos sobre los ingresos y gastos registrados en el periodo de 2025 a 2027. Todos estos registros son referentes a las categorías de sus Productos y Regiones.

Se añaden distintos tipos de gráficos (barras, líneas, mapas) y tablas a la Vista de Informe. Se seleccionan las columnas y medidas adecuadas para cada elemento visual.

Se configura cómo interactúan los elementos visuales entre sí y se añade la funcionalidad de Segmentación de datos (Slicers) para filtrar la información del informe.
Se aplican estilos y configuraciones de formato detalladas a los gráficos y tablas para mejorar la presentación (ej. colores, títulos, ejes).
Se insertan Botones y se configuran sus Acciones: borrar segmentaciones.
