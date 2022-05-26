# **Election Analysis**
## Overview of Election Audit 
The purpose of this audit is to see the spread of votes between candidates and counties. 

## Election-Audit Results 
- 369,711 votes were cast 
- Denver county was 1st in voting. 306,055 votes or 82.8% of total voting
- Jefferson county was 2nd in voting. 38,855 votes or 10.5% of total voting
- Arapahoe county was last in voting. 24,801 votes or 6.7% of total voting
- Diana DeGette won the election, with 272,892 votes or 73.8% of total voting
- Charles Casper Stockham was 2nd in voting, with 85,213 votes or 23% of total voting 
- Raymon Anthony Doane was last in voting, with 11,606 votes or 3.1% of total voting

## Election-Audit Summary 
This script can be used for future elections to save time calculating totals and percentages, and to give an almost instant update to all parties about who leads in voting.
This script can be modified easily to fit other elections. For example, other elections will have different candidates. This code automatically creates a list and dictionary of all the candidates, so this script will work if we add more candidates for a future election. If the location of headers changes in the data csv file, then the code can be repurposed to summarize information by changing the indexing coding in the script. Or if we wish to add in another dimension to analyze, for example the voters race. We can refactor this code to summarize voting metrics by voter race. 
