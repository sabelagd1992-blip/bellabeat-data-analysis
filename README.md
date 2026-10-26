# Bellabeat Data Analysis

## Google Data Analytics Capstone Case Study

### Project Overview

This project was completed as part of the Google Data Analytics Professional Certificate Capstone.

The objective of this case study is to analyze smart-device usage data in order to identify trends in users' activity, sedentary behavior, and sleep patterns. These insights are then used to develop data-driven recommendations that could support Bellabeat's marketing strategy and the Bellabeat App.

## Business Questions

The analysis focuses on three main questions:

1. What trends can be identified in smart-device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these insights help influence Bellabeat's marketing strategy?

## Tools Used

- Google Sheets
- Microsoft Excel
- GitHub

## Dataset

The analysis uses the **Fitbit Fitness Tracker Data** dataset provided for the Bellabeat case study.

The main datasets analyzed were:

- `dailyActivity_merged.csv`
- `sleepDay_merged.csv`

The activity dataset contains information such as daily steps, calories burned, activity minutes, and sedentary minutes.

The sleep dataset contains information about total minutes asleep and total time in bed.
## Data Cleaning and Preparation

Before performing the analysis, the datasets were reviewed and cleaned in Google Sheets.

The main steps included:

- Checked the datasets for missing values and inconsistencies.
- Identified and removed 3 exact duplicate records from the sleep dataset.
- Reviewed zero-step records instead of automatically removing them, as they could represent either inactive days or incomplete device tracking.
- Standardized date formats across the activity and sleep datasets.
- Created a unique key combining user ID and date to connect activity and sleep records.
- Successfully matched all 410 cleaned sleep records with their corresponding daily activity records.
- Created additional variables to analyze sleep categories, day of the week, step frequency, and sedentary behavior.

After cleaning, the activity dataset contained data from **33 users**, while sleep data was available for **24 users**.

## Analysis

The analysis focused on activity, sedentary behavior, sleep patterns, and the relationships between these variables.

Key metrics included:

- Average daily steps
- Average sedentary minutes
- Average calories burned
- Sleep duration
- Activity by day of the week
- Frequency of days with at least 8,000 steps
- Correlation between sleep and activity variables

### Key Findings

- Average daily steps were approximately **7,638 steps**.
- All 33 users averaged at least **600 sedentary minutes (10 hours) per day**.
- **45.45% of users** reached at least 8,000 steps on half or more of their recorded days.
- Saturday had the highest average number of steps at approximately **8,153**, while Sunday had the lowest at approximately **6,933**.
- Average sleep duration was approximately **6 hours and 59 minutes**.
- Sleep duration and sedentary minutes showed a **moderate negative correlation of approximately -0.60**.
- Sleep duration had only a weak relationship with steps (-0.19) and almost no linear relationship with calories (-0.03).

The correlations identified in this analysis represent associations and should not be interpreted as evidence of causation.
## Recommendations for Bellabeat

Based on the findings, the following recommendations could support Bellabeat's marketing strategy and the Bellabeat App:

### 1. Promote Active Breaks

Since all 33 users recorded an average of at least 10 hours of sedentary time per day, Bellabeat could encourage users to take short movement breaks through notifications and reminders during prolonged periods of inactivity.

### 2. Encourage Consistent Activity

Only 45.45% of users reached at least 8,000 steps on half or more of their recorded days. Bellabeat could introduce weekly activity challenges, badges, and rewards to encourage more consistent movement habits.

### 3. Target Sunday Activity

Sunday had the lowest average number of steps, at approximately 6,933 compared with 8,153 on Saturday. Bellabeat could use targeted Sunday reminders or short activity challenges to encourage movement on this day.

### 4. Connect Sleep and Daily Activity

The analysis found a moderate negative association between sleep duration and sedentary minutes. Bellabeat could combine sleep and activity tracking to provide more personalized insights and encourage healthier daily routines.

## Limitations

Several limitations should be considered when interpreting the results:

- The dataset contains a relatively small sample of 33 users.
- Only 24 of the 33 activity users had available sleep data.
- The number of recorded days varies considerably between users, ranging from 4 to 31 days.
- The dataset may not be representative of Bellabeat's actual customer base or the broader smart-device market.
- The analysis identifies associations between variables but does not establish causal relationships.
- Some zero-step records may represent inactive days or incomplete device tracking.

Therefore, the findings should be interpreted as trends observed within this sample rather than as conclusions that can be generalized to all smart-device users.

## Bellabeat Product

The insights from this analysis are particularly applicable to the **Bellabeat App**.

The app could use activity and sleep data to encourage movement, support consistent habits, and provide personalized recommendations based on users' daily behavior.

## Dashboard

The project includes an interactive analysis dashboard created in Google Sheets, presenting the main findings and visualizations.

The dashboard covers:

- Key activity metrics
- Sleep and sedentary behavior
- Activity by day of the week
- Frequency of users reaching 8,000+ steps
- Key insights and recommendations

## Conclusion

The analysis shows that sedentary behavior is a significant pattern within the sample, despite many users maintaining relatively active step counts on some days.

Bellabeat has an opportunity to position its app as a tool that not only tracks activity, but also encourages consistent movement, supports healthy routines, and connects activity with sleep insights.
