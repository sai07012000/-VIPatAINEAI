# -VIPatAINEAI
# Project 7:  Statistical Analysis and Hypothesis Testing

# Project :  Increasing YoY revenue from game purchases by increasing retention rate of gamers
# About the project:
The project involves working on data related to Cookie Cats – a hugely popular puzzle game. As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in the player's enjoyment of the game being increased and prolonged. But where should the gates be placed and how the placement of the gates can retain the players for more time.

The project requires you to:

1.Perform exploratory data analysis of the given datasets and generate their statistical summary.
2.Perform A/B testing between the two groups of data to analyze the impact on player retention if the first gate in Cookie Cats is moved from level 30 to level 40.

# Tools to Use: 
Python (preferred) or R Programming.

# Aim: 
Even though the overall subscription for the game is growing, the revenue from in-game purchases has been declining and many players are uninstalling the game after playing for a few days. What recommendations can you suggest increasing the in-game purchase and retaining the players?
# Objectives/Exercise:

The overall objective of the project is to test the company’s CEO’s hypothesis that moving the first gate from level 30 to level 40 increases retention rate and the number of game rounds played. The CEO believes that players are churning because the first gate encountered at level 30 is too early which forces players to wait before they can proceed further in the game.

 In order to increase player retention rate, developers ran AB-test by moving the first gate from level 30 to level 40 for some players i.e.,
 
-group A would encounter the gate at level 30, and
-group B would encounter the gate at level 40


 To achieve the overall objectives, this work plan can help:
 
1.Perform initial data preparation.

2.Generate statistical summary and plot charts to answer:

  a.What is the overall 7-day retention rate of the game?
  b.How many players never played the game after installing it?
  c.Does the number of players decrease as the levels become difficult?
  
3.Generate crosstab for two player groups to understand the difference in the 1-day and 7-days retention rate and total number of game rounds played.

4.Perform two-sample test for groups A and B to test statistical significance amongst the groups in the sum of game rounds played. Here, you can:
*Check the assumptions of two sample test:
                                                              i.      Normal distribution – Apply Shapiro test
                                                              ii.      Homogeneity of variance – Apply Levene’s test
 *Apply the relevant two sample significance test method based on the results from the tests for normality and homogeneity
 
 5.Analyze the significance of the test results and decide which level has more advantage in terms of player retention?
 
6.Use bootstrap resampling to plot retention rate distribution for both groups to visualize the effect of different versions of the game on retention.

                                                             












