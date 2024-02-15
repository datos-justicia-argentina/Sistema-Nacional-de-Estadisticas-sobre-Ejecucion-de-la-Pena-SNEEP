Sistema Nacional de Estadísticas sobre Ejecución de la Pena - SNEEP
===================================================================

En este conjunto de datos se detallan los datos recopilados en el censo realizado sobre el total de la población detenida al día 31 de diciembre de cada año, en cada establecimiento de la República Argentina. 

La unidad de análisis son las personas alojadas en los establecimientos. 

El censo recaba la siguiente información sobre cada interno: edad, sexo, nacionalidad, estado civil, nivel de instrucción, situación laboral, lugar de residencia, jurisdicción judicial, situación legal, fecha de detención, fecha de condena, establecimiento de procedencia, tipo de delitos imputado, participación en trabajo remunerado, en actividades de capacitación laboral, en actividades recreativas, asistencia médica, vistas, alteraciones al orden, sanciones disciplinarias, calificaciones de conducta, tentativas de fugas o evasiones, tentativa de suicidios, lesiones recibidas, duración de la condena, reincidencia, régimen de progresividad, salidas transitorias, régimen de semilibertad, programe de prelibertad, prisión discontinua, semidetención, reducción de pena, mujeres alojadas con sus hijos.

http://datos.jus.gob.ar/dataset/sneep

Características
---------------
-	**Fecha de Primera Publicación:** 14/07/2016

-	**Tags o Etiquetas:** SNEEP, SPF, censos, cárceles, ejecución de la pena, establecimientos penitenciarios, personas privadas de la libertad, presos, prisiones

-	**Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Dirección Nacional de Política Criminal en Materia de Justicia y Legislación Penal

-	**Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Dirección Nacional de Política Criminal en Materia de Justicia y Legislación Penal

-	**Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Dirección Nacional de Política Criminal en Materia de Justicia y Legislación Penal

-	**Grupos:** Política Criminal

-	**Frecuencia de Actualización:** Anualmente

Recursos Disponibles
--------------------

### Sistema Nacional de Estadísticas sobre Ejecución de la Pena – SNEEP - AAAA

-	**Nombre del archivo:** sneep-AAAA.csv (AAAA: corresponde el año del censo publicado)

-	**Descripción del contenido:** el Sistema Nacional de Estadísticas sobre Ejecución de la Pena SNEEP tiene como fuentes a todas las unidades de detención penal, dependientes del sistema federal y provincial. Constituye una fuente de conocimiento en cuanto a características de la población privada de la libertad

-	**Formato:** CSV delimitado por comas, codificado en UTF-8

-	**Rango temporal:** censos - SNEEP - desde el año 2002 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-	**censo_anio (int):** año en el que se realizó el censo

-	**provincia_sneep_id (int):** código de provincia SNEEP donde se encuentra el establecimiento penitenciario censado

-	**provincia_descripcion (string):** nombre de la provincia donde se encuentra el establecimiento penitenciario

-	**establecimiento_id (int):** código del establecimiento penitenciario

-	**establecimiento_descripcion (string):** nombre del establecimiento penitenciario

-	**edad (int):** edad del interno a la fecha del cierre del relevamiento

-	**genero_id (int):** género del interno (Código)

-	**genero_descripcion (string):** género del interno. Categorías por año:
  
    -   2002 al 2014: Mujer - Varón

    -   2015 al 2019: Mujer - Varón - Trans Mujer/Travesti

    -   2020 al 2021: Mujer - Varón - Trans Mujer/Travesti - Trans Varón
 
    -   2022: Mujer - Varón - Trans Mujer/Travesti - Trans Varón - No Binario

-	**nacionalidad_id (int):** código de nacionalidad

-	**nacionalidad_descripcion (string):** descripción de la nacionalidad del interno

-	**estado_civil_id (int):** código de estado civil

-	**estado_civil_descripcion (string):** descripción del estado civil que cada interno reviste al día de corte del relevamiento

-	**nivel_instruccion_id (int):** código de nivel de instrucción

-	**nivel_instruccion_descripcion (string):** descripción del nivel de educación alcanzado al ingreso del interno al establecimiento

-	**ultima_situacion_laboral_id (int):** código de la situación laboral

-	**ultima_situacion_laboral_descripcion (string):** descripción de la situación laboral que cada interno registra a su ingreso al establecimiento

-	**capacitacion_laboral_al_ingresar_id (int):** código de la situación laboral al ingresar

-	**capacitacion_laboral_al_ingresar_descripcion (string):** descripción de la capacitación laboral que tuviere cada interno a su ingreso al establecimiento

-	**ultimo_lugar_residencia_id (int):** código del último lugar de residencia

