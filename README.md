# Open-Manifesto

Open Manifesto es un estándar abierto para programas electorales. Un formato estructurado para los programas de los partidos políticos que facilita su comprensión y la rendición de cuentas a la ciudadanía.

## Standard OM versión 1.1

### Programa

- *politicalParty*: Nombre del partido político.
- *title*: Título del programa electoral.
- *publicationDate*: Fecha de publicación del programa electoral.
- *electionDate*: Fecha de las elecciones.
- *electionType*: Tipo de elecciones (Generales/Autonómicas/Municipales/Europeas)
- *geographicalArea*: Área geográfica (nombre del país, comunidad autónoma o municipio)
- *standardVersion*: Versión del estándar usada para publicar el programa.
- *URI*: URI (identificador de recursos uniforme) para la versión estandarizada del programa
- *createdBy*: Nombre del equipo que ha creado la versión estandarizada del programa.
- *pages*: Número de páginas del programa.
- *numProposals*: Número de propuestas del programa.

### Propuestas

- *id*: Identificador numérico de la propuesta (incremental desde 0)
- *body*: Texto de la propuesta.
- *topics*: Temas principales sobre los que versa la propuesta siguiendo un conjunto de términos definidos por el grupo Open Manifesto Project.
- *tags*: Subtemas o palabras clave abordados en la propuesta.
- *priority*: Prioridad de la propuesta asignada por el partido (baja, media, alta o NA)
- *budget*: Presupuesto para el desarrollo de la propuesta.
- *nonNegotiable*: Si la propuesta es negociable “línea roja” (verdadero, falso o NA)
- *agents*: Lista de agentes incluidos o mencionados en la propuesta.

## Directorio de programas estandarizados

El índice de los programas estandarizados se encuentra en [ManifestoDirectory.json](https://github.com/open-manifesto-project/Open-Manifesto/blob/master/ManifestoDirectory.json)

## Enlaces

Para más información sobre el proyecto acceder a [openmanifestoproject.org](https://openmanifestoproject.org/)
