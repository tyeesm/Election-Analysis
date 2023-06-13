# Module-3---Election-Analysis
## Overview
In this module, we need to generate a report that is typically done in Excel, in Python instead. We need to generate a vote count report that is for a U.S. congressional precinct taking place in Colorado. All of the votes casted must be included(mail in ballots, punch cards, and direct recording electronic counting machines). We need to find out if there is a way to automate the process using Python. The Python code was written and executed, confirming it was working. The code was submitted however there was additional data that was requested to finalize the audit.

## Purpose
The purpose of this election analysis was to calculate was to calcuclate summary statistics for the election occuring this year in Colorado. This summary includes total votes, the percentage of voter turnout per county, identifcation of the county with the largest turnout, as well as the winner of the election.
## Results
The results of this election are as follows:
* Total votes cast: 369,711
* County with largest voter turnout: Denver
* The winner: Diana DeGette
* Winning percentage: 73.8%
## Summary
This script though proto-typed for this election in colorado could be applied to any election anywhere. The only limitation is that the input data be in the same format as what was used here i.e a three column csv. containing voter I.D, county, candiate name. There are other security and privacy considerations for deploying this script across other states but those are out of the scope for this phase of development.
