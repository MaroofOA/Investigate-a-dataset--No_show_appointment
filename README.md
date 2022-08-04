# No Show Appointment Data Analysis
## by Morufdeen Olatunbosun Atilola


## Dataset

This is a No Show Appointment dataset from kaggle

This dataset collects information from 110,527 medical appointments in Brazil and is focused on the question of whether or not patients will show up for their medical appointment. It would be used to answer some questions like what is the most likely factor that makes patient no show up for their appointment.

Some of the questions to answer from the analysis
1. What Age group didn't show up the most?
2. Are many of the patient on Scholarship?
3. What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?


### Preliminary Data Wrangling
For the analysis, I performed initial data wrangling on the dataset to prepare it for analysis by:

1. Confirming the status of the dataset in terms of datatype, number of missing data, and duplicated column.
2. I cleaned the data by changing the datatype and drop missing data where necessary

## Summary of Findings

From the analysis, below are some of the findings as related to the main features (No-show):

> Exploring the data gave us some insight into the data as we compared some of the variables to the No-show variable.
1. Variables such as Gender, Age, Scholarship, Hypertension, Diabetes, Alcoholism, and Handcap are the independent variables and No-show is the dependent variable.

2. From the analysis, we can see that variables such as Scholarship, Hypertension, Diabetes, and Alcoholism are not the variables that can be used to predict if a patient scheduled for appointment would show up or not. This is evident from the proportional on the percentage of the variables with no-show. In most of this proportion, patient with scholarship and didn't show up is greater than that of the without scholarship and didn't show up. 

3. Also, Having limitations such as Hypertension, diabetes, alcoholism, and handicap is not a factor that can be used for the prediction



## Limitations on the project

1. The Handcap variable that is supposed to be boolean, happen to have multiple input values (0 to 4) and the SMS_received variables that is suppose to have a multiple input has a boolean data. An explanation on this discripancies could help us to have a good insight into the data.
2. The proximity of the patient residence to the neighborhood is not given. This can also be a factor to consider, knowing the distance from the patient residence to the neighbourhod can let us know if the patient can easily found her way to the appointment center.
3. The Appointment date and Scheduled date is the same, we need some clarifications on this, is the scheduled date same as appointment date? If so, why do we need to send an SMS to them again when the appointment date is the same as the scheduled day.