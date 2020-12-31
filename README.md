# DataJam-Projects

Este es un repositorio para el proyecto “Trata Brújula” sobre la ubicación/identificación de las zonas vulnerables a la trata de personas en el Perú. Incluye toda la data e investigación utilizada para su elaboración, así como la descripción detallada del proyecto.
Este repositorio tiene las siguientes carpetas:
1. Data source
2. Pitch
3. Project code


# Problem Statement

En el Perú existen pocos recursos y políticas públicas para la lucha contra la trata de personas. En el Plan Nacional contra la Trata de Personas 2017-2021, se identifica, entre otros factores, que existe una deficiente articulación interinstitucional, un débil sistema de prevención y que se carecen de los recursos suficientes para enfrentar este delito. 

En ese contexto, es esencial una adecuada gestión de los recursos e implementación de las políticas públicas dando prioridad a las zonas más vulnerables a la trata de personas en nuestro país. Precisamente, uno de los objetivos del mencionado Plan Nacional es reducir los factores de riesgo frente al delito de trata de personas, en especial, en las zonas de mayor prevalencia.

Para distribuir de manera eficiente y focalizada los recursos del Estado a las zonas más vulnerables de trata de personas, no es solo necesario conocer fríamente cuántas denuncias existen por Departamentos o Regiones, sino también conocer y establecer una relación con otros indicadores económicos y sociales que puedan explicar este fenómeno.


# Objective

Ante la falta de un método integral que identifique las zonas más vulnerables, "Trata Brújula" es un modelo de Machine Learning basado en Redes Neuronales que permite, a partir de distintos indicadores desagregados por Departamentos y de diferentes años, predecir la cantidad de denuncias por Departamento de Perú, además de conocer los indicadores que más peso tienen en el comportamiento de la Trata de Personas. 

La información obtenida servirá de guía a las autoridades competentes del Estado para una mejor gestión de los recursos e implementación de políticas públicas preventivas contra la trata de personas. Además, será de utilidad para los stakeholders interesados en contribuir a la lucha contra este delito en el país. 


# Solution/Data use case description

Ante la problemática antes descrita, en el presente proyecto se desarrolla un modelo de Machine Learning basado en Rede Neuronales que permite encontrar la relación entre los indicadores mostrados en [Datasets](https://github.com/TraffikAnalysisHub/Trata-Brujula/tree/master/1.Data_Source) y su impacto en el comportamiento de la cantidad de denuncias de trata de personas.

De esta forma, el modelo obtenido nos permite predecir la cantidad de denuncias de Trata de Personas a partir de indicadores economicos y sociales que podrían, a simple vista, no estar relacionados directamente. Esto es de gran utilidad pues ayudar al Estado a prever la cantidad de posibles víctimas e identificar los departamentos más vulnerables y así, focalizar los esfuerzos para poder combatir el delito.

Para el desarrollo se tomaron en cuenta datos de diferentes indicadores económicos y sociales desde 2016 al 2018 de distintos Departamentos del Perú, los cuales sirvieron de input para los 3 modelos distintos de Redes Neuronales que implementamos, los cuales tuvieron performance similares y se pudo obtener la función que permite obtener la cantidad de denuncias por trata por cada departamento a partir de estos indicadores antes mencionados.

Cabe resaltar que el mejor performance obtenido fue del 34% de error, el cual puede ser mejorado a partir del uso de más años de historia en los indicadores (por ejemplo, desde el 2014) y el uso de otras variables de entrada variables de entrada (como tasa de discriminación, explotación sexual, tasa de violaciones, migración, etc).


# Pitch

[Trata Brujula: Pitch](https://drive.google.com/drive/folders/1IWDHc62BIKwev4xLysQqwsHa7A-zATJO?usp=sharing)


# Datasets

[Trata Brujula: Explicacion Datasets](https://github.com/TraffikAnalysisHub/Trata-Brujula/blob/master/1.Data_Source/README.md#fuentes-de-datos)

# Project Code

[Trata Bujula: Code](https://github.com/TraffikAnalysisHub/Trata-Brujula/tree/master/3.Project_Code)

