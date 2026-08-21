# Data-science-project

import dagshub
dagshub.init(repo_owner='GauravBidaeet', repo_name='Data-science-project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)