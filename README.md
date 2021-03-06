# Automating analysis with Python

## Financial Analysis

![Revenue](Images/revenue-per-lead.png)

* I created a Python script for analyzing the financial records. I was given a set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`. 

* I created a [Python script](#pybank/main.py) that analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

### Output

   ```text
  Financial Analysis
______________________
Total month: 86
Total: 38382578
Average change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)
______________________
  ```

## Election Results Analysis

![Vote Counting](Images/Vote_counting.png)

* In this challenge, I was tasked with helping a small, rural town modernize its vote counting process.

* I was given a set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. I created a Python script that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote

### Output

   ```text
  Election Results
______________________
Total Votes: 3521001
______________________
Khan: 63.0% (2218231)
Correy: 20.0% (704200)
Li: 14.0% (492940)
O'Tooley: 3.0% (105630)
______________________
winner: Khan
______________________
______________________
  ```
