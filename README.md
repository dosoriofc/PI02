# Proyecto de Análisis de Datos de Siniestros Viales para la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires

## Descripción del Proyecto

- Se realizara un proceso de Analisis de Datos con los datos de siniestros viales con victimas factales suministrados por la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para ello, nos suministran un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato xlsx
- Se genero un archivo en Visual Studio Code / Jupyter con el procesamiento realizado a los datos suminstrados y el Analisis Exploratorio de los Datos (EDA)
- Se genero un Dashboard en la aplicacion Power BI que incluyo todo el analisis de los datos con graficos, tablas, medidadas, KPIs y recomendaciones relacionadas con el estado actual de los KPI y como mejorarlos y lograr los objetivos estrategicos establecidos
- Se realizo el respaldo de todos los datos y archivos generados en cuenta de GitHub

## Herramientas usadas

- Visual Studio Code y  Jupyter Notebook como editor de codigo
- Python como lenguaje de programacion
- GitHub como repositorio del proyecto
- PowerBI como herramienta de analisis de datos
  
## Etapas del Proyecto

### 1. EDA (Exploratory Data Analysis)

Se realizo un análisis exploratorio de los datos en un notebook de Jupyter. Se documentaron los pasos realizados, con conclusiones correspondientes en cada paso y gráficos empleados y análisis de los resultados obtenidos, utilizando celdas Markdown. 
Se realizaron los siguientes pasos: 
- Analisis estadistico basico de los datos
- Búsqueda de valores faltantes
- Identificacion de valores atípicos/extremos u outliers
- Identificacon de registros duplicados
- Analisis de correlaccion entre las variables
- Generaciòn de archivo depurado y preparado para la herramienta de Analisis de datos
   
Ver notebook del EDA: [Resultado de Proceso de EDA](https://github.com/dosoriofc/PI02/blob/main/EDA.ipynb)

### 2. Dashboard en Power BI

El dasbhoard es ineractivo e incluye los filtros adecuados para explorar detalladamente los datos con la selección de cada uno de ellos. El dasboard se puede navegar facilmente a traves de los marcadores definidos en la secuencia apropiada para aproyar el storytelling. Este diseño facilita la interpretación de la información y su análisis.

Ver archivo de Dashboard en Power BI: [Dashboard PowerBI](https://github.com/dosoriofc/PI02)

### 3. Definicion y Analisis de KPIs

Como resultado del analisis de los datos se definieron los siguientes KPI como los mas apropiados para lograr mejorar los resultados de la gestion de la Secretaria de Transporte en lo relacionado a la disminucion de los siniestros viales en la ciudad y de las vicitimas mortales    

#### KPI 1:
Reducir en un 5% la tasa de homicidios en siniestros viales de los últimos tres meses, en la Ciudad de Buenos Aires, en comparación con la tasa de homicidios en siniestros viales del trimestre anterior.

En donde se define la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en la Ciudad de Buenso Aires durante un período de tiempo de 3 meses.

#### KPI 2:
Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

En donde se define la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. 

#### KPI 3:
Reducir en un 10% la cantidad de victimas peatones en el último año, en CABA, respecto al año anterior.

#### Resultados Obtenidos KPI 1:
Al analizar los datos de los ultimos 2 trimestres se observa que la tasa de homicidios en siniestros viales del ultimo trimestre aumento un 10% en lugar de disminuir el 5% que era el objetivo deseado, por lo que no se logro alcanzar este objetivo estrategico 

#### Resultados Obtenidos KPI 2:
Al analizar los datos de los siniestros ocurridos en los ultimos 2 años se observa que la cantidad accidentes mortales de motociclistas en siniestros viales en el ultimo año aumento un 70% en lugar de disminuir el 7% que era el objetivo deseado, por lo que no se logro alcanzar este objetivo estrategico 

#### Resultados Obtenidos KPI 3:
Al analizar los datos de las victimas mortales en los ultimos 2 años se observa que la cantidad victimas peatones en el ultimo año disminuyo en un 2.9% en lugar de disminuir el 10% que era el objetivo deseado, por lo que no se logro alcanzar este objetivo estrategico 

### Conclusiones y Recomendaciones

1. Enfocar esfuerzos educativos, preventivos y de vigilancia específicos para las poblaciones con mayor frecuencia de siniestros:

   + **Conductores de Motos** como victimas más frecuentes en los siniestros:
      + Sexo: masculino
      + Edad: entre 20 y 32 años

   + **Peatones** como victimas muy frecuentes en los siniestros
      + Edad: entre 55 y 85 años

   + Conductores causantes de siniestros en mayor frecuencia
      + **Conductores de Autos y Vehículos de Carga** como mayores causantes de victimas en motos
      + **Conductores de Transporte Público y Vehículos de Carga** como mayores causantes de victimas peatones

2. Enfocar los esfuerzos educativos, preventivos y de vigilancia en lugares con mayor cantidad de victimas registradas:
   + **Avenidas:**   Av. General Paz, Av. Rivadavia y Av. del Libertador (principalmente en los cruces de estas avenidas con otras calles)

   + **Comunas:** 1, 4, 8 y 9 

3. Enfocar los esfuerzos educativos, preventivos y de vigilancia en los lapsos de tiempo con mayor cantidad de victimas:

   + Horas entre las **4am y 7 am**, principalmente los días **Sábados y Domingo** (solo esta franja horaria presenta el 10% de las victimas)  

4. Con Base al análisis presentado, se logra demostrar que alcanzar los objetivos establecido para los 3 KPI's se podría lograr de varias maneras, sin embargo se recomienda enforcar y optimizar recursos en aquellas medidas que hagan más probables lograr el éxito deseado de la manera mas eficiente:

    + Por ejemplo, si se logra **disminuir en sólo un 15% el número de siniestros mortales en motos** que ocurren sólo los días **sábados y domingo en el horario comprendido entre 4am y 7am** se lograria reducir la tasa de homicidios por siniestros viales del último trimestre en un 5% y reducir el total de siniestros en moto del último año en un 7% alcanzando los objetivos indicados por los primeros KPI's planteados

5. A pesar de las medidas que se hayan logrado implementar en el pasado, no se nota un descenso consistente de las victimas por mas de 2 trimestres consecutivos (a excepción del año 2021) por lo que se recomienda generar planes para disminuir la siniestralidad, las victimas y los KPI seleccionados que sean a largo plazo para que los logros obtenidos sean consistente por mas de 1 año y no haya un efecto rebote como se observó en el análisis realizado 

Agradecemos la confianza depositada por la Secretaría de Transporte en **SoyHenry** para lograr este importante objetivo de **lograr una Ciudad Autónoma de Buenos Aires mucho mas segura para todos los actores viales de la ciudad** 

### Repositorio de GitHub

Se creo un repositorio en l plataforma de GitHub invcluyendo un Readme con las caracteristicas del proyecto su proyecto, los resultados obtenidos y recomendaciones, asi como los links a los documentos y datos empleados y generados en el desarrollo del proyecto 

Ver Repositorio en GitHub: [Repositorio GitHub](https://github.com/dosoriofc/PI02)

### Datos Empleados
Los datos inicialmente entregados para el desarrollo del proyecto se encuentran en un archivo en formato excel denominado homicidios.xlsx y contienes dos tablas: una denominada **hechos** con los datos que caracterizan el siniestro vial y otra denominada **victimas** con los datos que caracterizan a las victimas fatales del siniestro vial

Ver dataset original: [Dataset Original](https://github.com/dosoriofc/PI02/tree/main/dataset)
