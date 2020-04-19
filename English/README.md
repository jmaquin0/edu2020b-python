# Python Updating Skills Course 2020B

## Emphasis

* Integrated Development Environments (IDE) management.
* Guided by a Data Analytics Application development.

## Main Goals

* Design and develop Data Analytics-based applications using service-oriented architectural principles.
* Use an Integrated Development Environment to go through the lifecycle´s stages of a common data analytics project.

## Methodology

* Virtual sessions.
**Training**: Theory: 20% and Labs and Workshops: 80%".
* **Responsibilities**: Homeworks, before class sessions; Workshops, during class sessions; and a Project during and after class sessions.
* **Online Resources** = [Videos, Docs, GitHub repository, Source code].
* **Communication channels and forums**: Slack and Discord.

## Index

* Course overview
  * Objectives.
  * Subjects.
  * Methodology.
  * Use Case.

* Tools for version control
  * Introduction to Git
  * Basics
    * Reference: Branch, Tag, Commit
    * Pull request, merge request
    * Merge
    * Rebase
    * Stash
    * Reset
  * Tools
    * Internet providers
    * Editors
    * Plugins
  * Workflows
    * GitHub Flow
    * GitLab Flow
    * BitBucket Flow

* Agile principles and methodologies
  * Introduction
  * Planning and monitoring
    * Project
    * Functional Requirements
    * User Stories
    * Subtasks
  * Metrics
    * Velocity metrics
    * Capacity metrics
  * Integration with Git
    * Rally
    * Jira
  
* Set Virtual Environments in Python
  * Version control with *pyenv*
  * Virtual environments management with *mkvirtualenvwrapper*
  * Library management in developer environments

