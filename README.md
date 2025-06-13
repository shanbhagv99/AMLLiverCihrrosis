v6 in the MLFlow tracking versions folder contains the code for the model with the best log loss and the one that was used for the submissions on Kaggle

A new Databricks account(community edition) must be created, and one must manually enter the workspace link for the same along with your user credentials manually when running the notebook in order to log your experiments with MlFlow 
to the server managed by DataBricks

In V7 - I fixed the issue with dynamically logging the current notebook to DataBricks and added code to log the models developed to the model registry. I also cleaned up the code and made it more efficient in general.
