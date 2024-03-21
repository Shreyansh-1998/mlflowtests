## ML Flow test

### MLflow is an open-source platform, purpose-built to assist machine learning practitioners and teams in handling the complexities of the machine learning process. MLflow focuses on the full lifecycle for machine learning projects, ensuring that each phase is manageable, traceable, and reproducible.

Follow this for more [https://mlflow.org/docs/latest/index.html]

<<<<<<< HEAD
=======

>>>>>>> 87d466ae052bc8d8d988c461e9b20d57798e3f3d
Important: Create a virtual environment 
```
 conda create -n your_env python==3.9 -y
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
<<<<<<< HEAD
Have a look at my mlflow run.[https://dagshub.com/Shreyansh-1998/mlflowtests.mlflow/#/experiments/0?searchFilter=&orderByKey=attributes.start_time&orderByAsc=false&startTime=ALL&lifecycleFilter=Active&datasetsFilter=W10%3D&modelVersionFilter=All%20Runs&selectedColumns=attributes.%60Source%60,attributes.%60Models%60,attributes.%60Dataset%60&compareRunsMode=CHART&compareRunCharts=W3sidXVpZCI6IjE3MTEwMjYyNjM3NjltdDc4MTEwbCIsInR5cGUiOiJCQVIiLCJydW5zQ291bnRUb0NvbXBhcmUiOjEwLCJtZXRyaWNLZXkiOiJtYWUifSx7InV1aWQiOiIxNzExMDI2MjYzNzY5YjkzMnQ1am0iLCJ0eXBlIjoiQkFSIiwicnVuc0NvdW50VG9Db21wYXJlIjoxMCwibWV0cmljS2V5Ijoicm1zZSJ9LHsidXVpZCI6IjE3MTEwMjYyNjM3Njk5eTNxbGFyMSIsInR5cGUiOiJCQVIiLCJydW5zQ291bnRUb0NvbXBhcmUiOjEwLCJtZXRyaWNLZXkiOiJyMiJ9LHsidXVpZCI6IjE3MTEwMjYyNjM3NjlndG80OHoybiIsInR5cGUiOiJQQVJBTExFTCIsInJ1bnNDb3VudFRvQ29tcGFyZSI6MTAsInNlbGVjdGVkUGFyYW1zIjpbXSwic2VsZWN0ZWRNZXRyaWNzIjpbXX1d]
=======
>>>>>>> 87d466ae052bc8d8d988c461e9b20d57798e3f3d
