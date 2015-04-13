README

run this jar with:
java -jar StatPredictor.jar

This is a simple program to predict what stats are needed by a basketball team to win a game.  I works by inputting the location (h, n, a) and then the halftime stats for your team.  Then input the season averages for your oppenent.  After that select 0 or more stats to focus on and click the "Calculate Magic Numbers" button and the result fields will be populated.  At this stage if you want to run the program with different focus values, it is best to restart and enter data again.

IN THIS FOLDER:
byu_avgs.arff- arff file that lists BYU's 2014-2015 season averages.  This file is loaded by the program to aid in prediction.

averages.txt- a file containing the season averages for every team in DI basketball compiled by Reed Wilson and labeled by a team's usual abbreviation (i.e. BYU, USU (Utah State), UK (Kentucky))

selectedSeasonAvgs.xlsx- an excel sheet showing the season averages for a few teams used to test the model.  This is simply a more readable form of these team's stats int he averages.txt file

2015-tourney-mlp.model- The Multi-Layer Perceptron that was trained with WEKA software to predict wins and losses.