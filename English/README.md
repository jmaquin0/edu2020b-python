# Python Analytics Course - Spring 2020

## Main Goals

* Design and develop Data Analytics-based applications using service-oriented architectural principles.
* Use an Integrated Development Environment to go through the lifecycle´s stages of a common data analytics project.

## Methodology

* **Training**: { Theory: "20%" , Practice: "80%" }.
* **Responsibilities**: { Homeworks: "Before class sessions", Workshops: "During class sessions",
  **Project**: "During and after class sessions" }.
* **Online Resources** = [Videos, Docs, GitHub repository, Source code].
* **Communication channels and forums**: Slack | Discord.

## Training areas

* **Use Case**
  * Problem definition.
  * Process definition.
  * Project stages.
  * Roles and Responsibilities.
  * Deriverables definition.

* **Git**
  * **Basics** - Working Directory --> Staging --> .git repo --> .git remote repo
  * **Git flow** - Master <- Develop <- Feature / Release / Hotfix  -- Pair Programming / Pull Request
  * **Tools** - GitHub, Git Editors and Editor Plugins.

* **Scrum**
  * How to write a Project, Features, User Stories and Tasks.
  * **Metrics**: Velocity and Capacity.
  * **Versioning**: Git integration.

* **Domain Driven Design (DDD)**
  * Concepts applied to the Use Case.

* **Python environment configuration**
  * Library version management with `pyenv`.
  * Virtual environments management with `mkvirtualenvwrapper`.

* **PyCharm IDE Basics** 
  * Create a new Data-Analytics Python Project.
    * Recommended python project template.
  * Creating a basic Data-Anaytics application.
  * Setup a virtual environment.
  * Creating a pip python library and publishing to registry.
  * Python Log management and Levels.
  * Static code analysis with Flake8.
  * Code coverage with **[Coverage.py](https://coverage.readthedocs.io/en/coverage-5.0.4/)**.
  * **Unittests** with **[pytest](https://docs.pytest.org/en/latest/)** and **[tox](https://pypi.org/project/tox/)**.
  * **[Integration testing](https://www.fullstackpython.com/integration-testing.html)**.
  * **[QA - Smoke testing](https://aarongorka.com/blog/smoke-testing-infrastructure/)**.

* **SOA**
  * Introduction to the Service-Oriented Architectures (SOA)
  * **SOAP service implementation**: pros and cons.
  * **RESTful service implementation**: pros and cons.
  * **GRAPHQL service approach**: pros and cons.
  * **GRPC service implementation**: pros and cons.

* **RESTful**
  * Introduction to OpenAPI.
  * RESTful API design and best practices.
  * **OpenAPI 3.0**: API REST specification.
  * Link the Python Data-Analytics application development to the OpenAPI 3.0 specification:
    * Path parameters.
    * Query parameters.
    * Body.
  * **Auth0**: API authentication/authorization using JWT Tokens.
  * Configuring an application server for high availability.
  * Packaging and Deploying a RESTful web service as a Docker container.
  * **Postman**: Testing the REST API.

* **REST AWS**
  * AWS resources and best practices (Tagging, Policies, IaaC).
  * **OpenAPI 3.0**: API REST specification.
  * Link the Python Data-Analytics application development to the OpenAPI 3.0 specification:
    * Path parameters.
    * Query parameters.
    * Body.
  * [**Cognito** - API authentication/authorization using JWT Tokens](https://aws.amazon.com/es/cognito/).
  * Packaging and Deploying a REST web service as a AWS Lambda Function.
  * Deploying to AWS EKS, AWS ECS, AWS Fargatate considerations.
  * **Postman**: Testing the REST API.

* **Polyglot Persistence layer && Not-Only SQL (NoSQL)**:
  * **Relational Databases**:
    * Relational Database modeling, principles and best practices.
    * Persistent python objects in database with SQLAlchemy (PostgreSQL, AWS Aurora).
    * Use unittests with Docker and Mocks.
  * **Time Series Databases**: [InfluxDB](https://www.influxdata.com/).
  * **Document Databases**: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_americas_colombia_search_brand_atlas_desktop&utm_term=mongodb%20atlas&utm_medium=cpc_paid_search&utm_ad=e&gclid=CjwKCAjw4KD0BRBUEiwA7MFNTaXgR5gxbpm9vmvLtPLnBkdaqBr9fWxMFSpO9orpBlAC0zC0R5RAGBoCnVEQAvD_BwE).
  * **Key-value store**: [AWS Dynamodb](https://aws.amazon.com/es/dynamodb/).
  * **BONUS - Graph Databases**: [Neo4j](https://neo4j.com/) && [OrientDB](https://orientdb.com/).

* **Logs and Data Visualization**
  * Setting up InfluxDB and Grafana.
  * Creating dashboards.
  * Realtime stats generation from an analytics service.

* **CI/CD**
  * Defining development workflows (test, delivery, deployment, rollbacks, patchs, vulnerability scan).
  * Implement code scripts for pipeline stages.
  * Use Github Actions for CI/CD implementation.
  * **ChatOps**: Notificaciones y alertas.

* **Monitoring**
  * Stack EFK.
  * AWS CloudWatch.

* **Profiling**
  * Basic security configuration steps before release delivery.
  * Improve Python code performance using profiling tools before release delivery.

## References
* **PyCharm**: https://www.jetbrains.com/help/pycharm/quick-start-guide.html
* **Smoke testing tools**: https://medium.com/hootsuite-engineering/our-journey-in-smoke-test-frameworks-6a1fb30572e2 

