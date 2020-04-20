# Curso de actualización en Python 2020B

## Énfasis

* Manejo de Entornos Integrados de Desarollo (IDE)
* Guiado por la construcción de una aplicación de analítica de datos

## Objetivos

* Diseñar e implementar aplicaciones para la analítica de datos empleando arquitecturas orientadas a servicios
* Emplear un IDE para las etapas de vida de un proyecto de analítica de datos

## Metología

* Curso virtual
* Clases 20% teoricas, 80% practicas.
* Actividades previas a la clase, durante la clase y posterior a clase
* Videos, Documentación y código fuente disponible en GitHub
* Canal de Slack y Discord para solución de dudas

## Contenido

* Descripción general del curso
  * Objetivos
  * Contenido
  * Metodología
  * Caso de Uso

* Herramientas de versionamiento de código
  * Introducción a Git
  * Instalación de Git
  * Conceptos básicos
    * Fork
    * Clone
    * Reference: Branch, Tag, Commit
    * Pull request, Merge request
    * Merge
    * Rebase
    * Stash
      * Push
      * Pop
    * Reset
    * connection via SSH
  * Herramientas
    * Proveedores en Internet
      * Gitlab
      * Github
      * Bitbucket
      * AWS CodeCommit
    * Editores
      * VSCode
        * Plugins
      * Pycharm
        * Plugins
  * Flujo de trabajo con Git
    * Github Flow
    * Gitlab Flow
    * BitBucket Flow

* Metodologías ágiles
  * Introducción
  * Planeación y seguimiento
    * Proyecto
    * Funcionalidades
    * Historias de usuario
    * Subtareas
  * Métricas
    * Velocidad
    * Capacidad
  * Integración con Git
    * Rally
    * Jira

* Configuración de ambientes virtuales en Python
  * Gestión de versiones de Python con pyenv
  * Gestión de ambientes virtuales con mkvirtualenvwrapper
  * Gestión de librerias por ambiente de desarrollo

* PyCharm IDE Basics 
  * Creación de un proyecto
  * Creación de una plantilla de proyecto
  * Configuración de ambientes virtuales
  * Presentación de ejemplo básico de analítica
  * Creación de una biblioteca de Python y publicación en servidor
  * Gestión de Logs y niveles
  * Analisis de código estatico con flake8,
  * Covertura con pycoverage

* Bateria de pruebas
  * Diseño guiado por las pruebas (TDD)
  * Diseño guiado por el comportamiento (BDD)
  * Pruebas unitarias with pytest and tox
  * Pruebas de integración 
  * Pruebas de humo
  * Pruebas de carga

* Diseño guiado por el dominio (DDD)
  * Introducción
  * Táctica y Estrategia
  * Dominios acotados, lenguaje ubícuo
  * Arquitectura hexagonal 
  * Comunicación entre dominios
  * Event sourcing
  * Principios SOLID

* SOA
  * Introduccion a las arquitecturas orientadas a servicios (SOA)
  * Implementacion SOA
  * Implementacion REST
  * Implementacion GRAPHQL
  * Implementación GRPC

* REST
  * Introducción a OpenAPI
  * Diseño de API y buenas prácticas
  * Creación de la especificación de un API usando OpenAPI 3.0
  * Conexión de una especificación en OpenAPI 3.0 con código en Python 3
    * Párametros en el path
    * Párametros en el query
    * Información en la carga útil
  * Autenticación y autorización de API empleando JWT Tokens (Auth0)
  * Empaquetando la aplicación en un contenedor de Docker
  * Configuración de un servidor de aplicación: UWSGI, AIO, Unicorn
  * Pruebas locales de la API empleando la aplicación Postman

* REST en AWS
  * Descripción de recursos de AWS
    * AWS VPC
    * AWS S3
    * AWS Api Gateway
    * AWS Route53
    * AWS IAM
    * AWS Lambda
    * AWS EC2
    * AWS EKS
    * AWS CloudFormation
  * Buenas prácticas
    * Etiquetado
    * Políticas
    * Infrastructura como servicio
  * Creación y recomendaciones para el ajuste inicial de una cuenta de AWS
  * Empaquetando el código para despliegue como función lambda en AWS
    * Creación de la especificación por medio de AWS API Gateway
    * Filtrado de parámetros en la URL, consulta y carga útil
    * Autenticación y autorización empleando JWT tokens y AWS Cognito
  * Empaquetando el código para despliegue como contenedor de docker en AWS
    * Consideraciones para el despliegue: AWS EKS, AWS ECS, AWS Fargate
  * Pruebas de la API usando la aplicación Postman

* Capa de persistencia y No solamente SQL 
  * Bases de datos relacionales
    * Principios, modelado y buenas prácticas
  * Bases de datos de series de tiempo
    * [InfluxDB](https://www.influxdata.com/)
  * Bases de datos documentales
    * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_americas_colombia_search_brand_atlas_desktop&utm_term=mongodb%20atlas&utm_medium=cpc_paid_search&utm_ad=e&gclid=CjwKCAjw4KD0BRBUEiwA7MFNTaXgR5gxbpm9vmvLtPLnBkdaqBr9fWxMFSpO9orpBlAC0zC0R5RAGBoCnVEQAvD_BwE)
  * Bases de datos llave-valor
    * [AWS Dynamodb](https://aws.amazon.com/es/dynamodb/)
  * Bases de datos orientada a grafos
    * [Neo4j](https://neo4j.com/) && [OrientDB](https://orientdb.com/).
  * Persistencia de objetos en bases de datos SQL and NoSQL
  * Pruebas unitarias para persistencia empleando contendores virtuales

* Visualización
  * Configurando un ambiente con InfluxDB y Grafana
  * Creacíon de tableros de información
  * Generación de estadísticas en tiempo real
  * Consideraciones para un despliegue a producción

* Integración continua y despliegue continuo (CI/CD)
  * Definición de flujos de desarrollo
    * Bateria de pruebas
    * Entrega continua
    * Despliegue continuo
    * Reversión de cambios
    * Correciones
    * Escaneo de vulnerabilidades
    * Validación de RFCs para despliegue
  * Herramientas de integración continua
    * Travis
    * Github Actions
    * DroneIO
    * CircleCI 
    * AWS CodePipeline
  * Uso de Python para la ejecución de tareas de automatización
  * Implementación de ChatOPS
    * Microsoft Teams
    * Slack
  * Diseño e implementación del sistema de alertas
    * PagerDuty 
    * NewRelic

* Monitoreo
  * Pila de monitoreo ElasticSearch-Fluentd-Kibana
    * Introducción y despliegue de Elasticsearch
    * Introducción y despliegue de Kibana
    * Introducción a los recolectores de logs y despliegue de Fluentd

* Monitoreo en AWS
  * Pila de monitoreo ElasticSearch-Fluentd-Kibana
  * AWS CloudWatch

* Optimización
  * Mejora del desempeño de apliciones en Python empleando herramientas de perfilado

## Referencias
* https://www.jetbrains.com/help/pycharm/quick-start-guide.html
