# Zenstra
This repository houses the source code for the project that we are working on for Provathon. The Heart Disease Prediction API is a solution based on Machine Learning that can predict the risks of heart disease using an API that can be integrated. Originally developed under Zen's alias, but later moved to this new repository under real name.
# Description:
Our solution is built on the architecture of microservices, and the AI Model may easily be utilised independently on any other platform. We have also included a demonstration dashboard for our smart watch simulator. On this dashboard, we are able to receive a patient's real-time health data directly from the patient's smart watch and then use those values to obtain a real-time prediction of the immediate risk of heart attacks in a patient. This real-time forecast is also modelled as a continuous graph in order to provide patients with early warning in the event that there are any potential concerns.
In a comparable manner, our application programming interface (api) may be coupled with any smart watches, hospital management systems, or health apps to get a real-time forecast of imminent risks of heart attacks.


# Instructions:
clone the heart-disease-api repository from https://github.com/aashutoshsapkota/heart-disease-api.git then navigate to the SmartWatch Dashboard directory in the heart-disease-api repository.
pip install django requests django-cors-headers with numpty pickle tops
runserver with the command python manage.py


## Installation: 

"cd heart-disease-api/api && pip install flask pickle numpy flask-cors && python Deployed_Flask_App.py && cd .. && python smartwatch_simulator.py"

## Run Simulator: 
"cd heart-disease-api && python smartwatch_simulator.py"

## Probable Sample Result:( runs at port 8000 on your local host)

{
  "status":"success",
  "value":"92",
  "risk":true,
}


    "status" : reports whether the prediction was successful or not, with a value of "success" or "error"
    "value" : a confidence score for the prediction, represented as a string
    "risk" : a boolean value indicating whether the risk of heart disease is considered high, with a default threshold of 75%.
