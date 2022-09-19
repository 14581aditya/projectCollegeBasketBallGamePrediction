# projectCollegeBasketBallGamePrediction
# Machine-Learning-Group-Project
# NCAA March Madness Prediction
Authors: Bryson Neel, Aditya Mishra, Garrett Shimek
University of Texas at Arlington
CSE 4309-001 Intro to Machine Learning

--- Final_Project.py ---

1. usage

	Can run the file via python command line. Example command:

	python Final_Project.py 

	No command line arguments are needed.

	You can also run this file on google colab.

2. Results

	The file will print out two accuracy stastics for the algorithm to the command-line. It will also
  create a filecalled bracket_predicts.txt. This file contains all the predicted probability values for
  each matchup between two teams in the 2018-2019 NCAA Men's Basketball Tournament.


--- .csv files ---
1. matches18-10.csv
	
	This file contains the data for all the games played in the 2018-2019 season for the NCAA Division I
  Men's Basketball League.

2. players18-19.csv

	This file contains the individual stats for the year 2018-2019 for each player in the NCAA Division I
  Men's Basketball League.

3. teams18-19.csv

	This file contains the team stats for 2018-2019 for each team in the NCAA Division I Men's Basketball
  League.

4. actual_results.csv

	This file contains the results for the NCAA Division I Men's Basketball Tournament. The teams that
  won in a round are placed on the same line. The tournament starts with 64 teams, so the first round
  has 32 winners. So, 32 nameson the first line. Then 16 names on the second line, and so on and so
  forth, until there is only 1 name on a line.

5. bracket_matchups.csv

	This file is used to contain the matchups for the tournament. It contains all the matchups necessary
  to predict the outcome of the tournament. Since these are predictions the scores are all set to zero.
  The first 32 lines contain all the initial matchups for round 1. Then, based on the predictions, the
  next 16 lines were added. Then based on those, the next 8 were added. This process was repeated until
  all the matchups necessary were added to the file.

