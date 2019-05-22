Archivos recibidos de los poderes judiciales provinciales - Justicia no penal
==========================================================================

Este conjunto de datos contiene los archivos recibidos de los poderes judiciales referidos a causas no penales según lo establecido en el [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)., (tabla3, tabla3.1, tabla4, tabla4.1 y tabla4.2) y número de orden de la tabla dentro del envío.

http://datos.jus.gob.ar/dataset/archivos-recibidos-de-los-poderes-judiciales-de-las-provincias-justicia-no-penal

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

[Código Civil y Comercial de la Nación - Ley 26.994](http://www.saij.gob.ar/26994-nacional-codigo-civil-comercial-nacion-lns0005965-2014-10-01/123456789-0abc-defg-g56-95000scanyel?&o=1&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=103)

[Código Procesal Civil y Comercial de la Nación - Ley 17.454](http://www.saij.gob.ar/17454-nacional-codigo-procesal-civil-comercial-nacion-lns0004592-1981-08-18/123456789-0abc-defg-g29-54000scanyel)

[Código Procesal Civil y Comercial de la provincia de Buenos Aires - Decreto Ley 7.425](http://www.saij.gob.ar/7425-local-buenos-aires-codigo-procesal-civil-comercial-buenos-aires-lpb0007425-1968-09-19/123456789-0abc-defg-524-7000bvorpyel)

[Código Procesal Civil y Comercial de la provincia de Catamarca (T.O. 2008) - Ley 2.339](http://www.adepra.org.ar/wp-content/uploads/2016/11/cpc-catamarca.pdf)

[Código Procesal Civil y Comercial de la provincia de Córdoba - Ley 8.465](http://www.saij.gob.ar/8465-local-cordoba-codigo-procesal-civil-comercial-provincia-cordoba-lpo0008465-1995-04-27/123456789-0abc-defg-564-8000ovorpyel)

[Código Procesal Civil y Comercial de la provincia de Corrientes - Decreto Ley 14](http://www.saij.gob.ar/14-local-corrientes-codigo-procesal-civil-comercial-corrientes-lpw0000014-2000-03-21/123456789-0abc-defg-410-0000wvorpyel)

[Código Procesal Civil y Comercial de la provincia del Chaco - Ley 2.559](http://www.saij.gob.ar/2559-local-chaco-codigo-procesal-civil-comercial-provincia-chaco-lph0002559-2016-12-19/123456789-0abc-defg-955-2000hvorpyel?&o=0&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo/C%F3digo%20Procesal%20Civil%20Comercial%0A%09%09%09%09%09%09&t=20)

[Código Procesal Civil y Comercial de la provincia de Chubut - Ley XIII - N° 5 (Antes Ley 2.203)](http://www.saij.gob.ar/5-local-chubut-codigo-procesal-civil-comercial-chubut-lpu1000005-2010-05-06/123456789-0abc-defg-500-0001uvorpyel?&o=2&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo/C%F3digo%20Procesal%20Civil%20Comercial%0A%09%09%09%09%09%09&t=20)

[Código Procesal Civil y Comercial de la provincia de Entre Ríos - Ley 4.870](http://www.saij.gob.ar/4870-local-entre-rios-codigo-procesal-civil-comercial-entre-rios-lpe0004870-1970-04-06/123456789-0abc-defg-078-4000evorpyel)

[Código Procesal Civil y Comercial de la provincia de Formosa - Ley 1.445](http://www.saij.gob.ar/1445-local-formosa-codigo-procesal-civil-comercial-formosa-lpp1001445-2002-11-14/123456789-0abc-defg-544-1001pvorpyel?&o=28&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=104)

[Código Procesal Civil y Comercial de la provincia de Jujuy - Ley 1.967](http://www.saij.gob.ar/1967-local-jujuy-codigo-procesal-civil-provincia-jujuy-lpy0001967-1949-07-21/123456789-0abc-defg-769-1000yvorpyel)

[Código Procesal Civil y Comercial de la provincia de La Pampa - Ley 1.828](http://www.saij.gob.ar/legislacion/ley-la_pampa-1828-codigo_procesal_civil_comercial.htm)

[Código Procesal Civil y Comercial de la provincia de La Rioja - Ley 1.575](http://www.saij.gob.ar/1575-local-rioja-codigo-procesal-civil-comercial-rioja-lpf0001575-1950-09-29/123456789-0abc-defg-575-1000fvorpyel)

[Código Procesal Civil, Comercial y Tributario de la provincia de Mendoza - Ley 9.001](http://www.saij.gob.ar/9001-local-mendoza-codigo-procesal-civil-comercial-tributario-provincia-mendoza-lpm0009001-2017-08-30/123456789-0abc-defg-100-9000mvorpyel)

[Código Procesal Civil, Comercial, de Familia y Violencia Familiar de la provincia de Misiones - Ley XII - NRO. 27](http://www.saij.gob.ar/27-local-misiones-codigo-procesal-civil-comercial-familia-violencia-familiar-provincia-misiones-lpn0005366-2013-10-10/123456789-0abc-defg-663-5000nvorpyel)

[Código Procesal Civil y Comercial de la provincia de Neuquén- Ley 912](http://www.saij.gob.ar/912-local-neuquen-codigo-procesal-civil-comercial-neuquen-lpq0000912-1975-10-24/123456789-0abc-defg-219-0000qvorpyel)

[Código Procesal Civil y Comercial de la provincia de Río Negro - Ley 4.142](http://www.saij.gob.ar/4142-local-rio-negro-codigo-procesal-civil-comercial-provincia-rio-negro-lpr2004142-2011-08-11/123456789-0abc-defg-241-4002rvorpyel)

[Código Procesal Civil y Comercial de la provincia de Salta - Ley 5.233](http://www.saij.gob.ar/5233-local-salta-codigo-procesal-civil-comercial-provincia-salta-lpa0005233-1978-01-30/123456789-0abc-defg-332-5000avorpyel)

[Código Procesal Civil, Comercial y Minería de la provincia de San Juan - Ley 988 – O](http://www.saij.gob.ar/988-local-san-juan-codigo-procesal-civil-comercial-mineria-san-juan-lpj1500988-2014-11-19/123456789-0abc-defg-889-0051jvorpyel?&o=1&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo/C%F3digo%20Procesal%20Civil%20Comercial%0A%09%09%09%09%09%09&t=20)

[Código Procesal Civil y Comercial de la provincia de San Luis - Ley VI-0150](http://www.saij.gob.ar/150-local-san-luis-codigo-procesal-civil-comercial-provincia-san-luis-lpd1000150-2004-04-28/123456789-0abc-defg-051-0001dvorpyel)

[Código Procesal Civil y Comercial de la provincia de Santa Cruz - Ley 1.418](http://www.saij.gob.ar/legislacion/ley-santa_cruz-1418-codigo_procesal_civil_comercial.htm)

[Código Procesal Civil y Comercial de la provincia de Santa Fe - Ley 136](http://www.saij.gob.ar/5531-local-santa-fe-codigo-procesal-civil-comercial-lps0000136-1961-10-30/123456789-0abc-defg-631-0000svorpyel) y [Modificación de los Artículos 232, 233, 236, 241, 244 y 333 - Ley 13.615]( http://www.saij.gob.ar/13615-local-santa-fe-modificacion-codigo-procesal-civil-comercial-plazo-caducidad-proceso-notificacion-costas-computo-plazo-caducidad-para-procesos-modificacion-articulos-232-233-236-241-244-333-lps0013615-2016-12-22/123456789-0abc-defg-516-3100svorpyel)

[Código Procesal Civil y Comercial de la provincia de Santiago del Estero - Ley 3.534](http://www.saij.gob.ar/legislacion/ley-santiago_del_estero-3534-codigo_procesal_civil_comercial.htm)

[Código Procesal Civil y Comercial de la provincia de Tucumán - Ley 6.176](http://www.saij.gob.ar/6176-local-tucuman-codigo-procesal-civil-comercial-tucuman-lpt0006176-1991-01-07/123456789-0abc-defg-671-6000tvorpyel)

[Código Procesal Civil, Comercial, Laboral, Rural y Minero de la provincia de Tierra del Fuego - Ley 147](http://www.saij.gob.ar/147-local-tierra-fuego-codigo-procesal-civil-comercial-laboral-rural-minero-lpv0000646-1994-07-01/123456789-0abc-defg-646-0000vvorpyel)
