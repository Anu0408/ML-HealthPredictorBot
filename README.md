# Chatbot for disease prediction and treatment recommendation using machine learning

This project implements a chatbot that predicts diseases and recommends treatments using machine learning algorithms such as Naive Bayes and Decision Tree. Built with Python 3.6, Flask, and ChatterBot, the chatbot analyzes user-reported symptoms to provide accurate health insights and treatment recommendations. The system utilizes a preprocessed medical dataset for training and employs natural language processing to interpret user inputs.

## Built With 
#### A web implementation of [ChatterBot](https://github.com/gunthercox/ChatterBot) using Flask.
- Python 3.6
- Flask==0.11
- ChatterBot==0.8.4
- SQLAlchemy==1.1.11

## Features
- Disease prediction based on user symptoms
- Treatment recommendations
- Interactive web-based interface

### Prerequisites
- Python 3.6
- pip (Python package installer)

## Local Setup:
#### 1. Install dependencies: Open command prompt and locate folder. run 'pip install -r requirements.txt' 
#### 2. Train the Chatbot: Run *train.py*
#### 3. Run the application: *run.py*
#### 4. Acess the Demo: Demo will be live at http://localhost:5000/

## Files and Directories
- train.py: Script to train the chatbot using predefined datasets.
- run.py: Script to start the Flask web server.
- main.py, main_1.py: Additional scripts for various functionalities.
- chatbot_database/: Directory containing training data files.
- db.sqlite3: SQLite database file.
- requirements.txt: List of Python packages required to run the application.
- README.md: This README file.
- Human-Disease-Prediction-using-Machine-Learning-Algorithms-master.zip: Project archive file.
- Training.csv, Testing.csv: Datasets for training and testing the model.

## Usage
Once the application is running, you can interact with the chatbot to get disease predictions and treatment recommendations. Simply input your symptoms, and the chatbot will analyze them to provide a potential diagnosis and suggested treatments.

## License
This source is free to use, but ChatterBot does have a license which still applies and can be found on the [LICENSE](https://github.com/gunthercox/ChatterBot/blob/master/LICENSE) page.

## Acknowledgments
- The [ChatterBot](https://github.com/gunthercox/ChatterBot) library for providing the chatbot framework.
- The Flask framework for enabling web application development.
