# Election_Analysis

## Project Overview
A Colorado Board of Elections employess have given you the followig tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.12, Visual Studio Code, 1.38.1

## Summary 
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana Degette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane receieved 3.1% of the vote and 11,606 number of vote.
- The winner of the election was:
  - Diana Degette, who received 73.8% of the votes and 272,892 number of votes.

## Challenge Overview
The purpose of this Election Audit Analysis was to utilize Python to read and extract data from a csv file. And after extracting the data, analyzing it, using basic Python data structures, statements, and functions in order to see the winners of the election as well as other catergories.

Election-Audit Results:
![image](https://user-images.githubusercontent.com/111463407/190881234-5aadc296-3211-4f36-a846-6c11f5d81216.png)

## Challenge Summary
Provided the Election Data is uploaded in a similar format as our original csv file (ID in Row 0, County in Row 1, Candidate in Row 2), this script could be used for any election, only needing to change the csv file within the code.

The script could also be modified for other elections as well.
If, for example, we wanted to do this with a Presidential Election, we could modify our code to also include what political party had the most turnout as well.

We could also modify this script to instead have state turnout rather than county turnout and see the percentage of the states votes instead.