-	**ultimo_lugar_residencia_descripcion (string):** descripción de último lugar de residencia (Rural / Urbano) de acuerdo al último domicilio que cada interno registre a su ingreso al establecimiento

-	**ultima_provincia_residencia_sneep_id (int):** código de provincia SNEEP donde el interno haya tenido su último domicilio

-	**ultima_provincia_residencia_descripcion (string):** nombre de la provincia donde cada interno haya tenido su último domicilio

-	**jurisdiccion_id (int):** código de la jurisdicción judicial interviniente en la causa penal motivo de la detención

-	**jurisdiccion_descripcion (string):** descripción de jurisdicción judicial interviniente en la causa penal motivo de la detención

-	**situacion_legal_id (int):** código de la situación legal

-	**situacion_legal_descripcion (string):** descripción de la situación legar (Condenado / Procesado / Contraventor / Inimputable)

-	**fecha_detencion (date):** fecha de detención

-	**fecha_condenado (date):** fecha de sentencia

-	**establecimiento_procedencia_id (int):** código de procedencia del interno

-	**establecimiento_procedencia_descripcion (string):** descripción de la procedencia del interno. Se entenderá por “Ingreso directo” aquellos casos en que el interno ingresa directamente desde sede judicial o cuando el mismo provenga de una institución policial en la que haya permanecido hasta cuatro (4) días

-	**delito1_id (int):** código del tipo de delito

-	**delito1_descripcion (string):** descripción del tipo de delito/s que se imputa/n en la/s causa/s por la cual el interno ha ingresado al establecimiento. Por razones operativas sólo se consignan hasta cinco (5) delitos, eligiendo los de mayor gravedad

-	**delito2_id (int):** código de delito

-	**delito2_descripcion (string):** descripción del tipo de delito

-	**delito3_id (int):** código de delito

-	**delito3_descripcion (string):** descripción del tipo de delito

-	**delito4_id (int):** código de delito

-	**delito4_descripcion (string):** descripción del tipo de delito

-	**delito5_id (int):** código de delito

-	**delito5_descripcion (string):** descripción del tipo de delito

-	**horas_trabajo_remunerado_id (int):** se consigna si el interno ha realizado trabajos remunerados dentro o fuera del establecimiento, según la carga horaria, durante el año (Código)

-	**horas_trabajo_remunerado_descripcion (string):** se consigna si el interno ha realizado trabajos remunerados dentro o fuera del establecimiento, según la carga horaria, durante el año (Descripción)

-	**participacion_programa_laboral (int):** se consigna si el interno ha participado en forma regular de un programa de formación o de capacitación laboral durante el año (1 – si / 2 - no / 0 - sin datos)

-	**participacion_programa_educativo_id (int):** nivel de educación que se encuentre cursando el interno a la fecha del corte (Código)

-	**participacion_programa_educativo_descripcion (string):** descripción del nivel de educación que se encuentre cursando el interno a la fecha del corte

-	**participacion_actividades_deportivas (int):** se consigna si el interno ha participado  regularmente (una vez por mes en forma continua o 12 veces al año en forma. discontinua) de actividades recreativas y deportivas en el último año (0 – no / 1 - si)

-	**recibio_atencion_medica_ult_anio (int):** se consigna si el interno recibió asistencia médica (consultas ambulatorias de clínica y de otras especialidades tanto por demanda espontánea como por citación o por guardia) durante el último año (0 – no / 1 - si)

-	**recibio_atencion_medica_ult_anio_descripcion (int):** se consigna si el interno recibió asistencia médica debido a alguna enfermedad preexistente (consultas ambulatorias de clínica y de otras especialidades tanto por demanda espontánea como por citación o por guardia) durante el último año (toma valores SI - descripción de la enfermedad / NO - en caso de que no hubiera consulta/enfermedad). **Este campo sólo está disponible a partir del año 2016**

-	**recibio_visitas_ultimo_anio (int):** se consigna si el interno mantuvo contactos sociales con personas ajenas a la institución (1 – si / 2 - no / 0 - sin datos)

-	**participo_alteracion_orden_ult_anio_id (int):** se consigna la participación en alteraciones del orden (Código)

-	**participo_alteracion_orden_ult_anio_descripcion (string):** se consigna la participación en alteraciones del orden (Descripción). En caso de que corresponda más de uno se indica el que involucre la situación de mayor gravedad

Alteraciones del orden: todos aquellos disturbios de tal magnitud que hayan dado lugar a un sumario administrativo y/o a intervención judicial, y en los que se hayan producido además: Daños, cuando se hubieren afectado o deteriorado bienes del Estado o de terceros; Rehenes, cuando se privare ilegítimamente de la libertad a otra/s persona/s a condición de lograr el cumplimiento de exigencias de quien/es la/s retiene/n; Heridos – muertos, cuando se lesione la integridad psico-física de las personas o se produzcan fallecimientos.

