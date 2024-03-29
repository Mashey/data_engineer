# Data Engineer :: Welcome

Hello and welcome to the Data Engineer onboarding process at Mashey!

!![Philip welcomes you](https://user-images.githubusercontent.com/10391857/104142589-768c8180-5379-11eb-9157-037f500abd73.jpg)

## Table of Contents

- [Mashey Team Culture](#mashey-team-culture)
- [What is a Data Engineer?](#data-engineer-introduction)
  - [What do Data Engineers Do?](#what-do-data-engineers-do?)
  - [Overlapping Roles](#overlapping-roles)
    - [What do Analytics Engineers do?](#what-do-analytics-engineers-do?)
    - [What do DevOps Engineers do?](#what-do-devops-engineers-do?)
    - [What do Cloud Engineers do?](#what-do-cloud-engineers-do?)
- [ELT vs ETL](#elt-vs-etl)
- [Agile + Scrum](#agile-+-scrum)
  - [Asana](#asana)
- [Data Engineering Practices](#data-engineering-practices)
- [The Mashey Stack](#the-mashey-stack)
  - [Code Quality and Testing](#code-quality-and-testing)
    - [CircleCI](#circleci)
    - [Coveralls](#coveralls)
    - [Codacy or Hound](#codacy-or-hound)
  - [Languages](#languages)
    - [Python](#python)
      - [Python Packages](#python-packages)
    - [SQL](#sql)
  - [ELT Pipeline](#elt-pipeline)
    - [Singer](#singer)
    - [Meltano](#meltano)
    - [Airflow](#airflow)
    - [Data Build Tool (dbt)](#data-build-tool-dbt)
    - [Fivetran](#fivetran)
    - [Docker](#docker)
  - [Google Cloud Platform](#google-cloud-platform)
    - [Kubernetes](#kubernetes)
    - [Cloud Functions](#cloud-functions)
    - [Cloud SQL](#cloud-sql)
    - [Cloud Storage](#cloud-storage)
    - [Artifact Registry](#artifact-registry)
  - [Amazon Web Services](#amazon-web-services)
    - [Elastic Container Service](#elastic-container-service-ecs)
    - [Elastic Kubernetes Service](#elastic-kubernetes-service-eks)
    - [Elastic Container Registry](#elastic-container-registry-ecr)
    - [S3](#s3)
  - [Data Warehouses](#data-warehouses)
    - [BigQuery](#bigquery)
    - [Snowflake](#snowflake)
- [Data Modeling](#data-modeling)
  - [Star Schema](#star-schema)
  - [Snowflake Schema](#snowflake-schema)
- [Environment Setup](#environment-setup)
- [Practice](#practice)

## Mashey Team Culture

Things about our team culture. Include:

- Feedback
- Code Quality
- Testing
- Supporting each other
- Bring your whole-self to work

## Data Engineer Introduction

You are now a Data Engineer, what is that?

### What do Data Engineers do?

From [Real Python](https://realpython.com/):

> Data engineering is a very broad discipline that comes with multiple titles. In many organizations, it may not even have a specific title. Because of this, it’s probably best to first identify the goals of data engineering and then discuss what kind of work brings about the desired outcomes.
>
>The ultimate goal of data engineering is to provide organized, consistent data flow to enable data-driven work, such as:
>
> - Training machine learning models
> - Doing exploratory data analysis
> - Populating fields in an application with outside data
>
>This data flow can be achieved in any number of ways, and the specific tool sets, techniques, and skills required will vary widely across teams, organizations, and desired outcomes. However, a common pattern is the **data pipeline**. This is a system that consists of independent programs that do various operations on incoming or collected data.

Please take a few minutes to read the entire article:

- [What Is Data Engineering and Is It Right for You?](https://realpython.com/python-data-engineer/)

### Overlapping Roles

Data Engineers at Mashey are responsible for a broad range of engineerng practices, including aspects of the roles outlined below. During your onboarding process as a new Data Engineer at Mashey you will not be responsible for the overlapping roles, but it is beneficial to understand how the Data Engineer role will grow as you gain experience.

![beautiful_mind](https://user-images.githubusercontent.com/10391857/104139620-15a97d00-536a-11eb-914a-d92292efb4d4.gif)

#### What do Analytics Engineers do?

It is important to understand where an Analytics Engineer fits between Data Engineers and Data Analysts. Saira Barles, Analytics Engineer at Hubspot describes the differences in this [blog post](https://dataform.co/blog/what-do-analytics-engineers-do) from [Dataform](https://dataform.co/):

> “Data engineers build the cupboard, they gather together the wood and the tools and put it together. The Analytics Engineers open the cupboard and start putting in the plates, mugs, bowls, and arrange them in a certain order. This could be arranging them into particular colours, shapes or sizes. Data analysts then go into the cupboard and they know where everything lives as it is arranged nicely. They can then grab the small blue mug they were looking for and go make a cup of tea!”

Understanding how to design and model data, similar to an Analytics Engineer, will be an extension to the role of Data Engineer at Mashey. It is a separate discipline and takes time to learn, but the ability to fulfill both roles will provide incredible value to our team.

#### What do DevOps Engineers do?

The role of a DevOps engineer will vary from one organization to another, but invariably entails some combination of release engineering, infrastructure provisioning and management, system administration, security, and DevOps advocacy. The Atlassian team has a great DevOps Engineer overview: [here](https://www.atlassian.com/devops/what-is-devops/devops-engineer).

> A DevOps engineer is an IT generalist who should have a wide-ranging knowledge of both development and operations, including coding, infrastructure management, system administration, and DevOps toolchains. DevOps engineers should also possess interpersonal skills since they work across company silos to create a more collaborative environment.
>
> DevOps engineers need to have a strong understanding of common system architecture, provisioning, and administration, but must also have experience with the traditional developer toolset and practices such as using source control, giving and receiving code reviews, writing unit tests, and familiarity with agile principles.

#### What do Cloud Engineers do?

There are generally 3 primary components of Cloud Engineering, which are outlined in this [Northeastern University blog post](https://www.northeastern.edu/graduate/blog/what-does-a-cloud-engineer-do/).

- Cloud Architecture
- Cloud Development
- Cloud Adminstration

> Cloud engineers must refine specific cloud computing skills in order to be successful in their roles. These skills range from software development and database administration to change management and data security.

At Mashey our Data Engineers live in the Cloud, and it's important to eventually be comfortable with fulfilling the above roles within our core Cloud technologies.

## ELT vs ETL

Extract Load Transform vs Extract Transform Load.

## Agile + Scrum

Things about Agile and Scrum.

### Asana

Things about Asana.

## Data Engineering Practices

Our data engineering practices.

## The Mashey Stack

Our core stack.

### Code Quality and Testing

How we test and maintain code quality.

#### CircleCI

CircleCI info.

#### Coveralls

Coveralls info.

#### Codacy or Hound

Codacy or Hound info based on which one I pick.

### Languages

The languages we use.

#### Python

Python Info.

##### Python Packages

- autopep8
- coverage
- coveralls
- poetry
- pylint
- pytest
- pytest-cov
- pytest-mock
- pytest-vcr
- python-dotenv
- requests
- singer-python
- singer-tools
- SQLAlchemy
- vcrpy

#### SQL

SQL Info.

### ELT Pipeline

#### Singer

Singer info.

#### Meltano

Meltano info.

#### Airflow

Airflow info.

#### Data Build Tool (dbt)

DBT info.

#### Fivetran

Fivetran info.

#### Docker

Docker info.

### Google Cloud Platform

#### Kubernetes

Kubernetes info.

#### Cloud Functions

Cloud Functions info.

#### Cloud SQL

Cloud SQL info.

#### Cloud Storage

Cloud Storage info.

#### Artifact Registry

Artifact Registry info.

### Amazon Web Services

#### Elastic Container Service (ECS)

ECS info.

#### Elastic Kubernetes Service (EKS)

EKS info.

#### Elastic Container Registry (ECR)

ECR info.

#### S3

S3 info.

### Data Warehouses

The data warehouses we use.

#### BigQuery

GCP BigQuery.

#### Snowflake

Snowflake.

## Data Modeling

Concepts to architect and model data.

### Star Schema

About Star Schemas.

### Snowflake Schema

About Snowflake Schemas.

## Environment Setup

Setting up a development environment.

## Practice

Things to practice, and how to practice them.
