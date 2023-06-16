# This is the Machine Learning repos of EduSign

<p align="center"> <img src="https://cdn.discordapp.com/attachments/755446353643176051/1112727753289117776/capstone.png" width="600" height="360" /> </p>

<div align="center">
  <p align="center">
    <a href="https://github.com/TheSalmonSushi/EduSign"><strong>Back to the main repository</strong></a>
  </p>
</div>

## What's inside of this repos??

Welcome to EduSign project repository for the machine learning part! 

This repository contains the process of developing machine learning as a complementary feature in the EduSign application as part of Bangkit 2023's Product-based Capstone Project.

## How can you clone the project??:
You can clone this repository with this methods:
* HTTPS: Use Git or SVN checkout by making use of this URL: https://github.com/Kimitozuki/EduSign-ML.git
  ```sh
  git clone https://github.com/Kimitozuki/EduSign-ML.git
  ```
* GitHub CLI: Write this on the command line: 
  ```sh
  gh repo clone Kimitozuki/EduSign-ML
  ```

## Technology Used for ML Repo
   - [Tensorflow](https://www.tensorflow.org/)
   - [Python](https://www.python.org/)
   - [Flask](https://flask.palletsprojects.com/en/2.3.x/)
   - [MediaPipe](https://developers.google.com/mediapipe/solutions)

## Dataset Resources
   - [Kaggle - Google ISLR](https://www.kaggle.com/competitions/asl-signs/overview)
   - [Kaggle - WASL](https://www.kaggle.com/datasets)
   - [WLASL: A large-scale dataset for Word-Level American Sign Language](https://github.com/dxli94/WLASL)

## API URL Created by CC Team
Flask API URL: [https://flaskapp-cr-v4-cky5j3e4sq-et.a.run.app/](https://flaskapp-cr-v4-cky5j3e4sq-et.a.run.app/)

## Installing FastAPI App
  - Download the repo/clone it. Make it available on your device
  - Open terminal and go to the project's app directory
  - Type `python -m venv env` and press enter (create virtual environment)
  - For Windows user, type `env\Scripts\activate`. For Linux, type `source ./env/bin/activate` (accessing the virtual environment)
  - Type `pip install -r requirements.txt` (installing the requirements)
  - Serve the app by typing `python main.py`
  - It will run on `http://127.0.0.1:5000`

## Sign Language Recognition Endpoint
| Endpoint | Method |           Body Sent          |                 Description                |
|:--------:|:------:|:-----------------------------------:|:------------------------------------------:|
|     /predict    |  POST  |                 Video file:  'video'               | HTTP POST REQUEST Prediction Endpoint |

## How to predict image with Postman
  - Open Postman App
  - Enter URL request bar with `http://127.0.0.1:8000/predict`
  - Select method POST
  - Go to Body tab and select form-data
  - Change key from form-data with file, with name `video`
  - Input the video that you want predict as a value of the key
  - Send the request

## Model Architecture
![image](https://github.com/Kimitozuki/EduSign-ML/blob/main/asset/ModelArchitecture.jpg)
