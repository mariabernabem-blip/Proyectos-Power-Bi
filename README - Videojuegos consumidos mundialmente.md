# Proyecto 1:
## Un análisis mediante Power Bi de los video juegos más consumidos mundialmente (desde 1980 hasta 2017)

## Objetivos
En este proyecto de nivel básico de Power Bi, voy a llevar a cabo un reporte interacivo que nos permita analizas las ventas de millones de copias de videojuegos a nivel mundial. Se trata de una toma de contacto con la aplicación y es un ejemplo muy sencillo de lo que Power Bi es capaz de hacer. 

Para ello, vamos a analizar por las categorías de: año, región, plataforma,  género y editorial. 

Nos vamos a hacer las preguntas: 
1. ¿Cuáles es el género de video juegos más vendido? 
2. ¿De qué forma es la función que representa las ventas por año?
Conexión a Datos de Excel: El proceso para importar la tabla de ventas de videojuegos desde un archivo Excel a Power BI, y cómo funciona el navegador para seleccionar las pestañas o tablas a cargar.

## Preparación de Datos (Power Query Editor):

Eliminación de columnas innecesarias (ej. la columna de ventas global).

Anulación de dinamización de columnas (Unpivot Columns): La técnica clave para transformar las columnas de ventas por región (ventas en NA, ventas en EU, etc.) en solo dos columnas: una de "Región" y otra de "Ventas", que es el formato ideal para Power BI.

Renombrar y reemplazar valores en las nuevas columnas (ej. cambiar "Ventas en EA" a "Norteamérica").

Asegurar que el tipo de datos de cada columna sea correcto (ej. cambiar el campo "Año" a tipo Texto para evitar que se sume).

## Modelado y Análisis Rápido

Modelado de Datos: Se explica brevemente la importancia del modelado (especialmente la gestión de relaciones entre tablas, aunque no se usa en este proyecto). Se muestra cómo ocultar campos y tablas del reporte. 

Vista de Datos: Cómo usar la vista de datos para realizar análisis rápidos, como filtros, ordenaciones y la aplicación de formatos a las columnas (ej. cambiar la columna de ventas a formato de separador de miles). Para que los datos en la tabla estuvieran listos, tuve que transformar los datos y activar la "anulación de la dinamización de columnas", pues los datos de las ventas venían en columnas separadas y para el buen funcionamiento de la aplicación deben estar en una misma columna.

## Visualización y Creación del Report
·Creación de las primeras visualizaciones:

Una Tabla con el detalle de Nombre, Año y Ventas.

Un Gráfico de Columnas Agrupadas para analizar las ventas por año.

Un Gráfico de Anillo (Donut) para ver el porcentaje de ventas por región.

Se muestra la interactividad básica de Power BI (cómo la selección en un gráfico filtra a los demás).

·Se agregan más gráficos y herramientas de filtrado:

Gráficos de Barras Horizontales (copiados y modificados) para mostrar las ventas por Plataforma y por Género.

Una Tarjeta (Card) que muestra el total de copias vendidas en millones, la cual se actualiza con cada filtro.

Segmentaciones de Datos (Slicers): Se agregan filtros desplegables para Año, Región, Género, Plataforma y Editorial, lo que permite la interacción dinámica por el usuario.

El archivo de Excel del que hemos obtenido los datos contiene 16327 datos por columna, por lo tanto, la aplicación de Power Bi nos impulsa a usarla debido al extenso de los datos.


## Finalmente se llevarán a cabo unas conclusiones acerca de este proyecto, contestanto a estas preguntas:
1. ¿Cuáles es el género de video juegos más vendido?
   El género más vendido se trata del género de acción, y además, es mayor en países como EEUU y Europa. Convendría decir que la activación de la violencia en los más pequeños se ve reflejada en la adultez, y podemos verla en cómo la sociedad actual, los jóvenes se ven más irritables que décadas antes de que existiera este género de video juegos.
   
3. ¿De qué forma es la función que representa las ventas por año?
   La gráfica representa la suma de de ventas (mill) frente a los años, con un máximo en 2008. Se observa perfectamente una curva de crecimiento que podría ser exponencial desde los 2000 hasta 2008 y un gran decrecimiento en los siguientes 8 años debido al desuso de estas consolas. Por lo tanto la vida media de estas consolas ha sido de 8 años.

## Conclusión
   Los datos dados no obtienen números para la actualidad de los video juegos, sin embargo sigue siendo interesante pues, a la existancia de las nuevas tecnologías como ordenadores y smartphones, se observa claramente un desapego de las consolas y una nueva tendencia a usar estos dispositivos móviles y portátiles como elemento de ocio. Ahora prevalece el poder llevar tu vide juego a cualquier lado y a la vez jugar en tu propia casa. 


