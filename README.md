# election-analysis
A classwork example project examining election results

---
# Overview
This is a classwork example in which "a Colorado board of elections employee" Tom is looking for help creating an automated process to auditing election results. These election results come from a recently completed U.S. congressional race in a specific Colorado boundry. Votes were initally collected from mail-in ballots, electronic counting machines, and physical vote punch cards, and then were added to an Excel sheet "election_results.csv".  This python program will quickly count votes for each candidate, percentage of votes for each candidate, and the winner of the election based on popular vote. It will also calculate county results to show each county and its total vote count, percentage of total votes based on county, and the county with the largest voter turnout. All results will be printed to the "election_results.txt" file.

## Purpose
Automating this process will make it so human interactions with the votes are extremely limited. This will cut down on errors and time spent on calculations. The goal is to present an easy to read and execute code that can work seamlessly with the current format of collected vote data. Tom and his manager have stated that if this audit is done successfully with Python, the code will be utilized in other congressional districs, senatorial districts, and local elections across Colorado. 

---

# Results
According to the data, 369,711 total votes were cast in this race. Denver county casted a significant portion of the votes, with 82.8% of the total votes coming from Denver voters. 306,055 votes were casted from Denver county. Jefferson county accounted for 10.5% of the vote, or 38,855 votes while Arapahoe county has 6.7% of the vote or 24,801 votes. 

![total and county votes screenshot](/analysis/total_and_county_votes.png)

The winner of the congressional race was Diana DeGette, who accounted for 73.8% of the total votes or 272,892 votes. The runner up was Charles Casper Stockham who had 23.0% of the votes or 85,213 votes total. In last place was Raymon Anthony Doane with 3.1% of the vote or 11,606 votes total. 

![candidte votes screenshot](/analysis/candidate_votes.png)

# Summary


---
