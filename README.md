## ML Flow test

### MLflow is an open-source platform, purpose-built to assist machine learning practitioners and teams in handling the complexities of the machine learning process. MLflow focuses on the full lifecycle for machine learning projects, ensuring that each phase is manageable, traceable, and reproducible.

Follow this for more [https://mlflow.org/docs/latest/index.html]
Important: Create a virtual environment 
```
 conda create -n your_env python==3.9 -y
 ```
 conda activate your_env
 ```


Steps:
1. install requirements with mlflow==2.5.0
2. For local run:
``` 
python your_file.py
```
3. For using mlflow ui in vsc terminal
``` 
mlflow ui
```

For remote server, Dagshub is being used as it is an opensource platform.
You can connect it with AWS sagemaker, Ec2 instance etc.

1. Open dagshub[https://dagshub.com/]
2. Connect to your git repository that needs tracking.
3. Export remote uri using git bash
```
export uri 
export username
export password
```
4. Run this on bash and update the code with 2 changes
```
remote_server_uri= "your uri"
mlflow.set_tracking_uri(remote_server_uri)
```
Try using AWS or google instances to do the same.