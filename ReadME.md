# Football CV Detection system

This project consists on training an artificial intelligence system to track football players in the pitch. The model is trained, tested, and then explored in therms of visualization. Each development phase is described below.

## Model training

The model was trained using the [DFL - Bundesliga Data Shootout dataset | https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data] available on Kaggle and on [Roboflow|https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc]. All the training was made in the notebook [PlayerDetection.ipnyb|Player_Detection/Model_Training/PlayerDetection.ipynb] and uploaded to [football-players-detection|https://app.roboflow.com/joao-xpt0j/football-players-detection-6domv/models] page on Roboflow, along with the entire dataset. The model had 94.5% of precision, considered satisfatory for the project.
Also, feel free to use the model at Roboflow.

## Model testing and visualization 
The model was tested in the [football_ai.ipynb|https://github.com/Joao-Alb/Football_CV/blob/master/Player_Detection/Model_Testing/football_ai.ipynb] notebook. The function process_frame only considered predictions with at least 30% of confidence.
The system also considered 3 classes: judges, ball and others (players and goalkeepers) and added anotations into them. Until now, the system doesnt differ the 2 teams.
You can see the demo from this system below:

https://github.com/Joao-Alb/Football_CV/blob/master/Player_Detection/Model_Testing/results/0bfacc_0_result.mp4

