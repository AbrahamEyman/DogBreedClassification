README FOR DOG BREED CLASSIFICATION 
ABE EYMAN CASEY & SAMEER PATEL

DATA:        
training data must be downloaded from - 
https://www.kaggle.com/c/dog-breed-identification/data?select=train

preprocessed_saves - user made splits of test and training data  
*note* using only "training" data from the kaggle link but users split that data into .85/.15 training and testing for the sake of having an answer key

labels - picture ids and their correct corresponding dog breed 

CODE:   
model_creation.ipynb - code used to train and create the model   
(**THIS CAN TAKE 9 HOURS TO RUN. DO NOT JUST RUN ALL WITHOUT READING THROUGH**)

predict_one_picture.ipynb - code to read in the saved model and use it to predict one picture and classify the breed of the dog

main_app.py - used to run a streamlit app on your local machine. Use "streamlit run main_app.py" in a terminal