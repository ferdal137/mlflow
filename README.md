# MLflow
Este repositorio contiene proyectos de Machine Learning utilizando MLflow para gestionar los ciclos de vida de los modelos, incluyendo experimentación, reproducción y despliegue de modelos.

<p align="center">
  <img src="https://techcommunity.microsoft.com/t5/image/serverpage/image-id/420557i0319A4181851485A/image-size/original?v=v2&px=-1" width="50%">
</p>

## What is MLflow?
MLflow is a solution to many of these issues in this dynamic landscape, offering tools and simplifying processes to streamline the ML lifecycle and foster collaboration among ML practitioners.
MLflow provides a unified platform to navigate the intricate maze of model development, deployment, and management. MLflow aims to enable innovation in ML solution development by streamlining otherwise cumbersome logging, organization, and lineage concerns that are unique to model development. This focus allows you to ensure that your ML projects are robust, transparent, and ready for real-world challenges.

## Core Components of MLflow
MLflow, at its core, provides a suite of tools aimed at simplifying the ML workflow. It is tailored to assist ML practitioners throughout the various stages of ML development and deployment. Despite its expansive offerings, MLflow’s functionalities are rooted in several foundational components:

- **Tracking**: MLflow Tracking provides both an API and UI dedicated to the logging of parameters, code versions, metrics, and artifacts during the ML process. This centralized repository captures details such as parameters, metrics, artifacts, data, and environment configurations, giving teams insight into their models’ evolution over time. Whether working in standalone scripts, notebooks, or other environments, Tracking facilitates the logging of results either to local files or a server, making it easier to compare multiple runs across different users.

- **Model Registry**: A systematic approach to model management, the Model Registry assists in handling different versions of models, discerning their current state, and ensuring smooth productionization. It offers a centralized model store, APIs, and UI to collaboratively manage an MLflow Model’s full lifecycle, including model lineage, versioning, aliasing, tagging, and annotations.

- **MLflow Deployments for LLMs**: This server, equipped with a set of standardized APIs, streamlines access to both SaaS and OSS LLM models. It serves as a unified interface, bolstering security through authenticated access, and offers a common set of APIs for prominent LLMs.

- **Evaluate**: Designed for in-depth model analysis, this set of tools facilitates objective model comparison, be it traditional ML algorithms or cutting-edge LLMs.

- **Prompt Engineering UI**: A dedicated environment for prompt engineering, this UI-centric component provides a space for prompt experimentation, refinement, evaluation, testing, and deployment.

- **Recipes**: Serving as a guide for structuring ML projects, Recipes, while offering recommendations, are focused on ensuring functional end results optimized for real-world deployment scenarios.

- **Projects**: MLflow Projects standardize the packaging of ML code, workflows, and artifacts, akin to an executable. Each project, be it a directory with code or a Git repository, employs a descriptor or convention to define its dependencies and execution method.
