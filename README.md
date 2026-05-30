# 📚 Apuntes de Arquitectura de Datos: NoSQL & Web Semántica

Bienvenido a mi repositorio de referencia sobre bases de datos modernas y tecnologías semánticas. 

Este proyecto consiste en una Single Page Application (SPA) estática que sirve como guía de consulta rápida y apuntes detallados. Está diseñada con especial énfasis en el ecosistema de la **Web Semántica** y en el modelado avanzado de documentos con **MongoDB**.

## 🎯 Foco Principal del Proyecto

Aunque la guía cubre varios motores NoSQL, el contenido principal hace hincapié en las siguientes tecnologías clave:

### 🕸️ Web Semántica y Grafos de Conocimiento
El futuro de los datos estructurados y enlazados. En esta sección profundizo en:
* **RDF & RDFS:** La base de los triples (`Sujeto` -> `Predicado` -> `Objeto`) y el establecimiento de taxonomías y jerarquías de clases básicas.
* **SPARQL:** Lenguaje de consulta declarativo para grafos RDF. Incluye el uso de filtros complejos, opcionales, uniones, funciones nativas (`STRSTARTS()`, `CONTAINS()`) y operaciones de actualización dinámicas (`INSERT/DELETE WHERE`), así como la gestión mediante *Graph Store Protocol* con comandos `cURL`.
* **SHACL (Shapes Constraint Language):** Definición de *Shapes* estructurales (`NodeShape` y `PropertyShape`) para forzar validaciones, tipos de datos (`datatype`), restricciones de cardinalidad (`minCount`/`maxCount`) y lógica condicional sobre grafos RDF.
* **OWL (Web Ontology Language):** Modelado ontológico formal sustentado en Lógicas Descriptivas. Uso de razonadores (*reasoners*) para la inferencia de conocimiento implícito, caracterización avanzada de propiedades (`owl:TransitiveProperty`, `owl:SymmetricProperty`, `owl:FunctionalProperty`, inversas) y restricciones locales de clases (`owl:someValuesFrom`, `owl:allValuesFrom`, cardinalidades exactas).

### 🍃 MongoDB
* Almacenamiento flexible basado en documentos BSON (JSON binario) y esquemas dinámicos.
* Uso avanzado de operadores de comparación, lógicos, expresiones regulares y operadores específicos para arrays (`$elemMatch`, `$size`).
* **Aggregation Pipeline:** Procesamiento de datos y analítica en etapas secuenciales utilizando etapas potentes como `$match`, `$group`, `$unwind` y acumuladores complejos.

## 🛠️ Tecnologías Adicionales Cubiertas
* **Redis:** Motor clave-valor en memoria de baja latencia. Gestión de tipos de datos estructurados (Hashes, Lists, Sets, Sorted Sets), políticas de persistencia (RDB/AOF) y arquitectura de mensajería Pub/Sub.
* **Cassandra (CQL):** Base de datos orientada a familias de columnas altamente escalable. Modelado físico basado en patrones de consulta, gestión de claves compuesta (*Partition Key* y *Clustering Key*) y niveles de consistencia ajustables (*Quorum*, *All*, *One*).
* **Neo4j (Cypher):** Base de datos de grafos de propiedades. Uso del lenguaje Cypher mediante patrones visuales ASCII para operaciones CRUD complejas y análisis de relaciones nativas de primer orden.

## 🚀 Cómo visualizar el proyecto
1. **En producción:** Puedes acceder a la versión desplegada en vivo a través de **GitHub Pages**.
2. **En local:** Clona este repositorio en tu máquina local y abre el archivo `index.html` con cualquier navegador web moderno.

---
*Repositorio desarrollado como recurso de estudio, consolidación técnica e ingeniería de datos durante mis estudios en la Escuela de Ingeniería de San Mamés (UPV/EHU).*
