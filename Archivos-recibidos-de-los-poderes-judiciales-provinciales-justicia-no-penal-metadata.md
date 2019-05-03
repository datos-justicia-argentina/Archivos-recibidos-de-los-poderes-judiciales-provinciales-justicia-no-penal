Datos recibidos de los poderes judiciales provinciales - Justicia no penal
==========================================================================

Este conjunto de datos contiene los archivos recibidos de los poderes judiciales referidos a causas no penales según lo establecido en el [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)., (tabla3, tabla3.1, tabla4, tabla4.1 y tabla4.2) y número de orden de la tabla dentro del envío.

http://datos.jus.gob.ar/dataset/datos-recibidos-de-los-poderes-judiciales-de-las-provincias-justicia-no-penal

Características
---------------

-   **Fecha de Primera Publicación:** 23/04/2019

-   **Tags o Etiquetas:** Buenos Aires, Catamarca, Chaco, Chubut, Ciudad Autónoma de Buenos Aires, Corrientes Córdoba, Entre Ríos Formosa, Jujuy, La Pampa, La Rioja, Mendoza, Misiones, Neuquén, Río Negro, Salta, San Juan, San Luis, Santa Cruz, Santa Fe, Santiago del Estero, Tierra del Fuego, Tucumán, actos procesales, casos, causas, código penal, delitos, instituciones, investigación penal preparatoria, poderes judiciales

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Justicia y Política Criminal. Programa Justicia Abierta

-   **Autor:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Responsable:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Archivos recibidos de los poderes judiciales provinciales - AAAA

-   **Nombre:** pj-no-penal-archivos-recibidos-AAAA.zip

-   **Descripción del contenido:** Contiene los archivos recibidos de los poderes judiciales referidos a causas no penales en 2018. El nombre de cada archivo corresponde al nombre de provincia, institución, fecha de envío, nombre de las tablas remitidas según [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf), (tabla3, tabla3.1, tabla4, tabla4.1 y tabla4.2) y número de orden de la tabla dentro del envío.

-   **Formato:** ZIP

-   **Rango temporal:** archivos recibidos por los poderes judiciales provinciales en el año AAAA

### Archivos del recurso

### Tabla3 - CAUSAS NO PENALES

- **Nombre del recurso:** nombre_provincia-pj-AAAAMMDD-tabla3-causas-no-penales-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_causa (string):** código que identifica la causa. Cada provincia usa su propio formato de identificación de causa

-   **materia (string):** indica la materia que le corresponde a la causa, según lo informado por la institución. Algunos ejemplos son: Civil/Laboral/Familia/Tributario Fiscal/Contencioso Administrativo, etc.

-   **id_circunscripcion (string):** indica la unidad geográfica en que está divida la institución en la que se inició la causa

-   **id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **fecha_inicio (date):** fecha en que se inició la causa. Tiene el formato AAAA-MM-DD

-   **objeto_litigio (string):** objeto por el cual se da inicio a la causa. Algunos ejemplos son: Amparo/Cobro de honorarios/Violencia familiar/Daños y perjuicios, etc.

-   **cantidad_actores (int):** indica la cantidad numérica de personas físicas o jurídicas que involucrados en la causa

-   **cantidad_demandados (int):** indica la cantidad numérica de personas físicas o jurídicas demandadas

### Tabla3-1 - CAUSAS NO PENALES - PERSONAS

- **Nombre del recurso:** nombre_provincia-pj-AAAAMMDD-tabla3-1-causas-no-penales-personas-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_causa (string):** código que identifica la causa. Cada provincia usa su propio formato de identificación de causa

-   **id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **persona_tipo (string):** indica el tipo de persona. Puede tomar los valores:

    -   Persona Física

    -   Persona Jurídica

-   **partes (string):** indica el rol procesal de las partes. Algunos ejempls son:  Actor/Demandado/Citado en garntía, etc.
	
-	**descripcion1 (string):** Para el caso de las personas físicas se solicitó se solicitó consignar la edad. En caso de una persona mayor de 65 años, se solicitó se solicitó consignar “65+”. Para el caso de personas jurídicas se solicitó se solicitó consignar el tipo de persona, con las siguientes categorías:
	
	-   Estado Nacional

    -   Estado Provincial

    -   Entes descentralizados Estado Nacional

    -   Entes descentralizados Estado Provincial

    -   Asociación Civil

    -   Asociación Sindical

    -   Fundación

    -   Sociedad Comercial

    -   Municipalidad

    -   Consorcio de Propietarios

    -   Otros
	
