# Face-and-Facial-Emotion-Recognition-Application
Trained a model that identifies the person in image along with the expression on their face.  
Tools/Technologies used: Python, Django, TensorFlow, OpenCV.
## INTRODUCTION
Face recognition is a broad challenge of verifying or identifying people in pictures. Many
attempts have been made to understand the process of how human beings recognize human
faces. It is widely accepted that face recognition may depend on both componential information
(such as eyes, mouth and nose) and non-componential/holistic information (the spatial relations
between these features). Face recognition is currently being used to make the world safer,
smarter, and more convenient. In addition if facial emotion is included it makes the application
more profound. Face detection is generally the first step towards many face-related applications
like face recognition or face verification. Now we know the exact coordinates/location of the
face, so we extract this face for further processing.

In the current project we address one of the computer vision tasks. The idea of this project is to
build a system that takes the image as input and does face identity recognition with facial
emotion. Face Recognition is a method of identifying or verifying the identity of an individual by
using their face. The first task that we perform is detecting faces in the image(photograph). Now
we know the exact coordinates/location of the face, so we extract this face for further processing.

Next is Feature Extraction. We cropped out the face from the image, so we extract specific
features from it. As we know a neural network takes an image of the face of the person as input
and outputs a vector that represents the most important features of a face.

In the Artificial Intelligence field, Computer Vision is one of the most interesting and
challenging tasks. Computer Vision acts as a bridge between Computer Software and
visualizations. Computer Vision allows computer software to understand and learn about the
visualizations in the surroundings. Based on the componential information (such as eyes, mouth
and nose) that identify the person. This task is very easy for the human brain but in the Computer
Vision pipeline, first, we need to gather the data, then we perform the data processing operations,
and then we train and teach the model to understand how to distinguish between the faces based
on its componential information (such as eyes, mouth and nose).


## Project Phase - 1 : Face Recognition and Person Identity
- Gather Images
- Extract Faces only from Images
- Labeling (Target output) Images
- Data Preprocessing
- Training Face Recognition with OWN Machine Learning Models.
  - Logistic Regression
  - Support Vector Machines
  - Random Forest Classifier
- Combine All Machine Learning Models using **Ensemble Technique** with **Voting Classifier** 
- Tuning Machine Learning Model
- Model Evaluation
  - Precision
  - Recall
  - Sensitivity
  - Specificity
  - F1 Score
  - Accuracy
## Project Phase - 2: Train Facial Emotion Recognition
- Gather Emotion Images
- Data Preprocessing
- Train Machine Learning Models with OWN Machine Learning Models.
  - Logistic Regression
  - Support Vector Machines
  - Random Forest Classifier
- Combine All Machine Learning Models using Ensemble Technique with Voting Classifier
- Tuning Machine Learning Model
- Model Evaluation
  - Precision
  - Recall
  - Sensitivity
  - Specificity
  - F1 Score
  - Accuracy
## Project Phase -3: Django Web App Developed in Local (Computer)
- Setting Virtual Environment
- Face Recognition Django Project
  - Models Views Templates (MVT)
- Design SQLite Database in Django
- Store Uploaded Image in Database
- Integrate Machine Learning to Django
  - MVT + Machine Learning Framework


## Output Screenshot
![Screenshot from 2022-05-07 14-58-31](https://user-images.githubusercontent.com/11390264/186408535-b6a3d8c9-2cf6-42f0-8204-e71dd90d140d.png)

![Screenshot from 2022-05-07 14-59-03](https://user-images.githubusercontent.com/11390264/186408591-21e27163-2308-4859-8d92-bcfba671df8e.png)

![Screenshot from 2022-05-07 14-59-19](https://user-images.githubusercontent.com/11390264/186408610-e3554fb1-fd47-4cf0-9c56-930c75727d88.png)



