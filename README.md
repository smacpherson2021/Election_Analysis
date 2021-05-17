# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates whoe received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9, Visual Studio Code, 1.56.2

## Summary
The analysis of the election shows that:

Election Results
Total Votes: 369,711

- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

Winner: Diana DeGette

Winning Vote Count: 272,892

Winning Percentage: 73.8%

## Challenge Overview
Overview of Election Audit: Explain the purpose of this election audit analysis.

Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

How many votes were cast in this congressional election?
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Which county had the largest number of votes?
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

## Challenge Summary

### Overview of Election Audit
The election commission has requested some additional data to complete the audit:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

### Election Audit Results

Election Results
Total Votes: 369,711
County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

Largest County Turnout: Denver
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

Winner: Diana DeGette

Winning Vote Count: 272,892

Winning Percentage: 73.8%

### Election-Audit Summary

This script could be used for any election. For example, you could modify the script using a for loop to load and save results from multiple files instead of just the one. This would allow you to use the script in all the elections. Secondly you could add state as a column in the election_results.csv file and add variables and loops to also do counts by state so that you could present the information back to the user by state, then county. This would allow you to see an analysis results for multiple elections at one time.
There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script.
