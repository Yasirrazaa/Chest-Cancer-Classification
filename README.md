# End to End Chest Cancer Classification using;
- Deep Learning (CNN)
- MLFLOW
- Docker 
- DVC

## Workflows
 1. Update config.yam1
 2. Update secrets.yam1 [Optional]
 3. Update params yaml
 4. Update the entity
 5. Update the configuration manager in src config
 6. Update the components
 7. Update the pipeline
 8. Update the main.py
 9. Update the dvc.yaml


## Dagshub and MLFlow
- Dagshub is a platform for ML experiment management, version control, and collaboration. It enables data scientists to easily track experiments, visualize results, and collaborate with team members.

'''MLFLOW_TRACKING_URI=https://dagshub.com/Yasirrazaa/End-to-End-Chest-Cancer-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=Yasirrazaa \
MLFLOW_TRACKING_PASSWORD=fa8be8cc5343a9aecd2ae1240f1605a31a17b457 \
python script.py'''