# Sensor-Fault-Detection

### Problem Statement
The Air Pressure System (APS) is a vital part of a heavy-duty vehicle, utilizing compressed air to drive a piston that applies pressure to the brake pads, thereby decelerating the vehicle. Compared to a hydraulic system, APS offers advantages such as the easy accessibility and long-term sustainability of natural air.

This is a Binary Classification problem, in which the affirmative class indicates that the failure was caused by a certain component of the APS, while the negative class indicates that the failure was caused by something else.

### Solution Proposed 
The dataset comprises of numerical values corresponding to many sensors involved in the APS brake system. Data streamed from these senors are streamed and stored on a MongoDB database through Kafka confluent (demonstrated in https://github.com/gsimethy/fault-detection-data-collection). This data is ingested in to ML pipeline which involves data ingestion, data preprocessing, data transformation, data evaluation, model trainining, model evaluation and finally model deplyoment on AWS as a FastAPI. 

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
4. Github Actions


## Data Collections
![image](https://user-images.githubusercontent.com/57321948/193536736-5ccff349-d1fb-486e-b920-02ad7974d089.png)


## Project Archietecture
![image](https://user-images.githubusercontent.com/57321948/193536768-ae704adc-32d9-4c6c-b234-79c152f756c5.png)

