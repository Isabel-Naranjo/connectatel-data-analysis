# Análisis de Datos - ConnectaTel

## Objetivo del proyecto
En este proyecto analicé los datos de ConnectaTel para entender cómo usan sus clientes las llamadas y mensajes en México y Colombia. El objetivo fue limpiar los datos, agrupar a los usuarios por edad y nivel de consumo, y entregar algunas recomendaciones básicas para mejorar los planes de la empresa.

## Principales hallazgos
Durante la exploración y el análisis descubrí varias cosas interesantes:
* El grupo más grande de clientes son los Adultos (51%), mientras que los Jóvenes son el grupo más pequeño (18%).
* La gran mayoría de los usuarios (casi el 75%) tiene un nivel de uso "Medio" en sus servicios. Solo un 7% registra un uso "Alto".
* Un dato que me sorprendió durante la limpieza de datos fue encontrar errores de registro bastante inusuales, como fechas de clientes que estaban en el futuro.

## Pasos del análisis
1. Exploración: Cargué los datos y revisé qué información contenían.
2. Limpieza de datos: Corregí valores nulos, arreglé errores en las fechas y cambié los tipos de datos para poder trabajar mejor.
3. Análisis y segmentación: Agrupé a los clientes por edades (Jóvenes, Adultos y Adultos Mayores) y por cuánto usan el servicio (Uso Bajo, Medio y Alto).
4. Conclusiones: Escribí mis recomendaciones finales basadas en los resultados.

## Archivos utilizados
Para este análisis usé tres archivos de datos:
* plans.csv: Tiene la información de los planes actuales (precio, minutos y mensajes incluidos).
* users_latam.csv: Tiene el perfil de los clientes (edad, ciudad, fecha de registro y plan).
* usage.csv: Tiene el registro de cuánto usaron las llamadas y los mensajes.

## Herramientas que usé
* Lenguaje: Python
* Librerías: pandas, numpy, matplotlib y seaborn

## Cómo ver este proyecto
Puedes leer todo el análisis, ver el código y los gráficos abriendo el archivo .ipynb aquí mismo en GitHub.

Nota sobre los datos: Los archivos de datos (.csv) fueron proporcionados por el programa y no están incluidos en este repositorio. Sin embargo, el notebook muestra el análisis completo con los resultados y visualizaciones ya generadas, por lo que no es necesario descargar nada para revisarlo.
