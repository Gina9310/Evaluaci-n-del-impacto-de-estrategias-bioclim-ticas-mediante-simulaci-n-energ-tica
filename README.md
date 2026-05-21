# Evaluación del impacto de estrategias bioclimáticas mediante simulación energética

## Descripción del proyecto
En el presente trabajo, se realizaron simulaciones a través del software EnergyPlus con la finalidad de definir el impacto de la aplicación de estrategias bioclimáticas en el tiempo en confort térmico, en una vivienda ubicada en Fresnillo, Zacatecas con 120 m2 de construcción, distribuidos en 3 recamaras, cocina, dos baños, sala y pasillo. Se evaluaron las condiciones internas térmicas de la vivienda construida, la cual presenta un comportamiento térmico hostil según la estación del año, temperaturainterna cálida en verano y temperatura fría en invierno.

La aplicación de estrategias bioclimáticas mostró mejoras en las condiciones de confort, evidenciando el potencial de herramientas de simulación para optimizar el diseño de viviendas y edificios. Este trabajo busca impulsar el uso de software especializado en la evaluación de proyectos arquitectónicos y energéticos, promoviendo soluciones que aprovechen las características climáticas locales para mejorar la habitabilidad y reducir el consumo energético.

## Objetivo General
Evaluar el impacto de estrategias de arquitectura bioclimática sobre el confort térmico de una vivienda convencional ubicada en el municipio de Fresnillo, Zacatecas, mediante simulación energética utilizando SketchUp y EnergyPlus.

## Objetivos especificos
* Determinar el comportamiento térmico (temperatura promedio anual) de las zonas térmicas de la vivienda antes y después de la implementación de estrategias bioclimáticas.

* Calcular el porcentaje anual de horas dentro del rango de confort térmico por zona térmica para el caso base y para el escenario con estrategias bioclimáticas.

* Comparar el incremento del porcentaje de horas de confort térmico por zona térmica después de la implementación de estrategias bioclimáticas.

* Determinar anualmente y mensualmente las temperaturas promedio, las temperaturas máximas y mínimas y el grado o porcentaje de confort po ZT, con enfoque en ZT con mayores incrementos de temperatura.

## Variables
Temperatura interior promedio anual por zona térmica (ZT)
Diferencia/ Incremento de temperatura promedio entre el caso base y el escenario con estrategias bioclimáticas.
Número anual de horas dentro del rango de confort térmico por ZT.
Porcentaje anual de horas dentro del rango de confort térmico por ZT.
Incremento porcentual de horas dentro del rango de confort térmico después de la implementación de estrategias bioclimáticas.
Temperatura máxima y mínima anual por ZT

## Metodología
1.- Análisis bioclimático mediante Climate Consultant
Se utilizó el software Climate Consultant para determinar el rango de confort térmico exterior e identificar estrategias bioclimáticas adecuadas para el caso de estudio ubicado en Fresnillo, Zacatecas.

Rango de confort térmico: Se determinó un rango de confort térmico entre 21 °C y 27 °C.

Estrategias bioclimáticas seleccionadas

La principal estrategia identificada fue la GANANCIA SOLAR DIRECTA, complementada con medidas de CONTROL SOLAR.

Estrategias implementadas: Ampliación de la ventana de la sala de 1.5 m² a 6.2 m² para incrementar la ganancia solar y el aprovechamiento de iluminación natural. Incorporación de tragaluces en las tres recámaras con dimensiones de 0.5 m de altura y 1 m de ancho. Instalación de protecciones solares en ventanas de las recámaras 2 y 3, con dimensiones de 1.74 m de ancho y longitud correspondiente al espacio de cada recámara.

Estas estrategias fueron implementadas con el objetivo de mejorar el confort térmico interior y reducir la incidencia de radiación solar directa durante el periodo de verano.

2.- Simulación energética mediante SketchUp y EnergyPlus
Se desarrolló un modelo energético de la vivienda utilizando SketchUp y EnergyPlus.

Se evaluaron dos escenarios:

Caso base sin implementación de estrategias bioclimáticas (diagnóstico). Caso con estrategias bioclimáticas implementadas.

3.- Exportación y procesamiento de datos
Los resultados de simulación fueron exportados en formato CSV para su procesamiento y análisis.

4.- Análisis de datos mediante Python
Se utilizó Python para el procesamiento, análisis y visualización de los resultados obtenidos en la simulación energética.

Se analizaron variables relacionadas con:

temperatura interior, horas de confort térmico, porcentaje de confort por zona térmica, y mejoras térmicas derivadas de las estrategias implementadas.


![imagen 1](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%201.png)
![imagen_2](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%202.png)


## Resultados:
1.-Análisis anual:

1.1 Temperaturas
* El incremento de la temperatura promedio anual para la VIVIENDA fue de 1.56 °C.

