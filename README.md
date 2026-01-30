# EDA_Ocurrencias_Au_Estados_Unidos
Integrantes del equipo: Juan Morales, Sebastian Ruiz, Daniel Pareja

Dataset utilizado: CriticalMineralDepositsGeochemistry.csv

Origen dataset: Disponible en el sitio web Servicio Geologico Australiano (https://portal.ga.gov.au/)

Link para descarga del dataset: https://critical-minerals.prod-geoserver.gis.ga.gov.au/geoserver/wfs?request=GetFeature&service=WFS&version=1.1.0&typeName=cmmi:CriticalMineralDepositsGeochemistry&outputFormat=excel2007&srsName=EPSG:4326

Metodologia usada: Para el desarrollo del EDA se siguio principalmente la metodologia OSEMN, sin embargo, se incorporo el primer punto de la metologia CRISP-DM (Comprensión del Negocio)

## Otros datasets consultados

- Tarifas aplicadas de gas natural: https://www.datos.gov.co/Minas-y-Energ-a/Tarifas-aplicadas-de-Gas-Natural/ek3f-5wn4/about_data

- Llegadas, Nacimientos, Salidas, Liquidaciones, Cancelaciones y Renovaciones de Empresas en Sabaneta: https://www.datos.gov.co/Econom-a-y-Finanzas/Llegadas-Nacimientos-Salidas-Liquidaciones-Cancela/tnkn-egcp/about_data

## Comentarios

Se desarrollaron ejercicios de analisis exploratorios de datos sobre los 3 datasets consultados, se revisaron en equipo, y se eligio para presentacion el notebook __Actividad_01_EDA_Ocurrencias_Au_Estados_Unidos__. Para consulta se dejaron en el repositorio los otros 2 EDAs y en la carpeta archivos los 3 datasets.

### Datos de precios de gas

Los datos de Tarifas aplicadas de gas natural fueron extraídos de los datos abiertos de la Republica de Colombia, dónde se presentan los valores, en cantidad monetaria, de los cargos fijos, conexión, reconexión, precios, si se tiene un precio en un rango de 0-20 $m^3$ y que tarifa prima si se supera ese volumen de consumo.

### Datos de empresas Sabaneta

Los datos de Llegadas, Nacimientos, Salidas, Liquidaciones, Cancelaciones y Renovaciones de Empresas en Sabaneta fueron extraídos de los datos abiertos de la Republica de Colombia. Cuenta con campor relacionados a cantidad de empresas para el estado y año en particular, sector económico, estatus de las empresas, cantidad de empleos y activos.
