# Python Analytics Course - Spring 2020

## Objetivos

* Diseñar e implementar aplicaciones para el analisis de datos empleando arquitecturas orientadas a servicios
* Emplear un IDE de desarrollo para las etapas de vida de un proyecto de analitica de datos

## Metología

* Clases 20% teoricas , 80% practicas.
* Actividades previas a la clase, durante la clase y posterior a clase
* Videos, Documentación y código fuente disponible en GitHub
* Canal de Slack para solución de dudas

## Contenido

* Git
  * Basics
  * Git flow
  * Tools (GitHub, Git Editors, Editor Plugins)

* Scrum
  * How to write a Project, Features, User Stories, Tasks
  * Metrics (Velocity, Capacity)
  * Git integration

* Python environment configuration
  * Manejo de version de python con pyenv
  * Gestion de ambientes virtuales con mkvirtualenvwrapper

* PyCharm IDE Basics
  * Create a Project
  * Recommended python project template
  * Setup a virtual environment
  * Creating a Hello World Application
  * Python Log management and Levels
  * Analisis de código estatico con Flake8, Covertura con Pycoverage
  * Unittests with Pytest and Tox

* SOA
  * Introduccion a las arquitecturas orientadas a servicios (SOA)
  * Implementaciones de SOA: SOA, REST, GRAPHQL, GRPC
  * Introduction to OpenAPI
  * Diseño de API Rest y buenas practicas

* REST ( Docker EKS / ECS / Fargate )
  * Creación de la especificación de un API REST usando OpenAPI 3.0
  * Conexión de una especificación en OpenAPI 3.0 con código en Python 3
    * Path parameters
    * Query parameters
    * Body
  * API authentication/authorization using JWT Tokens (Auth0)
  * Configuring an application server for high availability
  * Packaging and Deploying a REST web service as a Docker container
  * Pruebas de API REST usando la aplicación Postman

* REST ( Lambda )
  * Creación de la especificación de un API REST usando OpenAPI 3.0
  * Conexión de una especificación en OpenAPI 3.0 con código en Python 3
    * Path parameters
    * Query parameters
    * Body
  * API authentication/authorization using JWT Tokens (Cognito)
  * Packaging and Deploying a REST web service as a AWS Lambda Function
  * Pruebas de API REST usando la aplicación Postman

* Persistence ( SQL )
  * Database modeling and best practices
  * Persistent python objects in database with SQLAlchemy (PostgreSQL, AWS Aurora)
  * Use unittests with Docker and Mocks

* Persistence (NO SQL)
  * Database modeling and best practices
  * Time Series Databases
  * Document Databases
  * NoSQL persistence with Python (MongoDB, InfluxDB, AWS Dynamodb)
  * Unittest with Docker and Mocks

* Visualization
  * Setting up InfluxDB and Grafana
  * Creating dashboards
  * Realtime stats generation from an analytics service

* CI/CD
  * Defining development workflows (test, delivery, deployment, rollbacks, patchs, vulnerability scan)
  * Implement code scripts for pipeline stages
  * Use Github Actions for CI/CD implementation
  * ChatOps: Notificaciones y alertas

* Monitoring
  * Stack EFK
  * AWS CloudWatch

* Profiling
  * Improve Python code performance using profiling tools

## References
* https://www.jetbrains.com/help/pycharm/quick-start-guide.html