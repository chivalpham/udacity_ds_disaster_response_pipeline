# Udacity Disaster Response Pipeline
# Description
This Project is one part of the Data Science Nanodegree Program by Udacity in collaboration with Figure Eight. In this project, we will analyze disaster data set containing real messages that were sent during disaster events to build a model for an API that classifies disaster messages.

The Project is split up into the following sections:

1. Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure
2. Machine Learning Pipeline to train a model able to classify text message in categories
3. Web App to show model results in real time.

# Files:

# Data:

disaster_categories.csv and disaster_messages.csv: contain the data on which the model was trained in.
process_data.py: contain the ETL pipeline.
DisasterResponse.db: this is the output of running the ETL pipeline.

# Models:

train_classifier.py: contain ML pipeline
starting_verb_extractor.py : this is a class used for expanding the model creating a starting verb extractor as a feature.
App:

run.py: this is used as the main file for starting the web app.

# Instructions:

1. Link to GitHub Repository:
https://github.com/chivalpham/udacity_ds_disaster_response_pipeline

2. Run the following commands in the project's root directory to set up your database and model.

3. To run ETL pipeline that cleans data and stores in database, delete the DisasterResponse.db file if it has been created before and run the following code: python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves: python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run your web app: python run.py