-	**descripcion2 (string):**	Para el caso de las personas físicas se solicitó se solicitó consignar el género, siendo “F” para femenino y “M” para masculino. Para el caso de personas jurídicas se solicitó se solicitó consignar con el número de CUIT
	
	### Tabla4 - CAUSAS NO PENALES - MOVIMIENTOS

- **Nombre del recurso:** nombre_provincia-pj-AAAAMMDD-tabla4-causas-no-penales-movimientos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso
	
-   **id_causa (string):** código que identifica la causa. Cada provincia usa su propio formato de identificación de causa	
	
-   **id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa	
	
-   **fecha_acto_procesal (date):**	fecha en la que se realiza el acto procesal. Tiene el formato AAAA-MM-DD

-   **acto_procesal (string):** descripción del acto procesal. Algunos ejemplos son: Audiencia/Autos para resolver/Providencia simple/Sentencia definitiva, etc.
	
-   **estado_procesal (string):** indica en que estado se encuentra el acto procesal. Algunos ejemplos son: Archivado/En trámite/Finalizado mediación/Finalizado conciliación, etc.
	
	### Tabla4-1 - CAUSAS NO PENALES - AUDIENCIAS

- **Nombre del recurso:** nombre_provincia-pj-AAAAMMDD-tabla4-1-causas-no-penales-audiencias-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso
	
-   **id_causa (string):** código que identifica la causa. Cada provincia usa su propio formato de identificación de causa	
	
-   **id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa
	
-   **fecha_convocatoria (date):** fecha establecida para la audiencia. Tiene el formato AAAA-MM-DD
	
-   **fecha_realizacion (date):** fecha en la que se realiza la audiencia. Tiene el formato AAAA-MM-DD

-   **tipo_audiencia (string):** indica el tipo de audiencia. Algunos ejemplos son: Preliminar/Vista de causa/Conciliación, etc.
	
-   **estado_audiencia (string):** indica el estado de la audiencia. Algunos ejemplos son: Iniciada y suspendida/Frustarada/Iniciada y concluida, etc.
	
	### Tabla4-2 - CAUSAS NO PENALES - RECURSOS

- **Nombre del recurso:** nombre_provincia-pj-AAAAMMDD-tabla4-2-causas-no-penales-recursos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso
	
-   **uosj_alzada (string):** tribunal que recibe un recurso para decidir algún aspecto de la causa
	
-   **id_causa_alzada (string):** número que le asigna a la causa el tribunal que actúa en alzada
	
-   **uosj_origen (string):** tribunal del que provine la causa motivo de un recurso
	
-   **id_causa_origen (string):** número que identifica la causa en el tribunal de origen

-   **descripcion_recurso (string):** descripción del recurso. Algunos ejemplos son: Recurso contra sentencias definitivas o interlocutorias con fuerza de definitiva/Recurso contra sentencias interlocutorias o incidentes/Recursos por regulación de honorarios, etc.
	
-   **fecha_acto_procesal (date):** fecha en la que se realiza el acto procesal. Tiene el formato AAAA-MM-DD
	
-   **acto_procesal (string):** descripción del acto procesal. Algunos ejemplos son: Audiencia/Autos para resolver/Providencia simple/Sentencia definitiva, etc.
	
-   **estado_procesal (string):** indica en que estado se encuentra el acto procesal. Algunos ejemplos son: Archivado/En trámite/Finalizado mediación/Finalizado conciliación, etc.	
	
### Índice de archivos recibidos de los poderes judiciales provinciales referidos a causas no penales - AAAA

-   **Nombre:** indice-archivos-recibidos-poder-judicial-no-penal-AAAA.csv

-   **Descripción del contenido:** Este recurso es un índice de los archivos recibidos de los poderes judiciales referidas a causas no penales en 2018 en el marco del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** archivos recibidos de los poderes judiciales provinciales en el año AAAA

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión I](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)
