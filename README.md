# Election Audit Challenge 

## Project Overview
The purpose of this project is to perform an audit of a local congressional election. The votes are to be counted and confirmed across three different counties and three different candidates. I will be providing those numbers and the percentages, as well as the winner of the election based on popular vote and the county that had the largest voter turnout.


## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6; Visual Studio Code, 1.68.1


## Election-Audit Results
- In this election there were 369,711 total votes cast.

- There were three candidates in this election:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
	
- There were three counties in this election:
	- Jefferson
	- Denver
	- Arapahoe
	
- The results for the candidates were as follows:
	- Charles Casper Stockham received 85,213 votes, which was 23% of the total vote count.
	- Diana DeGette received 272,892 votes, which was 73.8% of the total vote count.
	- Raymon Anthony Doane received 11,606 votes, which was 3.1% of the total vote count.
	
- The results for the counties were as follows:
	- In Jefferson County there were 38,855 votes, which was 10.5% of the total vote count.
	- In Denver County there were 306,055 votes, which was 82.8% of the total vote count.
	- In Arapahoe County there were 24,801 votes, which was 6.7% of the total vote count.

- The county with the largest number of votes was:
	Denver County, with 306,055 votes and 82.8% of the total vote count.

- The Winning Candidate was:
	Diana DeGette, with 272,892 votes and 73.8% of the total votes cast during the election.
	

## Election-Audit Summary
The convenient thing about this script is that the bones of it are straightfoward enough to easily transfer to other elections. If someone wanted to use this code for another election, all it would take is placing the appropriate file in the `file_to_load = os.path.join("Resources", "" )` and `file_to_save = os.path.join("Analysis", "" )` parentheses.

Once the desired file is in the resources folder, and most importantly the contents are ordered the same way as the original file, the code will operate the same. It will extract the appropriate amount of candidates and their votes, as well as the counties and their votes, no matter if the number of candidates or counties is greater or fewer than in the presented election. Even the code for terminal print out can remain as is, because the output is independent of the election information itself. However, changing the terminal output to include a specific message or anything else would not be difficult.
