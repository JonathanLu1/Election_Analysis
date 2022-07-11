# Election_Analysis

## Overview

In this project of designing a program to calculate the total votes of an election, we used a script to take the data from a CSV file to calculate the total amount of votes that were cast for each person. The program that we had designed not only collected the votes, but it also took into account the different counties that each candidate was in and how active each county was. The code that we had designed allows us to take a look at the different variables that are impactful to the election.

## Election-Audit Results

* How many votes were cast in this congressional election?

![Total Election Votes Cast](https://user-images.githubusercontent.com/107448860/178173419-b1ac41f7-57b4-406a-91b9-bda32ab47f73.png)

![image](https://user-images.githubusercontent.com/107448860/178173470-b39b2665-b5ed-4734-83da-5ce2be9e5a00.png)
    
Using a FOR loop, we were able to go through the vote list and determine the total count of votes

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![image](https://user-images.githubusercontent.com/107448860/178173657-4ca1e8d0-a3c4-4199-b8d9-88d675e0c61b.png)

![image](https://user-images.githubusercontent.com/107448860/178173893-2a4136c7-aba7-4b8c-9289-03f4a0ccc17b.png)

Within the FOR loop, we use an IF statement to add a count for each county that we encouter to each county separated by name

* Which county had the largest number of votes?

![image](https://user-images.githubusercontent.com/107448860/178173979-b790314c-9fbf-40c0-9ca2-bb915388ef5f.png)

![image](https://user-images.githubusercontent.com/107448860/178174020-b3a32e9b-ba89-46fd-bf35-51a705356dd5.png)

Using another FOR loop, we are able to collect all the different counties votes and then determine the winning county. 
    
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![image](https://user-images.githubusercontent.com/107448860/178177270-62e393b4-0e8c-49ee-b4ae-b40f1d3072d5.png)

![image](https://user-images.githubusercontent.com/107448860/178177364-9b606e08-8c04-470d-b2e1-5a31cba33cf4.png)

Using a FOR loop, we are able to distinguish the different candidates and the percentages that they had received for the election process.

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![image](https://user-images.githubusercontent.com/107448860/178177437-681993d5-4bd7-459b-91dc-a4e962fc5b3d.png)

![image](https://user-images.githubusercontent.com/107448860/178177473-ece0eddc-1033-4255-94af-37144f5dca9c.png)

Using an IF statement we are able to pull the winning participant and display the statistics with which they had won. 

# Election Audit Summary

This Python script that we had created is extremely helpful to breakdown an election result and analyze some basics of the election. There are some things that could be added to modified from the script that would help with the analysis of different types elections. 

## Modification 1

To further enhance the analysis on this program, we can add a FOR loop and IF statement to extract each candidate's voter percentage within each county. This would allow us to see how each candidate performed in each County and how that impacted the overall votes that allows them to become elected. It is extremely important for candidates within an election to go to each region and win over each state. With this added analysis, we can see how each candidate performed in each county and how it is directly related to the win or loss. 

## Modification 2

The coding can also be modified by changing the countys to states if they are performed on a larger scale. There can be another FOR loop and IF statement added to further breakdown the states into countys and then analyzing them within the different countys from each state. 

# Summary

The coding that has been used within this project is extremely flexible and can be used in many different cases. It doesn't only have to track election results. This can be used to track different types of polling that marketing companies perform. It can be easily modified by changing the csv file and editting the data that it retrieves and using simple FOR loops and IF statements to extract the data and compile it into a summarized form. 
