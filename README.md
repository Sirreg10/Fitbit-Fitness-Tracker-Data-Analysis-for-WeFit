# Fitbit-Fitness-Tracker-Data-Analysis-for-WeFit
Fitbit Data Analysis for WeFit’s Marketing and Business Solutions

## Problem Statement
WeFit is a fitness-focused company with several subsidiaries:
1. LeanFit: Sells personalized diet plans for weight loss but has seen declining sales.
2. FitWear: Sells fitness apparel and gear, now moving online.
3. Sleepy-Nights: Offers a sleep scheduling app subscription and wants more users. 

The goal was to analyze Fitbit fitness tracker data to identify potential customers for each subsidiary and create a dashboard for WeFit’s management team.

## Data Sources 
The dataset used for this case study was downloaded from
1. FitBit Fitness Tracker Data from Kaggle uploaded by Möbius.
2. Data collected via Amazon Mechanical Turk from 30 Fitbit users between March 12–May 12, 2016.
3. Includes minute-level activity, heart rate, and sleep data.

## Tools 
I used Microsoft Excel and applied the following Pivot Tables, Charts, Formulas, Functions, Dashboard Creation 

## Data Cleaning/Preparation 
The following were done during data cleaning and preparation
1. Merged relevant sheets (e.g., weightLogInfo, heartrate_seconds, sleepDay).
2. Removed duplicates and filtered incomplete entries.
3. Standardized date formats and calculated averages (e.g., BMI, heart rate, sleep hours).

## Exploratory Data Analysis 
This section involves exploring the FitBit Fitness Tracker Data to help answer the key questions. 
1. <b>LeanFit:</b> Calculated BMI from weight logs to categorize users as Healthy, Overweight, or Obese.
2. <b>FitWear:</b> Analyzed activity minutes and tracker usage days to identify active users.
3. <b>Sleepy-Nights:</b> Evaluated sleep patterns to classify users as Poor, Normal, or Excessive sleepers.
4. <b> Dashboard:</b> Grouped users by activity level and created visual summaries.

## Data Analysis 
### 1. For LeanFit: 
- I used BMI ranges 
  - Healthy: 18.5–24.9
  - Overweight: 25–29.9
  - Obese: 30+

- Identified  1 Obese, 4 overweight, 3 Healthy users as potential targets for weight loss. 

### 2. For Heart Rate (LeanFit support):
- Flagged users with heart rate > 185 bpm as “Elevated Heart Risk.”
- 4 out of 7 sampled users had elevated risk—potential targets for heart-healthy weight loss plans.

### 3. For FitWear:
- I Categorized users based on tracker usage:
  - Active: >20 days
  - Moderate: 11–20 days
  - Light: ≤10 days
    
- Targeted Active and Moderate users for fitness gear marketing.

### 4. For Sleepy Nights 
- Classified sleep patterns:
 - Poor: <7 hours
 - Normal: 7–9 hours
 - Excessive: >9 hours
- Found 12 Poor sleepers as ideal targets for sleep app subscriptions.

### 5. Dashboard Creation
- Grouped users by activity level and average distance/steps.
- Created charts to visualize user engagement and activity trends.

## Results 
After Data has been analyzed the key questions were answered and the following were the results: 
1. <b> LeanFit:</b> 10 potential customers identified (obese/overweight + elevated heart risk).
2. <b> FitWear:</b> 28 Active users, 3 Moderate users identified as likely buyers.
3. <b> Sleepy-Nights:</b> 12 Poor sleepers identified for targeted app marketing.
4. <b> Dashboard:</b>  Interactive view of user activity levels and trends for management.

## Recommendations 
As a data analyst the solution to these problem statements are given below 
- <b> LeanFit:</b> Market to users with BMI > 25 and elevated heart rates.
- <b> FitWear:</b> Focus online ads on Active and Moderate users.
- <b> Sleepy-Nights:</b>  Target Poor sleepers with free trial offers.
- <b> General:</b> Use dashboard for ongoing tracking and campaign adjustments.

