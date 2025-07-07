# Porty B’s Banking Institute - A review of the previous marketing campaign outcome.

## OBJECTIVE
This analysis aims to inform on the success and failure rates of the previous marketing campaign done by Porty B’s banking institute, to guide future marketing initiatives.

## DATA SOURCE
The dataset used was sourced from the bank's internal campaign records and provided by Intern Pulse, comprising 4,483 client interactions with 17 attributes namely age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome, y.

https://github.com/QCessa/Bank-Data-Analysis/blob/Master/Porty%20B's%20Marketing%20Analysis.xlsx

## DATA PREPARATION
1.	Converted .csv into a .xlsx file.
2.	Analysed and removed redundant columns (default, pdays, previous, y).
3.	Renamed columns (marital, education, balance, loan, contact, duration, poutcome) for clarity.
4.	Formatted the age column from text to number.
5.	Formatted the account balance column to currency.
6.	Deleted unknown values from the Job column.

## ANALYSIS TECHNIQUE
1.	Pivot tables: Aggregated data by age, job roles, marital status, account balance, loan, previous outcome and month.
2.	Visualisation: Columns, bar and pie charts are used to highlight relationships.
3.	Filtering: Segmented data by existing loans and previous outcomes to isolate subgroups.

## BUSINESS CASES ANALYZED
1.	What month(s) of the year yielded the most successful and failed responses?
2.	Did the relationship status of the targeted audience affect the outcome of the campaign?
3.	Did the account balance and existing loan status affect the outcome of the campaign?
4.	Did the education level have any effect on whether the individual chose to sign up or not?

## TOOLS USED
1.	Data cleaning, modelling, pivot tables analysis, as well as dashboards, were carried out using Microsoft Excel
2.	A GitHub repository was used to load and store data for sharing.
3.	Microsoft Word is used for documentation.
4.	Microsoft PowerPoint was used for presentation.
5.	ChatGPT was used for deeper insights into business case scenarios.

<img width="523" alt="Task 3_PNG" src="https://github.com/user-attachments/assets/89f0c8a6-81db-420a-b56a-d8943ac7941d" />

## LIMITATIONS
The dataset contains over 80% 'unknown' entries in the ‘previous_outcome’ field, limiting the depth of historical engagement analysis.

## INSIGHTS ACQUIRED
1.	Entrepreneurs, retirees, technicians and service-delivery workers between 40 and 70 years of age responded more positively to the campaign.
2.	Out of people with already existing loans, only individuals who worked in administrative, management and service-delivery roles, between the ages of 34 and 52, were successfully converted during the campaign.
3.	Divorces with an account balance above £6K successfully subscribed to the bank, even though they already had an existing loan. Whereas married couples and single individuals with account balances between £2K and £5K were the highest subscribers when they did not have an existing loan.
4.	Higher success rates were recorded among educated individuals; however, this becomes greatly reduced when a pre-existing loan exists. Primary schoolgoers with existing loans were not successful at all.
5.	Higher success rates were achieved in January, March, July, October and November. In contrast, February, April, May and June had the most failed campaigns.

## FINAL CONCLUSIONS
Future marketing campaigns should target middle-aged individuals working in managerial or administrative positions. They should be initiated in January after individuals have splurged during the December holidays, and in November when preparation for the festivities starts. Furthermore, tailored campaigns should be considered for divorcees and retirees, as they are most likely to subscribe to the bank with a tailored offer.
