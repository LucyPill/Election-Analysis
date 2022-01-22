# Overview of Election Audit: 
## Purpose: the purpose of the challenge is to set up Python in my computer and use it to write algorithms that will assist in the confirmation and analysis of election results. 
# Election-Audit Results:
![election_results_summary](https://github.com/LucyPill/Election-Analysis/blob/main/election_results_summary.png)

o	The total votes cast in this congressional election was: 369, 711

o	For this election we considered three counties: Jefferson, Denver, and Arapahoe. As shown in the summary election, we can see that turnout for Jefferson County was 10.5% of votes which equate to 38, 885, the turnout for Denver was 82.8% of votes which equates to 306, 055 votes, and the turnout for Arapahoe was 6.7% which equates to 24, 801 votes. When added together this is equal the total votes which is 369, 711

o	County with the largest number of votes: Denver (306, 055)

o	Breakdown of total number of votes and percentage by candidate:
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272, 892)
Raymond Anthony Doane: 3.1% (11. 606)
	 
o	Winner candidate: Diana DeGettewith a vote count of 272, 892 votes with a of 73.8%
# Election-Audit Summary: 
This code was very useful in helping us determine the results of the elections for three counties: Jefferson, Denver and Arapahoe in the State of Colorado; however, there is so much more we can do with this code, for example, we could repurpose this code to get more out of it and use for a larger area where we can simply things and get results faster and accurate.
We can have this code to be interactive where we can write a script similar to the one we already have but require input/s from the people working on the elections, so they can input/feed the information require, so they can get an output in a matter of seconds with the results needed. 


#Overview of the scripts:

For this assignment we were giving a started code, and we had to fill the missing code so at the end, we ca run the code and get the election results.
### The first task was to create a county list and a county vote dictionary.
![county_list_vote_dictionaries.png]( https://github.com/LucyPill/Election-Analysis/blob/main/county_list_vote_dictionaries.png)

### Second: We need it to track the largest county and voter turnout. I started tow new variables:
![largest_county_turnout.png]( https://github.com/LucyPill/Election-Analysis/blob/main/largest_county_turnout.png)

### Third: We need it to add a piece of code that will allow us to extract the county name from each row.
![county_name.png]( https://github.com/LucyPill/Election-Analysis/blob/main/county_name.png)

### Fourth: We needed to add an if statement to check that the county doesn’t match any existing county in the county list. Then, if it doesn’t add it to the county list, and start tracking the county votes count and add it to that county’s vote count.
![if_statements.png]( https://github.com/LucyPill/Election-Analysis/blob/main/if_statements.png)

### Fifth: Finally, for the missing code we needed to write a loop to get the county from the county dictionary, retrieve the county vote count, calculate the percentage of votes for the county, print the county results to the terminal, save the county votes to a text file, write an if statement to determine the winning county and get its vote count, print the county with the largest turnout, and finally save the county with the largest turnout to a text file.
![loop_through_county_dictionary.png]( https://github.com/LucyPill/Election-Analysis/blob/main/loop_through_county_dictionary.png)
![image](https://user-images.githubusercontent.com/96222252/150652997-451bbc1e-a0da-4edc-9196-f6b5ebee964a.png)
