# Open-Manifesto

Open Manifesto es un estándar abierto para programas electorales. Un formato estructurado para los programas de los partidos políticos que facilita su comprensión y la rendición de cuentas a la ciudadanía.

## Standard OM versión 1.0
### Programa

- *politicalParty*: Nombre del partido político. 
- *title*: Título del programa electoral.
- *publication_date*: Fecha de publicación del programa electoral.
- *election_date*: Fecha de las elecciones.
- *type_of_elections*: Tipo de elecciones (Generales/Autonómicas/Municipales/Europeas)
- *geographical_area*: Área geográfica (nombre del país, comunidad autónoma o municipio)
- *standard_version*: Versión del estándar usada para publicar el programa.
- *URI*: URI (identificador de recursos uniforme) para la versión estandarizada del programa
- *created_by*: Nombre del equipo que ha creado la versión estandarizada del programa.
- *pages*: Número de páginas del programa.
- *num_proposals*: Número de propuestas del programa.

### Propuestas

- *id*: Identificador numérico de la propuesta (incremental desde 0)
- *body*: Texto de la propuesta.
- *topic*: Tema principal sobre la que versa la propuesta siguiendo la taxonomía propuesta en la Norma Técnica de       Interoperabilidad de España.
- *entities*: Subtemas o palabras clave abordados en la propuesta.
- *priority*: Prioridad de la propuesta asignada por el partido (baja, media, alta o NA)
- *budget*: Presupuesto para el desarrollo de la propuesta.
- *non_negotiable*: Si la propuesta es negociable “línea roja” (verdadero, falso o NA)
- *agents*: Lista de agentes incluidos o mencionados en la propuesta.
