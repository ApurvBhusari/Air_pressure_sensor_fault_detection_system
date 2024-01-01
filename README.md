# AWS Deployed Link
http://ec2-35-154-111-197.ap-south-1.compute.amazonaws.com:8080

# Sensor-Fault-Detection

### Problem Statement
The Air Pressure System (APS) is a critical component of a heavy-duty vehicle that uses compressed air to force a piston to provide pressure to the brake pads, slowing the vehicle down. The benefits of using an APS instead of a hydraulic system are the easy availability and long-term sustainability of natural air.

This is a Binary Classification problem, in which the affirmative class indicates that the failure was caused by a certain component of the APS, while the negative class
indicates that the failure was caused by something else.

### Solution Proposed 
In this project, the system in focus is the Air Pressure system (APS) which generates pressurized air that are utilized in various functions in a truck, such as braking and gear changes. The datasets positive class corresponds to component failures for a specific component of the APS system. The negative class corresponds to trucks with failures for components not related to the APS system.

The problem is to reduce the cost due to unnecessary repairs. So it is required to minimize the false predictions.
## Tech Stack Used
1. Python 
2. FastAPI 
3. Machine learning algorithms
4. Docker
5. MongoDB

## Infrastructure Required.

1. AWS S3
2. AWS EC2
3. AWS ECR
4. Git Actions
5. Terraform

## How to run?
Before we run the project, make sure that you are having MongoDB in your local system, with Compass since we are using MongoDB for data storage. You also need AWS account to access the service like S3, ECR and EC2 instances.

## Data Collections
![image](https://user-images.githubusercontent.com/57321948/193536736-5ccff349-d1fb-486e-b920-02ad7974d089.png)


## Project Archietecture
![image](https://user-images.githubusercontent.com/57321948/193536768-ae704adc-32d9-4c6c-b234-79c152f756c5.png)


## Deployment Archietecture
![image](https://user-images.githubusercontent.com/57321948/193536973-4530fe7d-5509-4609-bfd2-cd702fc82423.png)


# neurolab-mongo-python

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```

To download your dataset

```
wget https://raw.githubusercontent.com/avnyadav/sensor-fault-detection/main/aps_failure_training_set1.csv
```

This is changes made in neuro lab

Git commands

If you are starting a project and you want to use git in your project
```
git init
```
Note: This is going to initalize git in your source code.


OR

You can clone exiting github repo
```
git clone <github_url>
```
Note: Clone/ Downlaod github  repo in your system


Add your changes made in file to git stagging are
```
git add file_name
```
Note: You can given file_name to add specific file or use "." to add everything to staging are


Create commits
```
git commit -m "message"
```

```
git push origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name 

To push your changes forcefully.
```
git push origin main -f
```


To pull  changes from github repo
```
git pull origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name


.env file has
```
MONGO_DB_URL="mongodb://localhost:27017"
AWS_ACCESS_KEY_ID="aagswdiquyawvdiu"
AWS_SECRET_ACCESS_KEY="sadoiuabnswodihabosdbn"
```

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu
newgrp docker
```


```


AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
AWS_ECR_LOGIN_URI=
ECR_REPOSITORY_NAME=
BUCKET_NAME=
MONGO_DB_URL=
```
# ELASTIC CONTAINER REGISTRY
![Screenshot (1463)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/05bacf0d-3736-4650-83ce-be2f677ddfe2)
![Screenshot (1463)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/dc3925af-5db3-4246-a044-8b705cf27741)
![Screenshot (1464)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/91e388b5-436a-4ba7-b269-657a06ac3c89)

# IAM 
![Screenshot (1469)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/cfff4f3c-2458-4a56-bf05-cfc69db532b1)

# EC2 INSTANCE
![Screenshot (1465)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/71a49a51-24e8-406a-a68a-a461425921e7)
![Screenshot (1466)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/6e8df7df-19cf-4fe5-b48e-868a77d91f24)
![Screenshot (1485)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/cf9529b9-7fc6-4ab1-8c8b-9cfa2799b7a0)

# MONGODB DATABASE 
![Screenshot (1471)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/bc12202e-f32f-4977-8294-80b544fa2b5f)

# AWS CLI
![Screenshot (1475)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/37cca203-7c63-4f39-ab85-26b6dce06490)

# SUCCESSFULLY DEPLOYED ON AWS
![Screenshot (1486)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/592f5102-fcdb-4b94-a840-78a95f35ff26)

# AIRFLOW TO TRAIN  AND TRACK DEPLOYED PRODUCT ON AWS
![Screenshot (1441)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/4a0ac3c2-fd60-4f0d-a805-10531c45dcde)
![Screenshot (1443)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/df804333-cf3c-430d-ae4b-5abd7db5f029)
![Screenshot (1444)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/d4432356-1742-4d85-ae1e-ac6a6fdbb99d)
![Screenshot (1445)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/8e65ed6d-dca0-4c81-b6f3-d16dfb9c5a70)
![Screenshot (1446)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/14fd375e-33ee-4aaf-aa3d-edd2db1e2466)
![Screenshot (1447)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/b092f0a1-5e22-485f-b8ec-66d173a1e694)
![Screenshot (1448)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/efd39518-2835-4ebb-85fe-0b658bf375c8)
![Screenshot (1449)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/002e8227-43c1-4745-9fca-7170c68af5ac)
![Screenshot (1450)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/c4fdf89e-aea4-47d0-98e3-c6fa1ed04a69)
![Screenshot (1451)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/7bdbee48-1d41-4704-b59d-a70dab59166c)
![Screenshot (1452)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/f51e0106-c357-4666-b09a-e3f17fe4a06a)
![Screenshot (1453)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/f28e4aa8-431e-4bde-828e-efb20ddf14e7)
![Screenshot (1454)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/fa90f01b-5a33-4af2-9f27-e80860e1964a)
![Screenshot (1455)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/ef83dc50-2d71-488f-85ad-39eaa2aa2810)
![Screenshot (1456)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/38381412-c3a2-4c02-b21a-264744689401)
![Screenshot (1458)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/05bd4217-9fe0-420c-9c52-cb8a10387738)
![Screenshot (1461)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/e19717b9-08c5-4721-90a1-45b4a37c6666)
![Screenshot (1462)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/28f80bc4-4a89-4a66-aa78-63b972b10afe)

# AWS S3 BUCKET
 s3 bucket to download  the file and get prediction and that prediction file will be uploaded to the s3 bucket 
![Screenshot (1467)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/3a791108-d684-4c1a-9a80-204496459368)
![Screenshot (1468)](https://github.com/ApurvBhusari/Air_pressure_sensor_fault_detection_system/assets/80256026/fdc24340-b74e-4799-8c8c-1bcabe90fa38)























