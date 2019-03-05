+++
date = "2018-01-28T18:14:07Z"
draft = false
title = "Ver Archivos con Datos de Observaciones"

+++

<p style='text-align: justify;'>
Se colectarán tablas con registros de observaciones y/o colectas. Los datos a compartir deben tener como mínimo especie, fecha y lugar de colecta y pueden ser de dos tipos:
</p>


## 1. Tablas con registros individuales  

<p style='text-align: justify;'>
Las tablas contendrán campos relativos a la especie registrada, la localidad y fecha de colecta e información sobre su colector y lugar de almacenamiento. Cada fila en un archivo representa un registro completo y las columnas representan todos los parámetros que componen el registro (formato de hoja de cálculo).
</p>


## 2. Lista de especies

<p style='text-align: justify;'>
Dado que los investigadores pueden tener sus datos en este formato, además de tablas con registros individuales, se aceptarán registros en listas. En este caso el archivo será un inventario de organismos para un mismo punto geográfico o varias coordenadas, con una fecha de colecta. Una vez adaptados los archivos, los parámetros a ser completados para estos registros serán los mismos que para las tablas.
</p>  

<br />
Todos los datos serán luego sistematizados utilizando las siguientes columnas (parámetros) [^1]:  
<br />


| Term 	| Reference 	|
|----------------------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| scientificName 	| The full scientific name with genus and specific epithet. 	|
| vernacularName 	| Common or vernacular name in Uruguay. 	|
| kingdom 	| The full scientific name of the kingdom in which the taxon is classified. 	|
| phylum 	| The full scientific name of the phylum or division in which the taxon is classified. 	|
| class 	| The full scientific name of the class in which the taxon is classified. 	|
| order 	| The full scientific name of the order in which the taxon is classified. 	|
| family 	| The full scientific name of the family in which the taxon is classified. 	|
| countryCode 	| The standard code for the country in which the Location occurs. Uruguay: UY. 	|
| locality 	| The specific description of the place. 	|
| decimalLatitude 	| The geographic latitude (in decimal degrees). 	|
| decimalLongitude 	| The geographic longitude (in decimal degrees). 	|
| locationAccordingTo 	| Information about the source of this Location information. 	|
| eventDate 	| The date when the event was recorded. Format: dd-mm-yyyy. 	|
| year 	| The four-digit year in which the Event occurred. Format: yyyy. 	|
| month 	| The ordinal month in which the Event occurred. Format: mm. 	|
| day 	| The integer day of the month on which the Event occurred. Format: dd. 	|
| basisOfRecord 	| The specific nature of the data record. 	|
| institutionCode 	| The name (or acronym) in use by the institution having custody of the object(s) or information referred to in the record. 	|
| collectionCode 	| The name or acronym identifying the collection or data set from which the record was derived. 	|
| catalogNumber 	| An identifier (preferably unique) for the record within the data set or collection. 	|
| recordedBy 	| A list (concatenated and separated) of names of people, groups, or organizations responsible for recording the original Occurrence. 	|
| identifiedBy 	| A list (concatenated and separated) of names of people, groups, or organizations who assigned the Taxon to the subject. 	|
| iucnStatus 	| IUCN red list category of the taxon at the Global level 	|
| associatedReferences 	| A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the Occurrence. 	|

<br />

><p style='text-align: justify;'>En caso de que las tablas no sigan estos parámetros, no cuenten con los datos obligatorios o contengan datos en diferentes formatos a los esperados, esto no representará un problema ya que las mismas se adaptarán para cumplir con los estándares detallados (como parte de la tarea curatorial de los datos). Cualquier otro tipo de parámetro adicional que contenga la tabla enriquecerá el dato del registro extraordinariamente (por ejemplo: sex, lifeStage, reproductiveCondition), se podrán agregar luego de las columnas mencionadas y serán adaptados a los estándares previstos, según los términos de Darwin Core.</p>  

<br />

**Decargue aquí un archivo template: [Formato de Datos](/img/formato_de_registros.ods).**

<br />

[^1]: *Términos tomados del Darwin Core, un estándar diseñado con el propósito de crear un lenguaje común para publicar y documentar datos sobre registros biológicos (observaciones o ejemplares de colección), listas de especies y catálogos taxonómicos. Ver la lista completa de términos [Darwin Core quick reference guide](https://dwc.tdwg.org/terms/)* 

