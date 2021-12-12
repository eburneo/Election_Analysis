# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has requested our assitance to compelte the audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6 64-bit, Visual Studio Code 1.63.0

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in this congressional election. 
- The County results:
  - Jefferson County had 10.5% of the vote with 38,855 votes cast
  - Denver County had 82.8% of the vote with 306,055 votes cast
  - Arapahoe County had 6.7% of the vote with 24,801 votes cast
- Denver county had the largest number of votes with 306,055 
- The Candidate results:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of the votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of the votes.
  - Raymon Anthony Doane received 3.1% of the vote and 85,213 number of the votes.
- Diana DeGette was the winner of the election with 73.8% of the vote and 272,892 number of votes

![Election_analysis](https://github.com/eburneo/Election_Analysis/blob/main/Resources/Election_analysis.png)

## Election Audit Summary
The script that was created to anayize and generate output for the congressional election can be modified for use in future elections and maybe more efficiently. For example, the script can be refactored to detemine the column to read using the header so that different files that arranged differently can still be read. A second example could be to refactor the script so any file can be accepted so it does not have to be hardcoded.
