# Analyzing and Interpreting Election Data For the State of Colorado.

## Overview of Election Audit:
The purpose of this audit was to uncover information regarding a congressional election in Colorado. The audit was intended to discover which county (Denver, Arapahoe, or Jefferson) held the largest quantity of voters, and their subsequent total percentage of votes compared to one another. This data was applied to the already processed information regarding election results. 

## Election Audit Results:
In this election, there were 3 candidates running for office: Charles Stockham, Diana DeGette, and Raymond Deone. The Election audit discovered the following information:

* ### How many votes were cast in this congressional election?
  * There were a total of 369,711 votes cast in this election. (Fig. 1)

* ### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct:
  * To discover the number of votes-per-county, The following code was created:
  
  ![County_vote](https://user-images.githubusercontent.com/90812456/136720849-f7ddea33-798b-4d21-88c6-e349fde71d6a.png)

  * This code allowed Python to go through each casted vote on the provided csv list, seperate by county, and tally the votes to discover total votes per county. 

#### Total Votes in Each County:
   * Jefferson: 10.5% (38,855 votes)
   * Denver: 82.8% (306,055 votes)
   * Arapahoe: 6.7% (24,801 votes)

* ### Which county had the largest number of votes?
  * Denver had the largest number of votes, with 306,055 total votes. (fig.1)

* ### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received:
  * To discover the number of votes and total percentage each candidate recieved, The following code was created:
  
  ![county_percentage](https://user-images.githubusercontent.com/90812456/136720980-167b3367-91b8-4512-888b-12507abc206f.png)


  
  *  This code allowed Python to divide and tally each row by candidate. To acquire total percentage per candidate, the coder divided candidate votes by total votes in election, then multiplied by 100. 

* ### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Out of the 3 Candidates, Diana DeGette won the election by 73.8% with 272,892 total votes. 



#### Fig. 1: Election Results:

  ![election_audit_results](https://user-images.githubusercontent.com/90812456/136720687-fe53a0f4-dee5-4ef9-ab5d-0bfb74085324.png)


## Election-Audit Summary:

In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

