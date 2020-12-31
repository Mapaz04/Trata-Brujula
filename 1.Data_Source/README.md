# Fuentes de Datos

Para este proyecto se recolectaron una serie de indicadores relacionados a factores como pobreza, informalidad, densidad poblacional que pueden estar fuertemente relacionados a la Trata de Personas en el Perú.

La base de datos consultada fue la del Instituto Nacional de Estadística e Informática (INEI) y del [Sistema de Informacion Nacional para la Toma de Decisiones](https://systems.inei.gob.pe/SIRTOD), el cual es de acceso público. Se obtuvieron las cifras de estos indicadores para cada uno de los 25 departamentos del Perú dentro del periodo del 2016 al 2018.

Fueron elegidas estas fechas dado que, por fuente del Ministerio del Intenior con respecto a la Trata de personas (Variable dependiente), en el año 2016 se invirtió mayor presupuesto a la mitigación de este delito, por ende podría sesgar el modelo si se usaban datos menores a esa fecha.


#### Variable dependiente
1. Cantidad de denuncias de casos de Trata de Personas en el Perú (Casos intervenidos por el delito de trata de personas): Número de denuncias de Trata de Personas por departamento en Perú desde el 2016 al 2018.

#### Variables independientes
1. Acceso a servicios básicos - Agua potable (acceso-agua.csv): Indice de acceso a agua potable de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO
2. Población con al menos una necesidad básica insatisfecha (Al-menos-1-necesidad-no-satis.csv).Datos de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO
3. Tasa de analfabetismo (analfabetimos.csv): Tasa de analfabetismo de la población de 15 años a más de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO 
4. Años de estudio (educacion15amas.csv): Promedio de años de estudio alcanzado por la población de 15 y más años de edad, de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO
5. Empleo informal (empleoinformal.csv): Población ocupada por empleo informal en miles de personas, de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO
6. Incidencia de pobreza monetaria (Incidencia-pobreza.csv): Incidencia de la pobreza monetaria por grupos de departamentos según intervalos de confianza (puntos medios de los intervalos) desde el 2016 al 2018. Fuente: INEI - ENAHO 
7. Población por departamento (pob-total-estimada.csv):Población total estimada y proyectada a partir del Censo realizado el 2017 (Personas). Fuente: INEI - Censo Nacional de Población y Vivienda
8. Población con seguro de salud (poblacionconsegurosalud.csv):Porcentaje de la población afiliada a algún seguro de salud (Porcentaje respecto al total de la población), de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO
9. Tasa de denuncia por trata de personas (tasa-denuncia-delitos.csv): Tasa de denuncias de delitos (por 10,000 habitantes) de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - Registro Nacional de Denuncias de Delitos y Faltas (PNP) - Sistema de Denuncias Policiales (SIDPOL) 
10. Tasa de desempleo (tasadesempleo.xls.csv):Tasa de desempleo de la población (Porcentaje respecto al total de la población), de cada departamento del Perú desde el 2016 al 2018. Fuente: INEI - ENAHO 
11. Violencia física contra la mujer (violencia-fisica.csv): Violencia física contra la mujer ejercida alguna vez por parte del esposo o compañero, según ámbito geográfico (Porcentaje respecto al total de la población femenina), desde el 2016 al 2018. Fuente: INEI - ENDES  
12. Violencia psicológica contra la mujer (violencia-sicologica.csv): Violencia psicológica o verbal contra la mujer ejercida alguna vez por parte del esposo o compañero, según ámbito geográfico (Porcentaje respecto al total de la población femenina),desde el 2016 al 2018. Fuente: INEI - ENDES  

#### Limitaciones de los datos
En general la data que recopila en el Perú con respecto de la trata es escaza. Se recurrió al uso de de data oficial del estado ya que era la que estaba más estructurada y provenía en su mayoría de encuestas realizadas anualmente, con excepción de las denuncias de las que lleva el control el Ministerio Público. No obstante, se decidió solo usar el periodo de 3 años desde el 2016 al 2018 porque no se encontraron registros más actualizados de ciertos indicadores posteriores al 2018 y se toma como punto incial el año 2016 ya que , por fuente del Ministerio del Intenior con respecto a la Trata de personas (Variable dependiente), en el año 2016 se invirtió mayor presupuesto a la mitigación de este delito, por ende podría sesgar el modelo si se usaban datos menores a esa fecha. Además se decidió usar el nivel departamental, ya que una mayor desagregación hubiera resultado en la reducción significativa en los datos, con la ausencia de valores para múltiples localidades.
