# SensemakingDataPipeline
A fully automated sensemaking data pipeline using Apache Airflow.

The overarching goal of the project is to make sense of unstructured MIT course catalog data downloaded from the University website and structure it by creating a sensemaking data pipeline which counts word frequency in course titles. The project breaks down the process of making the data pipeline into discrete tasks and uses Airflow to automate each of the tasks. The goal for the project is to run the tasks end to end without needing any human intervention to extract and make sense of the data. Once the pipeline is complete, the data is visualized in word bubbles utilizing the D3 library.
