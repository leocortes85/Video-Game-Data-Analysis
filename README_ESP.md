![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=white)


# Video Game Data Analysis
 Practice for Data Analitics
![Analysis](images/Gaming_Portada.gif)

## ES: Resumen

Este proyecto se llevó a cabo como parte del trabajo integrador en el bootcamp de análisis de datos de "Soy Henry". Su objetivo principal es analizar el mercado de videojuegos y presentar un informe que sea de interés para posibles inversionistas en esta industria. Para lograr este objetivo, se utilizaron principalmente tres conjuntos de datos: "Video Game Sales", "Juegos en Steam" y "Console Sales".

El proyecto involucró la lectura y limpieza de datos de las tablas "Juegos en Steam" y "Video Game Sales". La limpieza de datos incluyó la reducción y extracción de géneros de videojuegos, así como la unificación de las clasificaciones de edad (rating) de los juegos en una sola categorización. Para esta clasificación se utilizó el sistema de calificación de Entertainment Software Rating Board (ESRB).

Además de la limpieza, se completaron valores faltantes en varias columnas clave para el análisis, como las ventas en diferentes regiones y las ventas globales de los juegos presentados en las tablas.

Como resultado, se creó una tabla final que contiene las siguientes columnas:

- Id_Game: Identificador del juego.
- Name: Nombre del juego.
- Developer: Empresa desarrolladora del juego.
- Platform: Consola o plataforma para la que se desarrolla el juego.
- Release: Año de lanzamiento.
- Genre: Género del juego.
- Rating: Clasificación por edades (ESRB).
- Ranking: Posición del juego según ventas y popularidad.
- Average_Playtime: Tiempo promedio de juego por parte de los usuarios.
- Score: Calificación de los usuarios.
- NA_Sales: Ventas en Norteamérica.
- EU_Sales: Ventas en Europa.
- JP_Sales: Ventas en Japón.
- Other_Sales: Ventas en el resto del mundo.
- Global_Sales: Ventas totales.

Para facilitar el análisis en Power BI, se generaron tablas dimensionales basadas en las columnas de Género, Desarrollador, Plataforma y Clasificación por edades. Además, se creó una tabla que incluye datos de tiempo de juego promedio y otra que recopila las ventas por región. Estas tablas auxiliares se relacionaron con la tabla principal mediante identificadores.

El resultado final es una tabla principal con la estructura mencionada y tablas auxiliares:

- developer
- platform
- genre
- rating
- games_main
- Region_Sales
- Avg_Time_Steam

El proyecto también incluye la definición de diferentes KPI (Key Performance Indicators) que permiten establecer el objetivo de análisis. Estos KPI se implementaron en Power BI mediante la creación de medidas que facilitan la visualización de soluciones y resultados.

El análisis se presenta en tres informes principales:

1. Informe General: 
![General Report](images/Report1.png)

2. Informe de la Plataforma Steam: Analiza la plataforma de distribución de juegos Steam.
![Steam Platform Report](images/Report2.png)

3. Informe del Mercado de Consolas: Explora el mercado de consolas de videojuegos.
![Console Market Report](images/Report3.png)


Los informes se crearon en Power BI y se recopilaron en un informe escrito final en formato PDF (Carpeta Analisys_Report).

## Contacto

Para cualquier consulta o información adicional, no dudes en ponerte en contacto a través de este repositorio de GitHub.

## Créditos

Agradecemos a todo el equipo de "Soy Henry" y a los autores de los conjuntos de datos utilizados en este proyecto.

Nota: Las imágenes de informes mencionadas en este resumen están disponibles en el repositorio del proyecto.