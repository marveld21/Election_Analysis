# Election Analysis

## Overview of Election Audit
### We are tasked with analyzing results from an election using the polling data. We also need to create a python script that will be able to break down data in future elections. The key results being looked at are turnout by county and the election results by candidate.

## Election Audit Results
### Election turnout by county:
- Denver County, 306,055 total votes, 82.8% of total turnout
- Jefferson County, 38,855 total votes, 10.5% of total turnout
- Arapahoe County, 24,801 total votes, 6.7% of total turnout
### Denver County had the largest turnout
### Election results:
- Raymon Anthony Doane, 11,606 total votes, 3.1% of total votes
- Charles Casper Stockham, 85,213 total votes, 23.0% of total votes
- Dianna DeGette, 272,892 total votes, 73.8% of total votes
### The election winner is DIANNA DEGTTE

## Election Audit Summary
### The script works as intended and prints an analysis text file located in the analysis folder.
### This script can be used with other election results by changing the source file.
```
file_to_load = os.path.join( "Resources", "election_results.csv")
```
### You can also change where the output file saves by changing the path of the save file.
```
file_to_save = os.path.join("analysis", "election_analysis.txt")
```