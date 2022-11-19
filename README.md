A machine learning pipeline is a way to codify and automate the workflow it takes to produce a machine learning model. Machine learning pipelines consist of multiple sequential steps that do everything from data extraction and preprocessing to model training and deployment.

What Are the Benefits of a Machine Learning Pipeline?

The Manual Cycle
we tend to start with a manual workflow, where no real infrastructure exists. The data collection, data cleaning, model training and evaluation are likely written in a single notebook. The notebook is run locally to produce a model, which is handed over to an engineer tasked with turning it into an API endpoint. Essentially, in this workflow, the model is the product.


The Automated Pipeline
Once we move from a stage where they are occasionally updating a single model to having multiple frequently updating models in production, a pipeline approach becomes paramount. In this workflow, we don’t build and maintain a model. we develop and maintain a pipeline. The pipeline is the product.
