# Election-Analysis

## Purpose
The purpose of this analysis is to provide additional data to complete the audit of the local congressional election.

## Project Overview
A Colorado Board of Elections employee has provided the following tasks to complete the election audit of a recent local congressional election. They are:

1. Calculate the total number of Votes cast
2. Get a complete list of candidates who recieved votes
3. Calculate the percentage of votes each candidates won
4. Calculate the total number of votes each candidate won
5. Determine the winner of the election based on popular vote

## Resources
- **Data Source:** election_results.csv
- **Software:** Python 3.7.3, Visual Code, 1.38.1

## Election Audit Results
>The analysis of the election show that:
>- There were `"369, 711"` votes cast in the election.
> - The candidates were:
>   - Charles Casper Stockham
>   - Diana DeGette
>   - Raymon Anthony Doane
>  
>- The candidate results were:
>  - Charles Casper Stockham recieved `"23.0%"` of the vote and `"85, 213"` number of votes
>  - Diana DeGette recieved `"73.8%"` of the vote and `"272, 892"` number of votes
>  - Raymon Anthony Doane recieved `"3.1%"` of the vote and `"11, 606"` number of votes
>  
>- The winner of the election was:
>  - Diana DeGette, who recieved `"73.8%"` of the vote and `"272, 892"` number of votes.

>The Election was conducted in three (3) counties. They are:
>- Jefferson County
>- Denver County
>- Arapahoe County
>All three countie combined had total of `369, 711` votes.
>
>The county turnout results were:
>  - Jefferson County recieved `"10.5%"` of the vote and `"38, 855"` number of votes  
>  - Denver County recieved `"82.8%"` of the vote and `"306, 055"` number of votes
>  - Arapahoe County recieved `"6.7%"` of the vote and `"24, 801"` number of votes
>The county with the largest turnout is Denvefr with `306, 055` votes and `82.8%` total turnout. 

>**Table showing Elections Results from Terminal:**
>
>![election_results](./Resources/election_results.png)
  
## Election Audit Summary
>With some modification this script can be used to retrieve a deeper analysis on the demographics of the each coumty, and like wise to get a glimpse of the candidates supporters. Script can be used to find out whether we have a larger turnout of younger or older population, the gender, race etc. These are key and important metrics, that can be made available in a matter of seconds. This can be done, by swapping out and or creating new variable names such as county and or county names. 
>
>The same script can be also used for other elections to determine the prefered method or most used method of voting, providing that the data is available.