* PyCharm IDE Basics
  * Create a project
  * Create a project template
  * Virtual environments configuration
  * Basic Analytics Sample Presentation
  * Making and publishing a custom Python library
  * Log management and verbose
  * Static code analysis with *flake8*
  * Code coverage with **[pycoverage](https://coverage.readthedocs.io/en/coverage-5.0.4/)**.

* Testing Stack:
  * Test Driven Development (TDD).
  * Behavior Driven Development (BDD).
  * Unit testing with **[pytest](https://docs.pytest.org/en/latest/)** and **[tox](https://pypi.org/project/tox/)**.
  * [Integration testing](https://www.fullstackpython.com/integration-testing.html).
  * [QA - Smoke testing](https://aarongorka.com/blog/smoke-testing-infrastructure/).
  * [Load Testing with Locust](https://locust.io/).

* Domain Driven Design (DDD)
  * Introduction.
  * Tactics and Strategy.
  * [Bounded Contexts](https://martinfowler.com/bliki/BoundedContext.html) and [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html).
  * Hexagonal Architecture.
  * Inter-domain Communication.
  * Event sourcing.
  * SOLID Principles.
  
* SOA
  * Introduction to the Service-Oriented Architectures (SOA)
  * **SOAP service implementation**: pros and cons.
  * **RESTful service implementation**: pros and cons.
  * **GRAPHQL service approach**: pros and cons.
  * **GRPC service implementation**: pros and cons.

* REST
  * Introduction to **[OpenAPI](https://swagger.io/docs/specification/about/)**.
  * API Design and best practices.
  * API creation and specification using OpenAPI 3.0.
  * [Python 3 and OpenAPI 3.0](https://github.com/zalando/connexion).
    * Path params.
    * Query params.
    * Request body.
  * API authentication and authorization using JWT Tokens with [Auth0](https://auth0.com/).
  * Containerization using **[Docker](https://www.docker.com/resources/what-container)** containers.
  * Applicaton server configuration using UWSGI, AIO, Unicorn.
  * **Postman**: Testing the REST API.

* REST AWS
  * AWS resources:
    * AWS VPC.
    * AWS S3.
    * AWS Api Gateway.
    * AWS Route53.
    * AWS IAM.
    * AWS Lambda.
    * AWS EC2.
    * AWS EKS.
    * AWS CloudFormation.
  * AWS Best Practices:
    * Tagging.
    * Policies.
    * Infrastructure as a Service (IaaS).
    * Creation and recommendations for initial adjustment of an AWS account.
    * Lambda functions in AWS in order to deploy an application code.
    * Specification using AWS API Gateway.
    * Filtering by: path params, query params and request body.
    * AWS Cognito for Authentication and Authorization using JWT tokens.
    * Packaging the code for deployment as a docker container on AWS
      * **Deployment requirements**: AWS EKS, AWS ECS, AWS Fargate.
    * AWS API testing using Postman.
  
  * Link the Python Data-Analytics application development to the OpenAPI 3.0 specification:
    * Path parameters.
    * Query parameters.
    * Body.
  * [**Cognito** - API authentication/authorization using JWT Tokens](https://aws.amazon.com/es/cognito/).
  * Packaging and Deploying a REST web service as a AWS Lambda Function.
  * Deploying to AWS EKS, AWS ECS, AWS Fargatate considerations.
  * **Postman**: Testing the REST API.


* Polyglot Persistence layer && Not-Only SQL (NoSQL):
  * **Relational Database modeling**
    * Principles and best practices.
  * **Time Series Databases**:
    * [InfluxDB](https://www.influxdata.com/).
  * **Document Databases**: 
    * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_americas_colombia_search_brand_atlas_desktop&utm_term=mongodb%20atlas&utm_medium=cpc_paid_search&utm_ad=e&gclid=CjwKCAjw4KD0BRBUEiwA7MFNTaXgR5gxbpm9vmvLtPLnBkdaqBr9fWxMFSpO9orpBlAC0zC0R5RAGBoCnVEQAvD_BwE).
  * **Key-value store**: 
    * [AWS Dynamodb](https://aws.amazon.com/es/dynamodb/).
  * **Graph-oriented databases**:
    * [Neo4j](https://neo4j.com/) && [OrientDB](https://orientdb.com/).
  * Unit testing using virtual containers.

* Visualization
  * Setting the environment using [InfluxDB](https://www.influxdata.com/) and [Grafana](https://grafana.com/).
  * Creation of information boards.
  * Generation of real-time statistics.
  * Considerations for a production deployment.

* Continuous Integration and Continuous Deployment (CI/CD)
  * Defining development workflows
    * Testing stack.
    * Continuous Delivery.
    * Continuous Deployment.
    * Rollbacks.
    * Patching.
    * Vulnerability scanning.
    * Request For Changes (RFC) validation before deployment.
  * Continuous Integration tools
    * [Travis CI](https://travis-ci.org/).
    * GitHub Actions.
    * [DroneIO](https://cloud.drone.io/).
    * [CircleCI](https://circleci.com/).
    * [AWS CodePipeline](https://aws.amazon.com/es/codepipeline/).
  * Implement Python code scripts for pipeline stages.
  * **ChatOps implementation**
    * [Microsoft Teams]().
    * [Discord](https://discordapp.com/).
    * [Slack](https://slack.com/intl/es-co/).
  * Design and implementation of an **alert system**
    * [PagerDuty](https://www.pagerduty.com/).
    * [NewRelic](https://newrelic.com/).

* Monitoring
  * Monitoring Stack ElasticSearch-Fluentd-Kibana.
    * Introduction and deployment of Elasticsearch
    * Introduction and deployment of Kibana
    * Introduction to log collectors and Fluentd deployment.

* AWS Monitoring
  * Monitoring Stack ElasticSearch-Fluentd-Kibana.
  * [AWS CloudWatch](https://aws.amazon.com/es/cloudwatch/).

* Optimization
  * Improve Python code performance using profiling tools before release delivery.

## References
* https://www.jetbrains.com/help/pycharm/quick-start-guide.html
