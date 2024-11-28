# Learning Astronomer and Airflow: Hands-On Projects

This repository showcases two projects that explore ETL (Extract, Transform, Load) pipelines using Astronomer and Apache Airflow. These projects focus on implementing workflows to fetch and process data efficiently while demonstrating the power and flexibility of Airflow as a data orchestration tool.

## Why Airflow and Astronomer?

- Apache Airflow: A robust workflow orchestration tool that makes it easy to define, schedule, and monitor complex workflows. It allows for creating ETL pipelines with clear visibility into each task's status and enables seamless integration with various data sources.
- Astronomer: A managed platform for running Apache Airflow at scale. Astronomer simplifies Airflow deployment, provides enhanced observability, and supports collaborative workflow development.

These tools are ideal for learning and implementing ETL pipelines due to their flexibility, scalability, and active support in the data engineering community.

## Projects Overview

### Project 1: Astronomer Fetch and Print

This project demonstrates a simple workflow designed to fetch and process astronomical data.

**Features:**

- Fetches data related to astronomical objects or events from a public API.
- Processes and prints the data in a structured format for further use or analysis.

**Purpose:**
To get hands-on experience with task definition and scheduling using Airflow, leveraging Astronomer's managed platform.

### Project 2: Weather API Data Pipeline

This project focuses on creating a complete ETL pipeline for weather data.

**Features:**

- Data Source: Fetches weather data from the open-source Meteo API.
- ETL Workflow:
  - Extract: Queries the Meteo API for weather data.
  - Transform: Processes and cleans the raw data for consistency and usability.
  - Load: Stores the transformed data into a target storage (e.g., local files or a database).
- Airflow Workflow:
  - The ETL tasks are implemented as an Airflow DAG (Directed Acyclic Graph) to automate and orchestrate the pipeline.

**Purpose:**
To gain experience in building, scheduling, and monitoring ETL workflows using Airflow, and to understand how Astronomer simplifies deployment and observability.

## How to Use This Repository

1. Clone the Repository:

   ```bash
   git clone https://github.com/NeelDevenShah/astro-projects.git
   cd <repo-directory> (As per the project)
   ```

2. Set Up the Environment:
   Follow the provided instructions in each project folder to set up dependencies and initialize Airflow.

3. Run the Pipelines:

   - For the Astronomer project, use the Astronomer CLI to deploy and monitor workflows.
   - For the Airflow project, trigger the DAGs from the Airflow UI or CLI.

4. Explore and Learn:
   Modify and expand the pipelines to explore more features and workflows.

## Conclusion

These projects highlight the power of Airflow and Astronomer for building reliable and scalable ETL pipelines. The repository is a stepping stone for learning workflow orchestration and mastering the tools used in modern data engineering workflows.
