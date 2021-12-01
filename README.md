# Project 7: Statistical Analysis and Hypothesis Testing
## Project : Increasing YoY revenue from game purchases by increasing retention rate of gamers

### About the project:
The project involves working on data related to Cookie Cats – a hugely popular puzzle game. As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in the player's enjoyment of the game being increased and prolonged. But where should the gates be placed and how the placement of the gates can retain the players for more time.

The project requires you to:
1.	Perform exploratory data analysis of the given datasets and generate their statistical summary.
2.	Perform A/B testing between the two groups of data to analyze the impact on player retention if the first gate in Cookie Cats is moved from level 30 to level 40.
__Difficulty Level: Intermediate__

__Tools to Use: Python (preferred) or R Programming__

### Aim:
Even though the overall subscription for the game is growing, the revenue from in-game purchases has been declining and many players are uninstalling the game after playing for a few days. What recommendations can you suggest increasing the in-game purchase and retaining the players?

### Objectives/Exercise:
The overall objective of the project is to test the company’s CEO’s hypothesis that moving the first gate from level 30 to level 40 increases retention rate and the number of game rounds played. The CEO believes that players are churning because the first gate encountered at level 30 is too early which forces players to wait before they can proceed further in the game.
 In order to increase player retention rate, developers ran AB-test by moving the first gate from level 30 to level 40 for some players i.e.,
-	group A would encounter the gate at level 30, and
-	group B would encounter the gate at level 40
 To achieve the overall objectives, this work plan can help:
1.	Perform initial data preparation.
2.	Generate statistical summary and plot charts to answer:
a.	What is the overall 7-day retention rate of the game?
b.	How many players never played the game after installing it?
c.	Does the number of players decrease as the levels become difficult?
3.	Generate crosstab for two player groups to understand the difference in the 1-day and 7-days retention rate and total number of game rounds played.
4.	Perform two-sample test for groups A and B to test statistical significance amongst the groups in the sum of game rounds played. Here, you can:
      
      ●	Check the assumptions of two sample test:
      
          i.      Normal distribution – Apply Shapiro test
          
          ii.      Homogeneity of variance – Apply Levene’s test
      
      ●	Apply the relevant two sample significance test method based on the results from the tests for normality and homogeneity

5.	Analyze the significance of the test results and decide which level has more advantage in terms of player retention?
6.	Use bootstrap resampling to plot retention rate distribution for both groups to visualize the effect of different versions of the game on retention.

### Skills/Concepts to Use:
1. 	Slicing and dicing data frames to generate summary statistics
a.  	Filtering data frames based on column(s)
b. 	Splitting data into multiple data frame(s)
c.  	Shape of data frame, counting rows and length
d. 	Adding/deleting column(s) to a data frame
e. 	Aggregations and merging data frames
f.   	Grouping, pivot table, cross tabs
g.  	Scatter plots, histogram, box plots, etc.
2. 	Hypothesis testing
a.  	Null and alternate hypothesis
b. 	P-value and significant testing based on confidence intervals
3. 	One sample t-test - One-tailed and two-tailed
4. 	Two sample t-test
a.  	Assumptions –normality test and homogeneity of variances
b. 	Types of two sample t-test
                                                              i.      z-test
                                                            ii.      t-test with equal variances
                                                          iii.      t-test with unequal variances

### Resources:

__1.	 Essential Statistics Training on Excel (LinkedIn Learning):__
 https://www.linkedin.com/learning/excel-statistics-essential-training-1-2

__2.	Essential Math for Machine Learning:__
Python Edition

https://www.linkedin.com/learning/essential-math-for-machine-learning-python-edition

__3.	Descriptive statistics__

a.  	Individuals and variables: https://youtu.be/noV7b2mZ6VU

b. 	Numerical and categorical data: https://youtu.be/FsGerboj9Sc

c.  	Types of data: https://youtu.be/ga3cNZ7ZcoQ

d. 	Using histograms to summarize data: https://youtu.be/QCvvbck8B-A

e. 	Calculating Mean, Median and Mode: https://youtu.be/Ciizn_yX46s

f.   	Calculating Range, Variance and Standard Deviation: https://youtu.be/X6i5orYSU5M

g.  	Skewness analysis: https://youtu.be/lBN0Q2W-4ec

h. 	Boxplot analysis: https://youtu.be/9ftg9uD5qTE

__4. 	Sampling and Confidence Intervals:__

a.  	Sampling and sampling distributions: https://youtu.be/f87kb6kBPPk

b. 	Confidence intervals: https://youtu.be/EqbAQxQiQ00

c.  	Confidence intervals examples: https://youtu.be/YkZSwRq2EcA

d. 	Population and samples: https://youtu.be/K6kEAV-poy0

e. 	Sampling strategies: https://youtu.be/PohcgP-8m3M

f.   	Problems in sampling: https://youtu.be/XPPMLWeDigA

g.  	Mean, variance and standard deviation of sample mean: https://youtu.be/zvtThcEWt6s

h. 	Estimating population proportion using samples: https://youtu.be/boSPWIUniqs

i.        Sample size determination: https://youtu.be/1im1VCSnkYw

__5. 	 Hypothesis testing:__

a.  	Overview of hypothesis testing: https://youtu.be/Nr501ePJ-ow

b. 	Null and alternate hypothesis: https://youtu.be/hPyjpQ_rhds

c.  	One and two tailed tests: https://youtu.be/wNFJ1ICPE-Y

d. 	Choosing between one-tailed and two-tailed test: https://youtu.be/Dz2wuxvh0h8

e. 	Type I and type II error: https://youtu.be/ca-GMlTZsnM

f.   	Critical region: https://youtu.be/ni4r8tg8F3g

g.  	One sample Z-test: https://youtu.be/Y0z6FMTmBAc

h. 	P-values: https://youtu.be/jzSCUtYmz2Q

i.        T random variable: https://youtu.be/70qpGzIrPSQ

j.        One sample T-test : one-tailed: https://youtu.be/43-vHhD2Yro

k.  	One sample T-test: two-tailed: https://youtu.be/VYfk0ohvafM

l.        Single Sample test for population proportion: https://youtu.be/OiJXxVX4r7Q

m.   Testing equity of variances: https://youtu.be/NCR-R1GPsvk

__6. 	Sample testing:__

a.  	Four types of tests: https://youtu.be/JWBGbxxlumw

b. 	Which type of the four tests to use: https://youtu.be/O2gte4GP49A

c.  	Two sample Z-test: https://youtu.be/A_0Pe9iwloA

d. 	Equal variance T-test: https://youtu.be/Uebs6myfSGU

e. 	Unequal variance T-test: https://youtu.be/_FoPGMQxOJ0

f.   	Idea of pairing: https://youtu.be/cv7wUungIcA

g.  	T-test paired two sample: https://youtu.be/VnGeVz4xi8E

5. 	Contingency Table and Hypothesis of Independence:

a.  	Introduction to contingency table and hypothesis of independence: https://youtu.be/yje5XX97gQA

b. 	Chi-squared statistics: https://youtu.be/kdteJPdNsBM

c.  	Computing Chi-squared statistics: https://youtu.be/5D3p2NDahWs

d. 	Conducting the hypothesis test and computing p-value: https://youtu.be/ony4e0et9Uk



