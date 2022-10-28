# aikit_xgboost_demo
Trying an ML experiment to check if the performance improves using Intel powered XGBoost

Steps to run the Intel extended XGBoost
1. Start running aikit_demo.ipynb notebook
2. It sets up aikit-modin library and the Intel extension for XGBoost
3. As the last step, it runs the aikit_xgboost_incidents notebook that actually contains the XGBoost model
4. Make sure the incident_classification_postprocess.csv is present in the same path as the aikit_demo notebook

Step to compare that against the normal XGBoost
5. Open another instance (connecting to a different runtime session that does not have the aikit installed)
6. Clone aikit_xgboost_incident.ipynb and the incident_classification_postprocess.csv files to it
7. Run the notebook 

Note the time elapsed in "model.fit" step in both cases and compare results!