* La RECAMARA 2 registró el mayor incremento de la temperatura promedio anual, siendo esta de casi 3°C.


  ![imagen 3](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%203.png)
   ![imagen 5](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%205.png)

* Las temperaturas promedio anual mínimas en el caso base y con la aplicación de estrategias estuvieron ubicadas en el baño completo (4.1°C y 4.9°C ) mientras que las temperaturas promedio anual máximas estuvieron ubicadas en la COCINA (36.1°C y 36.5°C).

1.2 Confort térmico
Caso base (diagnóstico):

   ![imagen 4](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%204.png)
* Todas las zonas térmicas tienen menos del 45% de horas al año dentro del rango de confort y el resto, más de 55% se encuentran fuera del rango de confort, ya sea por encima de 27°C o por debajo de 21°C.

* En promedio, para la vivienda, el 41.76% de las horas en un año, se encuentran dentro de la zona de confort.

* En promedio, para la vivienda, el 58.24% de las horas en un año, se encuentran fuera de la zona de confort.

* La zona térmica con mayor porcentaje de horas con temperaturas en confort, es la COCINA con un 43.56% y la zona térmica con menor porcentaje con temperaturas en confort, es el baño completo con 36.18%.

Caso con Estrtategias bioclimáticas:

   ![imagen 4](https://github.com/Gina9310/Evaluaci-n-del-impacto-de-estrategias-bioclim-ticas-mediante-simulaci-n-energ-tica/blob/main/imagen%204.png)
* En promedio, para la vivienda, el 47.76% de las horas en un año, se encuentran dentro de la zona de confort.
* En promedio, para la vivienda, el 58.24% de las horas en un año, se encuentran fuera de la zona de confort
* En la vivienda, se logró un incremento del 5.73% de horas en confort, lo que equivale a 503 horas.
* La zona térmica con mayor porcentaje de horas con temperaturas en confort, es el SALA-PASILLO con un 54.15% y la zona térmica con menor porcentaje con temperaturas en confort, es el baño completo con 39.58%.

El efecto del rediseño de la ventana en la sala puede visualizarse en el incremento de horas en confort de esta área. De igual manera las 3 recamaras presentan un incremento de confort posterior a la construcción de tragaluces, favoreciendo la ganancia tanto de luz como de calor.

2.- Análisis mensual:
2.1 Temperaturas
Recamaras
las 3 recamaras tienen una tendencia de temperaturas similar, presentan temperaturas promedio mensual por debajo del rango de confort (21°C) de octubre a marzo, los meses de abril, junio, julio, agosto y septiembre muestran temperaturas promedio mensuales dentro del rango de confort. La temperatura mensual promedio más alta y fuera del rango de confort, se registran en el mes de mayo (27.2°C).

Las temperaturas mínimas y máximas, muestran un ligero incremento en la temperatura, en aquellos meses en los que la temperatura promedio mensual fueron temperaturas menores a 21°C (octubre-marzo).

Los incrementos de temperatura mensuales debido a la aplicación de estrategias bioclimáticas, muestra como las recamaras son las zonas térmicas con incrementos por arriba de 2°C. Los mayores incrementos son en los meses de noviembre a marzo por arriba de 2.5,

abril a septiembre los incrementos rondan por debajo de 2.5.

Los incrementos de temperatura mensuales debido a la aplicación de estrategias bioclimáticas, muestra como la cocina y el baño son las zonas térmicas con incrementos por debajo de 1°C.

## Recamara 2
Fue la ZT que mayor incremento de temperatura promedio anual presentó,

La temperatura máxima de 33.5 se presenta en el mes de junio pero que la temperatura mensual promedio máxima se registrada durante el mes de mayo siendo esta de 27.2°C.
Presenta los mayores incementos de temperatura los meses de febrero y marzo con 3.2 y 3.3 respectivamente.
El mes con menor incremento fue junio con 2.1 °C.
2.2 Confort térmico
La Estrategias bioclimáticas incrementan el % de confort en los mese de febrero, marzo, septiembre, octubre y noviembre, mientras que en los meses de abril a agosto el % de confort disminuye con la aplicación de estrategias bioclimáticas.

El incremento de horas de confort en meses fríos como septiembre, octubre, noviembre, diciembre-enero un poco y febrero es evidente, sin embargo nuevamente resalta la necesidad de mejorar las estrategias para evitar ganancia de calor en meses con temperaturas altas como lo son de abril a agosto, donde sin la aplicación de estrategias se llega a mayor % de confort.

Por otro lado, para ZT como el pasillo, sala y la cocina, la distribución de horas en confort tienen un mejor balance en meses con temperaturas más altas y con mejor desempñeo para el caso de aplicaciónde estrategias
