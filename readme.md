  https://github.com/dmatrix/mlflow-workshop-part-1/tree/master

## What is ``Mlflow``?

``Mlflow`` is a library which manages the lifecycle of machine learning models. Mlflow provides 4 modules:

- [``Mlflow Tracking``](https://www.mlflow.org/docs/latest/tracking.html): This modules focuses on experiment versioning. Its goal is to store all the objects needed to reproduce any code execution. This includes code through version control, but also parameters and artifacts (i.e objects fitted on data like encoders, binarizers...). These elements vary wildly during machine learning experimentation phase. ``Mlflow`` also enable to track metrics to evaluate runs, and provides a *User Interface* (UI) to browse the different runs and compare them.
- [``Mlflow Projects``](https://www.mlflow.org/docs/latest/projects.html): This module provides a configuration files and CLI to enable reproducible execution of pipelines in production phase.
- [``Mlflow Models``](https://www.mlflow.org/docs/latest/models.html): This module defines a standard way for packaging machine learning models, and provides built-in ways to serve registered models. Such standardization enable to serve these models across a wide range of tools.
- [``Mlflow Model Registry``](https://www.mlflow.org/docs/latest/model-registry.html): This modules aims at monitoring deployed models. The registry manages the transition between different versions of the same model (when the dataset is retrained on new data, or when parameters are updated) while it is in production.

For more details, see [Mlflow's official documentation](https://www.mlflow.org/docs/latest/index.html).
