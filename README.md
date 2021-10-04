# Election_Analysis_1
## Overview of Election Audit
### Tom is a Colorado Board of Elections employee who needs assistance conducting an election audit for a US Congressional Precinct in Colorado in order to verify and confirm the total number of votes cast, the number of votes cast per candidate, and ultimately, the winner of the election based on the popular vote. 
---------
## Election Audit Results

- A total of 369,711 votes were cast.  


**County Votes**
- Jefferson: 10.5% with 38,855 votes cast
- Denver: 82.8% with 306,055 votes cast
- Arapahoe: 6.7% with 24,801 votes cast
---------
- County with the largest number of votes: **Denver**
---------
**Vote Summary by Candidate**
- Charles Casper Stockham received 85,213 votes for 23% of the popular vote.
- Diana DeGette received 272,892 votes for 73.8% of the popular vote.
- Raymon Anthony Doane received 11,606 votes for 3.1% of the popular vote.
---------
**Election Winner**
- Diana Degette
  - 272,892 Total Votes
    - 73.8% of the Popular Vote
---------
## Election Audit Summary

The script developed for this Election Audit Analysis was written to tabulate the number of votes cast in an entire state and further breaks down the findings by county. Although this analysis is broken down by county, this variable could be amended to accomodate a citywide election that spans accross different neighborhoods. This would require a simple change to the assigned variable names such as:
```
1. largest_county
2. county_voter_turnout
```
**Variable Equivalent in City Election:**
```
1. largest_neighborhood
2. neighborhood_voter_turnout
```
This code is also generic enough to apply to an analysis of vote distribution accross a number of *ballot measures* as opposed to *candidates*. This would require simple amendements to the variables such as:
```
candidate_options = []
candidate_votes = {}
largest_county = ""
county_voter_turnout = 0
```
**Variable Equivalent for Analysis of Ballot Measures**
```
ballot_measures = []
ballot_measure_votes = {}
most_popular_ballot_measure = ""
election_voter_turnout = 0
```






