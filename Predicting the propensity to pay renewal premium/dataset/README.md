# Data ([soruce](https://datahack.analyticsvidhya.com/contest/mckinsey-analytics-online-hackathon-4/?utm_source=sendinblue&utm_campaign=Events_in_July_2018&utm_medium=email))

## train.csv

It contains training data for customers along with renewal premium status (Renewed or Not?)

**Variable** | **Definition**
------------ | -------------
id | Unique ID of the policy
perc_premium_paid_by_cash_credit | Percentage of premium amount paid by cash or credit card
age_in_days | Age in days of policy holder
Income | Monthly Income of policy holder
Count_3-6_months_late | No of premiums late by 3 to 6 months
Count_6-12_months_late | No  of premiums late by 6 to 12 months
Count_more_than_12_months_late | No of premiums late by more than 12 months
application_underwriting_score | Underwriting Score of the applicant at the time of application (No applications under the score of 90 are insured)
no_of_premiums_paid | Total premiums paid on time till now
sourcing_channel | Sourcing channel for application
residence_area_type | Area type of Residence (Urban/Rural)
premium | Monthly premium amount
renewal | Policy Renewed? (0 - not renewed, 1 - renewed


## test.csv

Additionally test file contains premium which is required for the optimizing the incentives for each policy in the test set.

**Variable** | **Definition**
------------ | -------------
id | Unique ID of the policy
perc_premium_paid_by_cash_credit | Percentage of premium amount paid by cash or credit card
age_in_days | Age in days of policy holder
Income | Monthly Income of policy holder
Count_3-6_months_late | No of premiums late by 3 to 6 months
Count_6-12_months_late | No  of premiums late by 6 to 12 months
Count_more_than_12_months_late | No of premiums late by more than 12 months
application_underwriting_score | Underwriting Score of the applicant at the time of application (No applications under the score of 90 are insured)
no_of_premiums_paid | Total premiums paid on time till now
sourcing_channel | Sourcing channel for application
residence_area_type | Area type of Residence (Urban/Rural)
premium | Monthly premium amount

## sample_submission.csv

Please submit as per the given sample submission format only

**Variable** | **Definition**
------------ | -------------
id | Unique ID of the policy
renewal | Predicted Renewal Probability
incentives | Incentives for agent on policy
	








 
