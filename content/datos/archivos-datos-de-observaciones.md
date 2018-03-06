+++
date = "2018-01-28T18:14:07Z"
draft = false
title = "¿Qué información deben contener los archivos con datos de observaciones?"

+++

### Tablas con registros individuales  

Las tablas contendrán campos relativos a la especie registrada, la localidad y fecha de colecta e información sobre su colector y lugar de almacenamiento. Cada fila en un archivo representa un registro completo y las columnas representan todos los parámetros que componen el registro (formato de hoja de cálculo).

<br />

Idealmente las columnas (parámetros) a ingresar son los siguientes (los datos en __negrita__ son imprescindibles)[^1]:  
  

| Parámetro            | Descripción                                                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------|
| __scientificName__   | Nombre científico del organismo registrado.                                                                                 |
| scientificNameID     | Identificador para relacionar el registro con el nombre taxonómico aceptado                                                 |
| vernacularName       | Nombre común del organismo registrado.                                                                                      |
| kingdom              | Esta información se determina informáticamente a partir del scientificNameID.                                               |
| phylum               | Esta información se determina informáticamente a partir del scientificNameID.                                               |
| class                | Esta información se determina informáticamente a partir del scientificNameID.                                               |
| order                | Esta información se determina informáticamente a partir del scientificNameID.                                               |
| family               | Esta información se determina informáticamente a partir del scientificNameID.                                               |
| countryCode          | Código para Uruguay: UY.                                                                                                    |
| locality             | Localidad de colecta.                                                                                                       |
| __decimalLatitude__  | En grados decimales. Ejemplo: -33.0000                                                                                      |
| __decimalLongitude__ | En grados decimales. Ejemplo: -58.0000                                                                                      |
| __eventDate__        | Fecha de colecta. Formato dd-mm-aaaa                                                                                        |
| basisOfRecord        | Describe la naturaleza del registro. Ejemplos: PreservedSpecimen, LivingSpecimen, HumanObservation, and MachineObservation. |
| institutionCode      | Código de identificación de la institución que posee los datos. Ejemplos: A, B, C.                                          |
| collectionCode       | Código de identificación de la colección. Ejemplos: A-HERP, B-REPTILES, C-MAM, etc.                                         |
| catalogNumber        | Código de identificación del registro en la Colección. Ejemplos: A-HERP-001, B-REPTILES-001, C-MAM-001, etc.                |
| recordedBy           | Nombre de la persona que colectó el registro.                                                                               |
| identifiedBy         | Nombre de la persona que identificó el registro.                                                                            |
| record_number        | Código del registro en la Colección. Ejemplo: A-HERP-001, B-REPTILES-001, C-MAM-001, etc.                                   |

<br />

>En caso de que las tablas no sigan estos parámetros, no cuenten con los datos obligatorios o contengan datos en diferentes formatos a los esperados, **esto no representará un problema** ya que las mismas se adaptarán para cumplir con los estándares detallados (como parte de la tarea curatorial de los datos). Cualquier otro tipo de parámetro adicional que contenga la tabla enriquecerá el dato del registro extraordinariamente (por ejemplo: sex, lifeStage, reproductiveCondition), se podrán agregar luego de las columnas mencionadas y serán adaptados a los estándares previstos, según los términos de Darwin Core.  

<br />


### Lista de especies 
Dado que los investigadores pueden tener sus datos en este formato, además de tablas con registros individuales, se aceptarán registros en listas. En este caso el archivo será un inventario de organismos para un mismo punto geográfico o varias coordenadas, con una fecha de colecta. Una vez adaptados los archivos, los parámetros a ser completados para estos registros serán los mismos que para las tablas.  

<br />

[^1]: *Términos tomados del Darwin Core, un estándar diseñado con el propósito de crear un lenguaje común para publicar y documentar datos sobre registros biológicos (observaciones o ejemplares de colección), listas de especies y catálogos taxonómicos.* 

