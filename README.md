
----------------------------------------------------------------------

# Proyecto sobre vivienda en España por CC.AA./Nacional #:

He empezado por crear un repositorio y en una ruta local. He enlazado mi repositorio local de mi pc con mi repositorio en GitHub.
He adquirido las bases de datos principalmente desde Kaggle y del INE.


---------------------------------------------------------------------

# Objetivos:

 	* Saber en que CC.AA. de España es más fácil para comprar o vender una vivienda. (Ya sea de vivienda nueva, segunda mano u otro...)

 	* Ver o observar variables de precios según zonas.

 	* Saber como ha ido evolucionando o variando el precio año tras año.

	* El PIB per cápita de cada año, o incluso si la encuentras el sueldo medio por persona de cada año, con respecto al precio medio de la vivienda en cada año, sería útil para ver dónde es más fácil comprar vivienda con respecto 	al dinero que tienen los habitantes.

	* Comparación de PIB en cada región con el precio medio de la vivienda, e incluso una evolución y/o progresión por CCAA del PIB también sobre el precio de vivienda. Así no solo sabría qué área es más o menos fácil comprar 	vivienda, sino cómo ha evolucionado con el tiempo.

	Ejemplo. Si coges la comunidad de Madrid, el PIB per cápita de cada año, o incluso si la encuentras el sueldo medio por persona de cada año, con respecto al precio medio de la vivienda en cada año, sería útil para ver dónde es 	más fácil comprar vivienda con respecto al dinero que tienen los habitantes.

    	* Resultado:

    	Un gráfico de correlación entre PIB y precio medio de la vivienda por CCAA.
    	Un gráfico de evolución progresiva para cada región y año.
	Ver el PIB per cápita por regiones.
	Promedio de vivienda por año y CCAA.


----------------------------------------------------------------------

# Preguntas a resolver:

    * En qué regiones o CC.AA. es más fácil la compra/venta de vivienda?
    * Como varia el precio dependiendo de la CC.AA. donde se reside?
    * Qué zonas son más baratas o más caras?
    * Cuál sería el promedio por CC.AA.?
    * Cuál sería el PIB por región o CC.AA.?


# Extracción y exploración de datos:

	He explorado y extraído datos de las bases de datos que conseguido en Kaggle e INE sobre la vivienda en España.
	He utilizado código, funciones y variables que hemos ido viendo en clases para extraer datos en Python.

# Transformación:

	He eliminado columnas y filas con valores nulos, también filas duplicadas y reiniciado índice de dataframe.
	He aplicado código/función que cuenta los valores nulos en cada columna.
	He convertido el DataFrame a un DataFrame de pandas.
	He hecho estadística descriptiva en todas las columnas.
	Información general del dataframe.

# Unión de tablas/BBDD de CSV:
Posteriormente, una vez explorado, extraído y transformado los datos de las BBDD, he querido unir cada una de ellas en una sola BBDD.
Algunas tablas las he dejado sueltas, por ejemplo, la de PIB per cápita y las he importado a Power BI para las visualizaciones.

---------------------------------------------------------------------

# Visualización en Power BI:

En Python no he sabido hacer visualizaciones con gráficos y me iba a llevar más tiempo hacerlo, por ese motivo he tenido que saltarme ese paso.

Después de terminar en Python los datasets los he importado inicialmente a Tableau, pero viendo los problemas y errores que me da constantemente el programa he tenido que importar los CSV a Power BI y realizar de visualizaciones desde ahí.

	*Primer plot*:

	Por una parte, el gráfico de la izquierda  es un gráfico de areas donde se puede ver la suma del precio de la vivienda por año y por CCAA, del cuál varia en función de la región, Extremadura sería la que tiene un menor precio, 	la más barata, y por contra la Comunidad de Madrid sería la que tiene precio más alto y por lo tanto, viviendas más caras.

	Por otra parte, el gráfico de la derecha se puede ver como cambia o evoluciona año tras año, entre el 2000 y 2010 hay como un repunte bastante alto, entre 2010 y 2015 ese repunte baja estrepitosamente y a partir de 2020 vuelve a 	subir progresivamente...
 

	*Segundo plot*:

	En la gráfica de la izquierda que es de tabla se indica los datos de CCAA, edad media de la población, promedio de edades de población desde menores hasta jubilados.

	En la gráfica de la derecha, de barras apiladas, podemos ver el promedio de edades por cada región o comunidad autónoma, el Principado de Asturias es la región con edad media más alta y por el contrario Melilla es la que tiene 	la edad media menor al resto. Se puede clicar una a una en las barras apiladas para ver información y detalle sobre edad media de cada región.

	Por último, el gráfico anillo/circular en la parte inferior del dashboard muestra el promedio de población por año, si clicamos año tras año en el recuadro de la izquierda veremos como cambian los gráficos.


	*Tercer plot*:

	Tenemos a la izquierda una tabla de segmentación de datos, dónde podemos seleccionar por CCAA o región, una a una, y automáticamente el mapa muestra en punto/zona del mapa está esa comunidad.

	En el gráfico del centro es una mapa coroplético, donde se puede ver las comunidades autónomas por colores y si clicamos en cada una de las CCAA se puede ver el PIB per cápita y automáticamente queda destacado y señalado también 	en el gráfico colocado de la derecha.


	*Cuarto plot*:

	Por último, en el gráfico de mapa coroplético colocado a la izquierda podemos ver diferentes círculos de colores, unos más grandes y otros más pequeños, esos círculos indican el promedio de precios de la vivienda por región y 	permite hacer una comparación con tan solo pasar el puntero del ratón por encima de cada circulo de colores y adicionalmente junto a ese mapa, a la derecha se puede ver una tabla con información sobre vivienda general, nueva y 	de segunda mano, donde también se muestra el periodo por comunidades e índices y tasas con variación media anual junto con el promedio total detallado.

---------------------------------------------------------------------------------

# Conclusión:

Ver una evolución progresiva del precio en el mercado de la vivienda en España, detectar y analizar tendencias y patrones sobre este tema, ver en qué zonas es más fácil adquirir una vivienda, ya sea nueva o de segunda mano, comparativa PIB por año, regiones, edad media de población, etc... Visualizar una comparación, promedio o mediana año tras año del precio, también la suma del periodo por comunidades autónomas, etc... Tras el análisis realizado, se ha tratado de dar respuesta de una manera precisa y eficiente.


------------------------------------------------------
