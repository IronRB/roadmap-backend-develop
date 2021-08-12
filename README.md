# Roadmap backend develop
[[_TO_]]

## Introducción
Repositorio dedicado al plan de estudios de desarrollo de backend usando tecnologías como node js que nos brinda un entorno de ejecución para JavaScript 

## Contenido

- Prerequisitos
- Conceptos generales de desarrollo
- Framework de desarrollo web
- Bases de datos y ORMs
- Clientes API
- Testing
- Microservicios
- Caching
- Typed Superset
- Real-Time Communication

### Prerequisitos

- JavaScript
- NPM
- Node js
- ECMAScript

#### JavaScript:

Conceptos generales usados para dominar Node.js y JavaScript en el mínimo tiempo posible:

- Funciones de flecha
- Tipos de datos
- Funciones
- Bucles
- Matrices

En Node.js manejará mucha programación asincrónica y para eso, se recomienda aprender los siguientes conceptos.

- Temporizadores
- Promesas
- Cierres
- El bucle de eventos
- Programación asincrónica y devoluciones de llamada(callbacks)

#### NPM:

Node Package Manager, es un administrador de paquetes que facilita el desarrollo de aplicaciones que requieren una lista de dependencias.

NPM consta de 3 componentes distintos:

- La interfaz de línea de comandos (CLI): es el entorno de terminal de la máquina en que la que el desarrollador interactúa con NPM por medio de comandos.

- Registry: base de datos pública con librerias de software JavaScript.

- Sitio Web: plataforma donde se encontraran todos los paquetes creados.

#### Node Js:

Es un entorno de ejecución, el cual permite correr JavaScript del lado del servidor.

Los conceptos básicos de Node Js son:

- Event Emitters: Los emisores de eventos son objetos que desecadenar eventos al enviar un mensaje para indicar que se completó una acción.

- Callbacks: son funciones que son llamadas luego de completar una tarea evitando bloqueos y así permitir que el resto de código se ejecute.

- Buffers: una clase llamada Buffer en Node.js está diseñada para manejar datos binarios sin procesar. Corresponden a algo de memoria bruta asignada fuera de V8 . Los búferes son una matriz de números enteros que no se pueden cambiar de tamaño con un montón de métodos específicos para datos binarios.

- Module System: como parte del ecosistema de Node.js, utilizará el módulo para implementar funciones complejas con solo usar los módulos proporcionados por Node.js, estos son archivos JavaScript que contienen todas las características organizadas y complejas que cualquiera puede reutilizar.

#### ECMAScript:

Es la especificación definida en ECMA-262, para crear un lenguaje de scripting de propósito general. ECMA-262 es el estándar. ECMAScript es la especificación que este estándar representa.

### Conceptos generales de desarrollo:

- Sistemas de control de versiones(Git): son herramientas de software que ayudan a los equipos de software a gestionar los cambios en el código fuente a lo largo del tiempo.

- Protocolos HTTP/HTTPS: Son protocolos de transferencia de datos, HTTPS utiliza un protocolo de cifrado conocido como Transport Layer Security (TLS) para cifrar las comunicaciones. hay 6 métodos de solicitud responsables de cualquier comunicación básica en la web:

    - GET: Se utiliza para recuperar una representación de un recurso.
    - POST: Se utiliza para crear nuevos recursos.
    - PUT: Se utiliza para actualizar las capacidades.
    - PATCH: Se utiliza para modificar capacidades.
    - DELETE: Se utiliza para eliminar un recurso identificado por una URL.
    - OPTIONS: Solicite la opción de comunicación permitida para una URL o servidor determinados

- Clean code: 
Es una guía para crear software legible, reutilizable y refactorizable que se pueda mejorar con el tiempo.

### Framework de desarrollo web:

- Express.js
- Adonis.js
- Meteor.js
- Nest.js
- Sails.js
- Koa.js
- Loopback.io
- egg.js
- midway

### Bases de datos y ORMs:

- Relational
    - SQL Server
    - PostgreSQL
    - MariaDB
    - MySQL
- Cloud Databases
    - CosmosDB
    - DynamoDB
- Search Engines
    - ElasticSearch
    - Solr
    - Sphinx
- NoSQL
    - MongoDB
    - Redis
    - Apache Cassandra
    - LiteDB
    - RavenDB
    - CouchDB

### Clientes API:    
- REST
    - Node-Rest-Client
    - Axios
- GraphQL
    - express-graphql
    - apollo-server

### Testing    

- Pruebas unitarias, Pruebas de Integración
    - Jest
    - Chai
    - Mocha
- Pruebas E2E
    - Selenium
    - Playwright

### Microservicios

- Message-Broker
    - RabbitMQ
    - Apache Kafka
    - ActiveMQ
    - Azure Service Bus
- Message-Bus
    - Distribus
    - BusMQ

### Caching

- Node-Cache
- Distributed Cache
    - Redis
    - Memcached
- Memory Cache    

### Typed Superset

- TypeScript

### Real-Time Communication

- Socket.IO