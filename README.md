# Election_Analysis

## Overview of Election Audit
    The Colorado Board of Elections conducted an election for a U.S. congressional precinct in Colorado.  In order to certify the race, the Board must run an audit on the results to ensure accurate counts and declare a winner.  We have been tasked with building a Python script that will import a fixed format file of the results, count/process the votes and output the results both on screen and to an output file.  The board has requested the following data as results:

         - Total votes cast
         - County turnout and percent of total for each county
         - The county with the largest turnout
         - Candidate counts and percent of votes for all candidates
         - A declaration of the winner with a summary of their votes

## Resources 
- Data Source: election_results.csv
    - https://github.com/djaiello/Module3Challenge/blob/main/Resources/election_results.csv
 
- Software: Python 3.7.6, Visual Studio Code, 1.72.2

## Election Audit Results
- There were 369,711 votes cast in thid congressional election. 

- The county turnout for this precinct was:
    - Jefferson county turnout was 38,855 voters (10.5% of total turnout)
    - Denver county turnout was 306,055 voters (82.8% of total turnout)  
    - Arapahoe county turnout was 24,801 voters (6.7% of total turnout)

- The county with the largest turnout was:
    - Denver county with 306,055 voters

- The candidates were:
    - Charles Casper Stockham  
    - Diana DeGette
    - Raymon Anthony Doane 

- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 

- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

### Resultant Screen Output


- Reference Link to the Audit Results Output File:
   - https://github.com/djaiello/Module3Challenge/blob/main/analysis/election_results.txt

- Reference Link to Python Script:
   - https://github.com/djaiello/Module3Challenge/blob/main/PyPoll_Challenge.py


## Election Audit Summary
    The results above show that the audit script created for this project delivered fast, accurate results at both the county and candidate levels.  It is proposed that this script serve as a template for future election audits in the state of Colorado allowing for script modifications for any changes in election level or input file format. 
    
    For example, elections at a lower level may not be reported at the county level, such as a county election where results may be by town.  A modification to allow the user to input the election level (national, state level, congressional district, county, or town) and aggragate level(s) beneath it, would make the script more universal.

    A change in the input file format would also necessitate a change in the script. While it would be easier to enforce the format for future elections, in cases where it changes, the script would have to alter the data structures and all references to them to accomodate the new format.

    We look forward to working with the Colorado Election Board in the future.
