#TP4 - SCM

En el siguiente documento se presentan los lineamientos que se seguirán a lo largo de la gestión de la configuracion del proyecto durante el cursado de la materia Ingenieria y Calidad de Software en la Universidad Nacional Tecnológica.

### Árbol de Directorios
    ISW
    I──I Teórico
    |     |──I 01 Presentación de clase
    |     |      |──I  0X - Nombre
    |     |──I 02 Resúmenes
    |     |      |──I  ResumenParcialX
    |     |──I 03 Bibliografia
    |     |      |──I  Libros
    |     |──I 04 Toma de notas
    |     |      |──I  Clase-FechaDD/MM/AAA-Nombre
    I──I Práctico
    |     |──I 05 Guías
    |     |      |──I  GuíaDeTrabajo_AAAA
    |     |──I 06 Trabajos Prácticos
    |     |      |──I  TPX
    |     |──I 07 Toma de notas
    |     |      |──I  Clase-FechaDD/MM/AAA-Nombre
    I──I Complementario
    |     |──I Link-Clase
    |     |──I Programa de la materia



------------

###Línea Base
Teniendo en cuenta que un punto de referencia que utilizamos para medir el progreso en la materia son los resultados de los parciales y el contenido que abarcan los mismos, utilizamos este criterio y definimos la línea base para cada parcial rendido aprobado. 
Consideramos un parcial, un momento adecuado para marcar la línea base, la cual estará en la rama main del repositorio.


---
###Listado Items de configuración

| Tipo             | Formato          | Regla Nombrado                   | Abreviatura | Ubicación Física          |
|------------------|------------------|----------------------------------|-------------|---------------------------|
| Presentación de clase | PDF          | `<0X><Nombre de la presentación>.pdf` | PRES        | Teórico/Presentación      |
| Resúmenes        | PDF              | `<Resumen><Parcial><X>.<Extensión>`  | RESUM       | Teórico/Resúmenes         |
| Bibliografía     | PDF              | `<Nombre>.pdf`                   | BIBLIO      | Teórico/Bibliografía      |
| Toma de notas    | PDF              | `<Clase><DD/MM/AAAA><Nombre><Legajo>.pdf` | NOTATEO | Teórico/Toma_de_notas    |
| Guías            | PDF              | `<Guía><Nombre>.pdf`             | GUIA        | Práctico/Guías            |
| TPS              | PDF, DOCX        | `<TP><X>.pdf`                    | TPS         | Práctico/TPS              |
| Toma de notas    | PDF              | `<Clase><DD/MM/AAAA><Nombre><Legajo>.pdf` | NOTAPRA | Práctico/Toma_de_notas    |
| Complementario   | PDF, DOCX, XLSX  | `<Nombre>.<extensión>`           | COMP        | Complementario/           |


------------

