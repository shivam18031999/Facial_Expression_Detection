# Facial_Expression_Detection
This repoistory contain my project files .
1. first file is facial_expression_detection.ipynb which contain my training part . for training i used the dataset of one of the Kaggle Competition ( link : https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset )  . I used keras for training the model . and then saved my model in the form of json file. 
2. model_json file is a json file which contain model archietecture.
3. main.ipynb is the file which predict the expressions corrosponds to the image . I used Harcascade Classifier for face detection in OpenCv  to detect face in the image
and then used my model which is saved in the form of json file to predict the class(i.e.. expression) 
