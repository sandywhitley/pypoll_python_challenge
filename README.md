# PyPoll Python Challenge
* By: Sandra Whitley
* September-October 2020
* Data Visualizations
*****

## Election-Audit Overview
The purpose of this audit was to use Python to analyze the raw data vote file (election_results.csv) for the 2018 US House Colorado District 1 general election. The counties included in District 1 are Jefferson, Denver, and Arapahoe and the candidates were Dianne DeGette (Democrat), Charles Casper Stockham (Republican) and Raymon Anthony Doane (Liberatarian). Python was used to calculate and organize the data to show total votes cast, votes by county by percentage and quantity, and votes by candidate by percentage and quantity. 

## Election-Audit Results
The analysis lead to the following results which are also reflected in the deliverables:
* Total Votes: 369,711
* County Votes: Jefferson: 10.5% (38,855), Denver: 82.8% (306,055), Arapahoe: 6.7% (24,801)
* Largest County Turnout: Denver
* Candidate Votes: Charles Casper Stockham: 23.0% (85,213), Diana DeGette: 73.8% (272,892),Raymon Anthony Doane: 3.1% (11,606)
*  Winner: Diana DeGette

### Deliverables

1. Election Results Terminal Output

![Election Results Terminal Output](/Resources/election_results_terminal.PNG)

2. Election Results Text Output File

![Election Results Text Output File](/analysis/election_results.txt)


## Election-Audit Summary
The Python script developed for this project can be modified minimally for any election scenario thereby reducing business analyst development and testing time which thereby reduces election commission costs. 

This Python election results script contains two sets of data organizations tools (i.e. variables, lists, dictionaries); one for county data and one for candidate data. The county variables, lists, and dictionaries can be modified for use at any scale such as local, city, state, regional, or national elections. The candidate variables, lists, and dictionaries can be minimally modified to include many candidates.

This script also contains output file organization that can be modified to meet the reporting needs of the election.

![Election Results Python Script](pypoll_challenge.py)
