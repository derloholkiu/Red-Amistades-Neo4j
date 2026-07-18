# Red de Amistades del Salón con Sugerencia de Amigos

## Descripción

Este proyecto implementa una base de datos NoSQL utilizando **Neo4j**, modelando una red de amistades de un salón de clases.

El objetivo es demostrar cómo una base de datos orientada a grafos facilita consultas de relaciones, como la sugerencia de amigos basada en amigos en común.

## Tecnologías utilizadas

- Neo4j 5.x
- Cypher Query Language
- Neo4j Browser

## Estructura del proyecto

```
Red-Amistades-Neo4j/
│
├── 01_crear_nodos.cypher
├── 02_relaciones.cypher
├── 03_consultas.cypher
└── README.md
```

## Modelo de datos

### Nodos

- Persona
- Curso
- Hobby

### Relaciones

- `AMIGO_DE`
- `ES_DE`
- `LE_GUSTA`

## Datos cargados

El proyecto contiene:

- 40 personas
- 8 cursos
- 10 hobbies
- Relaciones de amistad (AMIGO_DE)
- Relaciones Persona → Curso (ES_DE)
- Relaciones Persona → Hobby (LE_GUSTA)

## Instrucciones de ejecución

### Paso 1

Crear una nueva base de datos en Neo4j.

### Paso 2

Ejecutar el archivo:

```
01_crear_nodos.cypher
```

Este archivo crea:

- Personas
- Cursos
- Hobbies

### Paso 3

Ejecutar el archivo:

```
02_relaciones.cypher
```

Este archivo crea:

- Relaciones ES_DE
- Relaciones LE_GUSTA
- Relaciones AMIGO_DE

### Paso 4

Ejecutar el archivo:

```
03_consultas.cypher
```

Este archivo contiene las consultas solicitadas en el proyecto.

## Consultas implementadas

### Consulta 1

Sugerencia de amigos basada en amigos en común.

### Consulta 2

Personas con mayor cantidad de conexiones.

### Consulta 3

Amigos en común entre dos personas.

## Resultados obtenidos

El sistema permite:

- Modelar una red social mediante grafos.
- Identificar personas con mayor número de amistades.
- Encontrar amigos en común entre dos personas.
- Recomendar nuevos amigos mediante relaciones de segundo nivel.

## Autores:
-AGUILAR CALDERON AGUILAR CALDERON.
-ALCALDE NAVARRO SEBASTIAN ALONSO.
-RIOS RIOS HOLGER BRYAM.
-SANCHEZ VARGAS DANIELA CRISTINA.

Proyecto desarrollado para el curso de Bases de Datos NoSQL utilizando Neo4j.
