# Election-Analysis

## Overview of Election Audit
A Colorado Borad of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Calculate the number of votes and the percentage of total votes for each county.
3. Determine which county had the largest number of votes.
4. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software Python 3.7.6, Visual Studio Code, 1.73.1

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election

- The counties in which the vote was held were:
  - Jefferson
  - Denver
  - Arapahoe
- The county turnout resutls were:
  - Jefferson's turnout was 10.5% of the total vote with 38,855 votes
  - Denver's turnout was 82.8% of the total vote with 306,055 votes
  - Arapahoe's turnout was 6.7% of the total vote with 24,801 votes
The county with the largest turnout was:
  - Denver
- The candidates were:
  - Charles Casper Stockham
  - Diana Degette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham recieved 23% of the vote and 85,213 number of votes.
  - Diana Degette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana Degette, who received 73.8% of the vote and 272,892 number of votes.
  
## Election-Audit Summary  
The results show that this script has worked great for the current election. It is a general and useful script that could be used as a template for any future elections. With just some small modifications you can adapt the script to audit any election. One of this modifications could be the location of the new data set. By changing the path to the election data file:  file_to_load = os.path.join("analysis", "election_results.csv"), we can acces other files with election data. If you wanted to use this script for a presidential election you could add state data in addition to the county data. For that you would need to add another loop to go through the data for each state to determine the winner of the election. You could also use this script to analyze more than just the outcome of an election. By adding rows to the data set with demographics data, you could determine the kind of voters that each candidate is attracting.
Because of all these reasons, this script is a great base template for any election.
