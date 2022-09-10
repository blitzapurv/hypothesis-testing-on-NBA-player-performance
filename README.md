# Hypothesis testing on NBA player performance
Analysing Player performance stats after for the regular NBA season 2020-2021. The aim of the present study is to test if the players in different classic postions have significantly different values of performance variables.

A test for the null hypothesis that 2 independent samples have identical average. Here, the samples being, values of performance variables corresponding to all the five distinct positions.

* Null hypothesis: Average value of a performance metric 'p' is same for all the positions.
H0: μ1 = μ2 = · · · = μ5
* Alternative hypothesis: Average value of a performance metric 'p' is not same for all the positions.
H1: At least two of the means are not equal.

## About Dataset

This dataset has been obtained from [Basketball-reference](https://www.basketball-reference.com/)

Note:
Some of the advanced performance statistics may be missing in older data.
The N.B.A. introduced the 3-point shot in the 1979-80 season. So, 3PA, 3P, and 3P% are absent in older records.
Attribute Information:

**player_data.csv**

* From -- First year
* To -- Last year
* Pos -- Position
* Ht -- Height
* Wt -- Weight
* Birth Date -- Birth Date
* Colleges -- College

**seasons_stats.csv**

Over 50 performance stats,
Here is a list of Columns in this file and their descriptions, [Glossary](https://www.basketball-reference.com/about/glossary.html)
