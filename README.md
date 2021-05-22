# School District Analysis

## Overview of Project
The purpose of the analysis was to get a summary of high school performance based on student budget, school size, and school type. Math and reading scores for one school in particular were altered, so that data had to be cleaned by replacing all the test scores with NaN values.

## School District Results
- **How is the district summary affected?** <br/>
- **How is the school summary affected?** <br/>
- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?** <br/>
- **How does replacing the ninth-grade scores affect the following:** <br/>
    - **Math and reading scores by grade** <br/>
    - **Scores by school spending** <br/>
    - **Scores by school size** <br/>
    - **Scores by school type** <br/>


The results of the analysis are showed below. Out of almost 370,000 total votes, Denver had the largest voter turnout of 82.8% of all votes coming from that county. Denver has the largest population out of the three counties from which votes were collected with Jefferson coming in with the next largest population followed by Arapahoe. It is possible that the voting infrastructure is more developed in Denver compared to the other two counties. It can also be seen that Diana Degette won by a landslide, raking in 73.8% of all votes across the three Colorado counties.

### Total Votes: 369,711
### County Votes:
- **Jefferson**: 10.5% (38,855) <br/>
- **Denver**: 82.8% (306,055) - ***Largest voter turnout*** <br/> 
- **Arapahoe**: 6.7% (24,801) <br/>
### Candidate Votes:
- **Charles Casper Stockham**: 23.0% (85,213) <br/>
- **Diana DeGette**: 73.8% (272,892) - ***Election winner*** <br/>
- **Raymon Anthony Doane**: 3.1% (11,606) <br/>
-------------------------

## Election Audit Summary
The results of the analysis showed that the Python script is robust enough to handle any election, since the code is set up in such a way that it always checks if a candidate's votes have been counted and if a certain county has been included. One way that the script could be modified to run faster would be to to write the results directly to the text file instead of printing it to the terminal. Another way that the code could be changed to adapt to another election, say a state-wide election, would be to add additional lists to track state voter turnout in addition to their votes by county. Alternatively, votes could just be counted by state and ignore county-wide votes.

