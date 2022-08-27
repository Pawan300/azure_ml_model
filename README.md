# Azure ML model

Successfully created two scenario.

First : 
      
      - Saved input data in datalake.
      - Created notebook in databricks :
             - Fetched data from datalake
             - trained a model on that.
             - Registered that model in Azure ML studio via azureml library.
             - Deployed the model with config file, score.py file. 
      - Created a pipeline in ADF and run this notebook successfully.
      - Tested model in the evironment
      

Second :

      - Saved input data in datalake.
      - Created a notebook in databricks:
             - Fetched data from datalake.
             - Trained a model and monitor using mlflow.
      - Created another notebook in databricks:
             - Fetched run_id of the job and registered it in AzureML environment.
             - Deployed the model with config file, score.py file.
      - Created a pipeline in ADF with two notebook activity and linked both. 
      - Tested model in the environment.
