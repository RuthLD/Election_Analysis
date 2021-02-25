# Election_Analysis
Learning to use Python by analyzing election data. 
Project #3 of Data Analysis Bootcamp

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent congressional election.
1. Total number of votes cast.
1. A complete list of candidates who received votes.
1. Total number of votes each candidate received.
1. Percentage of votes each candidate won.
1. The winner of the election based on popular vote.

## Resources
* Data Source: [election_results](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/election_results.csv)
* Software: Python 3.7.6, Visual Studio Code, 1.53.2

## Summary
The analysis of the election showed that:
* There were 369,711 total votes cast in the election.
* The candidates were:
  *   Charles Casper Stockham
  *   Diana DeGette
  *   Raymon Anthony Doane
* The results by candidate were:
  * Charles Casper Stockham received 23.0% of the vote and 85,213 total votes.
  * Diana DeGette received 73.8% of the vote and 272,892 total votes.
  * Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes
* The winner of the election was:
  * Diana DeGette, who recieved 73.8% of the vote and 272,892 total votes.

## Challenge Overview
The challenge asked for additional analysis related to the county voter turnout. 
1. The voter turnout for each county.
1. The percentage of votes from each county out of the total count.
1. The county with the highest turnout.

## Challenge Results Summary
* The total number of votes cast in the congressional election is:
 *  369,711 votes
 *  Here is an image of the code used to get the total votes. ![Total_vote_code](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/Total_vote_code.png)
* The total number of votes by County are as follows:
  *  Jefferson County accounted for 38,855 votes which is 10.5% of voters.
  *  Denver County accounted for 306,055 votes which is 82.8% of voters.
  *  Arapahoe County accounted for 24,801 votes which is 6.7% of voters.
  *  Here is an image of the code used to get the votes and vote percentages by county. ![County_votes_code](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/County_votes_code.png)
* Denver County had the largest number of votes.
  *  Here is an image of the code used to determine the country with the most votes. ![Largest_County_code](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/Largest_County_code.png)
* The number of votes and the percentage of the total votes each candidate received are:
  *  Charles Casper Stockham received 23.0% of the vote and 85,213 total votes.
  *  Diana DeGette received 73.8% of the vote and 272,892 total votes.
  *  Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes
  *  Here is an image of the code used to determine the vote percentage and the number of votes for each candidate. ![Candidate_votes](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/Candidate_votes.png)
* The Winner:
  *  Diana DeGette, who recieved 73.8% of the vote and 272,892 total votes.
  *  Here is an image of the code used to determine the candidate with the most votes. ![Winning_Candidate_code](https://github.com/RuthLD/Election_Analysis/blob/main/Resources/Winning_Candidate_code.png)

The summary of results may also be viewed with the [election_analysis](https://github.com/RuthLD/Election_Analysis/blob/main/analysis/election_analysis.txt) text document. 
The python code for the challenge can be found in [PyPoll_Challenge](https://github.com/RuthLD/Election_Analysis/blob/main/PyPoll_Challenge.py).
