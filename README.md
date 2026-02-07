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
<img width="359" height="441" alt="Leanfit analysis" src="https://github.com/user-attachments/assets/bf7ddf7c-943d-4b0e-8452-72017e1df7e1" />

### 2. For Heart Rate (LeanFit support):
- Flagged users with heart rate > 185 bpm as “Elevated Heart Risk.”
- 4 out of 7 sampled users had elevated risk—potential targets for heart-healthy weight loss plans.
<img width="488" height="440" alt="Heart rate leanfit analysis" src="https://github.com/user-attachments/assets/65e1f226-aef7-4e57-b95f-066832939c71" />

### 3. For FitWear:
- I Categorized users based on tracker usage:
  - Active: >20 days
  - Moderate: 11–20 days
  - Light: ≤10 days
    
- Targeted Active and Moderate users for fitness gear marketing.
<img width="466" height="369" alt="Wefit Dashboard" src="https://github.com/user-attachments/assets/4426346c-7c47-4aae-be57-60c2d5a6139a" />

### 4. For Sleepy Nights 
- Classified sleep patterns:
 - Poor: <7 hours
 - Normal: 7–9 hours
 - Excessive: >9 hours
- Found 12 Poor sleepers as ideal targets for sleep app subscriptions.
<img width="616" height="386" alt="Sleep Day Analysis" src="https://github.com/user-attachments/assets/17baa886-0e54-4342-ac97-1a92685bfd98" />

### 5. Dashboard Creation
- Grouped users by activity level and average distance/steps.
- Created charts to visualize user engagement and activity trends.
<img width="596" height="443" alt="Wefit 2" src="https://github.com/user-attachments/assets/c9b276f5-fed3-4d9f-a8a0-4a4568169d62" />
<img width="563" height="440" alt="Wefit Dashboard 3" src="https://github.com/user-attachments/assets/b92284ae-a8f5-4e42-aaf1-dd6fd6fc2d24" />

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

## Limitations 
- Data is from 2016—may not reflect current behaviors.
- No demographic info (age, gender, location) for deeper targeting.
- Sleep and heart rate data were limited to available logs.