-	**tipo_infraccion_disciplinaria_id (int):** código de tipo de infracción disciplinaria

-	**tipo_infraccion_disciplinaria_descripcion (string):** descripción del tipo de infracción disciplinaria

-	**sancion_aplicada_id (int):** código del tipo de sanción aplicada

-	**sancion_aplicada_descripcion (string):** descripción del tipo de sanción aplicada

-	**calificacion_conducta_id (int):** calificación de conducta (Código)

-	**calificacion_conducta_descripcion (string):** descripción de la calificación de la conducta correspondiente al último trimestre del año

-	**tentativa_fugas_evasiones_id (int):** se consigna tentativa de fuga y evasiones (Código)

-	**tentativa_fugas_evasiones_descripcion (string):** se consigna la tentativa de evasión (aquellos casos en que la persona, hallándose legalmente detenida, saliera del establecimiento utilizando violencia en las personas o fuerza en las cosas) o fuga (aquellos casos en que la persona, hallándose legalmente detenida, saliera del establecimiento sin autorización legal y/o reglamentaria)

-	**tentativa_suicidio (int):** se consigna si el interno tuvo intento de suicidio en el último año (1 – si / 2 - no / 0 - sin datos)

-	**fue_lesionado_id (int):** se consigna si el interno fue lesionado en el establecimiento en el último año (Código)

-	**fue_lesionado_descripcion (string):** se consigna si el interno fue lesionado en el establecimiento en el último año según el resultado de las actuaciones que se derivaron del hecho

-	**duracion_condena_anios (int):** cantidad de años de condena según testimonio de sentencia

-	**duracion_condena_meses (int):** cantidad de años de condena según testimonio de sentencia si el interno ha sido condenado a pena privativa de libertad divisible. Se indica cantidad  de años y meses

-	**duracion_condena_rango (int):** si la situación legal del interno es condenado toma valores: 1) Hasta 3 años; Valor 2) De 3 6 años; Valor 3) De 6 a 9 años; 4) De 9 a 12 años; 5) De 12 a 15 años; 6) De 15 a 18 años; 7) Más de 18 años; 8) Sin datos. Si la situación legal del interno es procesado, inimputable o contraventor toma el valor 0. **Este campo sólo está disponible a partir del año 2016**

-	**tipo_condena (int):** se consigna en caso que el interno haya sido condenado a prisión o reclusión perpetua (1 – si / 2 - no / 0 - sin datos)

-	**es_reincidente_id (int):** código de tipo de reincidencia

-	**es_reincidente_descripcion (string):** descripción de tipo de reincidencia: 
      Primario: internos que han sido condenados por primera vez
      Reiterante: es un concepto criminológico, aquellos internos que han cometido varios hechos, pero que no han sido declarados reincidentes
      Reincidente: internos en cuyo testimonio de sentencia obre declaración de Reincidencia a tenor de las disposiciones del Art. 50 del Código Penal
      Reincidente múltiple: internos en cuyo testimonio de sentencia obre declaración de reincidencia y a los que se les haya impuesto la Medida de Seguridad prevista en el Art. 52 del Código Penal (Reclusión por tiempo indeterminado)

-	**tiene_periodo_progresividad_id (int):** se consigna el Período de la Progresividad del régimen penitenciario al que se encuentra incorporado (Código)

-	**tiene_periodo_progresividad_descripcion (string):** se consigna el Período de la Progresividad del régimen penitenciario al que se encuentra incorporado, a la fecha del corte. El régimen penitenciario aplicable al condenado, cualquiera fuere la pena Impuesta, se caracterizará por su progresividad y constará de: a) Periodo de Observación; b) Periodo de Tratamiento; c) Periodo de Prueba; d) Periodo de Libertad Condicional

-	**reparticion_id (int):** código de repartición

-	**reparticion_descripcion (string):** descripción de la repartición (Federal / Provincial)

-	**tuvo_salidas_transitorias_id (int):** se consigna si el interno ha gozado o goza de salidas transitorias durante el año (Código)

-	**tuvo_salidas_transitorias_descripcion (string):** se consigna si el interno ha gozado o goza de salidas transitorias durante el año (Descripción)

-	**incorporado_reg_semi_libertad_id (int):** se indica si el interno está o estuvo incorporado al régimen de semilibertad (Código)

-	**incorporado_reg_semi_libertad_descripcion (string):** se indica si el interno está o estuvo incorporado al régimen de semilibertad durante el año (Descripción)

