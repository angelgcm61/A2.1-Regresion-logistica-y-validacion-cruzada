# A2.1-Regresion-logistica-y-validacion-cruzada

En este proyecto analizaremos la base de datos de la INEGI ya limpiados y eliminado variables inecesarias que consta de los vehiculos en circulacion del año 2024 al rededor de los 32 estados de mexico.
Nos centraremos en hacer una regresion logistica para clasificar la variable AUTOS_PARTICULARES para saber como clasificarlos dependiendo de la cantidad, si es superior a su promedio o no y a su vez ver que tan eficas es y exacto es el modelo que obendremos para al final analizar las variables y ver que tanto y como afecta al modelo.

Se cuenta con los siguientes datos
- ID_ENTIDAD: Clave de la entidad federativa de México, va del 1 al 32 respresentando cada estado de México.
- AUTO_OFICIAL: Autos que cuantan con hasta 7 asientos son utilizados por los organismos gubernamentales en el municipio.
- AUTO_PUBLICO: Autos que cuantan con hasta 7 asientos son utilizados como servicios para el traslado de personas, bienes o mercancia en el municipio.
- AUTO_PARTICULAR: Autos que cuantan con hasta 7 asientos son de la propiedad de cada persona en el municipio.
- CAM_PAS_OFICIAL: autobuses urbanos y suburbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos, cuyas unidades son utilizadas por los organismos gubernamentales para satisfacer sus propios requerimientos y/o atender las necesidades de la población.
- CAM_PAS_PUBLICO: Autobuses urbanos y suburbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos, cuyas unidades son utilizadas por el publico en general como un servicio.
- CAM_PAS_PARTICULAR: Autobuses urbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos. Las unidades son destinadas al autotransporte de pasajeros o bienes por cuenta propia.
- CYC_CARGA_OFICIAL: Camiones de carga diseñados para el remolque que son utilizadas por los organismos gubernamentales.
- CYC_CARGA_PUBLICO: Camiones de carga diseñados para el remolque que son utilizadas como servicio para el traslado de bienes o mercancías.
- CYC_CARGA_PARTICULAR: Camiones de carga diseñados para el remolque que son destinadas al autotransporte de bienes o mercancías por cuenta propia.
- MOTO_OFICIAL: Vehiculos automotor de dos, tres o cuatro ruedas, utlizadas por los organmismos gubernamentales.
- MOTO_DE_ALQUILER: Vehiculos automotor de dos, tres o cuatro ruedas, que son utilizadas por el público en general como un servicio. 
- MOTO_PARTICULAR: Vehiculos automotor de dos, tres o cuatro ruedas, destinadas al autotransporte de pasajeros o bienes.
  
Los documentos son:
- [Reporte en formato html](./A2_1_Regresion_logistica_y_validacion_cruzada.html)
- [Reporte en formato ipynb](./A2_1_Regresion_logistica_y_validacion_cruzada.ipynb)
- [Base de datos](./P1-Vehiculos-en-Circulacion-Limpia.csv)
- [Diccionario de los datos](./diccionario_datos_vmrc_anual_1980_2024.csv)
