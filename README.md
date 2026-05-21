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