-	**participa_programa_pre_libertad (int):** se consigna si el interno participa o participó durante el año de un programa de prelibertad (1 – si / 2 - no / 0 - sin datos)

-	**participa_programa_prision_discontinua_id (int):** se consigna si el interno se encuentra o se encontró durante el año cumpliendo la pena bajo la modalidad de Prisión Discontinua (Código)

-	**participa_programa_prision_discontinua_descripcion (string):** se consigna si el interno se encuentra o se encontró durante el año cumpliendo la pena bajo la modalidad de Prisión Discontinua (Descripción)

-	**participa_programa_semi_detencion_id (int):** se consigna si el interno se encuentra o se encontró durante el año cumpliendo la pena bajo la modalidad de Semidetención (Código)

-	**participa_programa_semi_detencion_descripcion (string):** se consigna si el interno se encuentra o se encontró durante el año cumpliendo la pena bajo la modalidad de Semidetención

-	**tuvo_reduccion_pena_id (int):** se consigna la reducción de pena que hubiera otorgado el poder ejecutivo (Código)

-	**tuvo_reduccion_pena_descripcion (string):** se consigna la reducción de pena que hubiera otorgado el poder ejecutivo (Descripción) 

-	**mujer_tiene_hijos_intramuro (string):** sólo para mujeres, se consigna si tiene hijos alojados con ella (1 – si / 2 - no / 0 - sin datos)

-	**provincia_id (string):** código de provincia según codificación de INDEC donde se encuentra el establecimiento penitenciario censado (hasta 05/2019 nombre campo provincia_indec_id)

-	**ultima_provincia_residencia_id (string):** código de provincia según codificación de INDEC donde el interno haya tenido su último domicilio

### Servicio penitenciario censo (series)

-	**Nombre del archivo:** servicio-penitenciario-censo-series.csv

-	**Descripción del contenido:** Este recurso contiene las series de tiempo sobre personas privadas de su libertad en los servicios penitenciarios federales y provinciales, correspondientes a los censos anuales realizados a partir del año 2002, clasificados por provincia y situación legal (condenados, procesados y otra situación legal). Incluye total país por cada una de las situaciones legales.

-	**Formato:** CSV delimitado por comas, codificado en UTF-8

-	**Rango temporal:** series de tiempo de los censos - SNEEP - desde el año 2002 hasta la fecha consignada como "Datos actualizados al"

### Sistema Nacional de Estadísticas sobre Ejecución de la Pena – SNEEP - AAAA-AAAA (por año)

- **Nombre:** sneep-AAAA-AAAA.zip

- **Descripción del contenido:** archivo comprimido con los censos del Sistema Nacional de Estadísticas sobre Ejecución de la Pena – SNEEP, correspondientes a los años AAAA-AAAA (desde-hasta), organizados en archivos anuales.

- **Formato:** ZIP

### Sistema Nacional de Estadísticas sobre Ejecución de la Pena – SNEEP - AAAA-AAAA (unificado)

- **Nombre:** sneep-unificado-AAAA-AAAA.zip

- **Descripción del contenido:** archivo comprimido con los censos del Sistema Nacional de Estadísticas sobre Ejecución de la Pena – SNEEP, correspondientes a los años AAAA-AAAA (desde-hasta), organizados en un archivo unificado.

- **Formato:** ZIP

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Estadísticas de Política Criminal - Filtrado interactivo SNEEP](https://www2.jus.gov.ar/dnpc/)

[Informes Sneep 2002 - 2020](https://www.argentina.gob.ar/justicia/politicacriminal/estadisticas/sneep)

Esta tarea se lleva a cabo en el marco de lo dispuesto por la [Ley Nº 25.266](http://servicios.infoleg.gob.ar/infolegInternet/anexos/60000-64999/63666/norma.htm) que faculta a la Dirección a requerir información estadística a diferentes organismos oficiales con el fin de confeccionar los informes correspondientes (Estadísticas SNEEP).

La Base de Datos del SNEEP no incluye los registros sobre la cantidad de internos que se encuentran bajo régimen de Monitoreo Electrónico en la Provincia de Buenos Aires. Estos valores son provistos por la Dirección General de Régimen del Servicio Penitenciario de la Provincia de Buenos Aires y son agregados manualmente a los informes finales.

Bibliografía 

[“Una gestión penitenciaria integral”](http://www.jus.gob.ar/media/1126013/Una_Gestion_Penitenciaria_Integral_SNEEP.pdf), Editorial Infojus, 2011, Dirección Nacional de Política Criminal.

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 986 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2016-986-E-APN-MJ.pdf), del 26 de Octubre de 2016.

