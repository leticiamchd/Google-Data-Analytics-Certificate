# Google Analytics Certificate Capstone 
#### Case Study 2 - BellaBeat

## Summary 
[1. Ask](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#1-ask)<br/>
> [1.1 - Business Task ](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#11---business-task)<br/>

[2. Prepare](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#2-prepare) <br/>
> [2.1 - Where is the data stored ?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#21---where-is-the-data-stored-)<br/>
> [2.2 - How is the data organized ?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#22---how-is-the-data-organized-)<br/>
> [2.3 - Bias and credibility](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#23---bias-and-credibility)<br/>
> [2.4 - Security and Privacy](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#24---security-and-privacy)<br/>

[3. Process](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#3-process)<br>
> [3.1 - Storage](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#31---storage)<br/>
> [3.2 - Filtering (Used Spreadsheets)](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#32----filtering-used-spreadsheets)<br/>
> [3.3 - Changes (Used Spreadsheets)](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#33----changes-used-spreadsheets)<br/>
> [3.4 - Unique users (Used SQL - Bigquery)](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#34----unique-users-used-sql---bigquery)<br/>
> [3.5 - Round (Used SQL - Bigquery)](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#35---round-used-sql---bigquery)<br/>

[4. Analyze](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#4-analyze)<br/>
> [4.1 - First, we are going to analyze the characteristics of app use](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#41---first-we-are-going-to-analyze-the-characteristics-of-app-use)<br/>
> > [4.1.1 - Adherence of each user, and classification in daily activities](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#411----adherence-of-each-user-and-classification-in-daily-activities)<br/>
> > > [Now grouping by use_classification](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#now-grouping-by-use_classification)<br/>

> > [4.1.2 - Adherence of each user, and classification in sleep](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#412---adherence-of-each-user-and-classification-in-sleep)<br/>

> > > [Now grouping by use_classification](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#now-grouping-by-use_classification-1)<br/>

> > [4.1.3 -Adherence of each user, and classification in weight](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#413--adherence-of-each-user-and-classification-in-weight)<br/>

> > > [Now grouping by use_classification](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#now-grouping-by-use_classification-2)<br/>

> > [4.1.4 - Adherence of users in tracking their daily activities + sleep + weight](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#414---adherence-of-users-in-tracking-their-daily-activities--sleep--weight)<br/>
> > [4.1.5 -How many users tracked all 3 pillars (Activity, sleep, weight)?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#415--how-many-users-tracked-all-3-pillars-activity-sleep-weight)<br/>

> > > [Daily Activity](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#daily-activity)<br/>
> > > [Sleep](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#sleep)<br/>
> > > [Weight](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#weight)<br/>
> > > [Joining all 3 tables:](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#joining-all-3-tables)<br>
> > > [Knowing how many completed at least one of all activities](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#knowing-how-many-completed-at-least-one-of-all-activities)<br/>
> > > [Knowing Who completed at least half of all activities, and how many days of each acitivity the person completed](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#knowing-who-completed-at-least-half-of-all-activities-and-how-many-days-of-each-acitivity-the-person-completed)<br/>

> > [4.1.6 - App usage of each user, per month](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#416---app-usage-of-each-user-per-month)<br/>
> > [4.1.7 - Average of device usage per day through time](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#417---average-of-device-usage-per-day-through-time)<br/>
> > [4.1.8 -Digging into low adherence users](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#418--digging-into-low-adherence-users)<br/>


> > > [For Id = 2347167796](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--2347167796)<br/>
> > > [For Id = 3372868164](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--3372868164)<br/>
> > > [For Id = 4057192912](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--4057192912)<br/>
> > > [For Id = 6117666160](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--6117666160)<br/>
> > > [For Id = 6290855005](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--6290855005)<br/>
> > > [For Id = 7007744171](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--7007744171)<br/>
> > > [For Id = 8253242879](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#for-id--8253242879)<br/>
> > > [Visualization of all 7 users](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#visualization-of-all-7-users)<br/>

> [4.2 - Understand the users habits](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#42---understand-the-users-habits)<br/>
> > [4.2.1 - Steps classification](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#421---steps-classification)<br/>
> > [4.2.2 - Amount of users that achieved the minimum physical activity recommended by the American Heart Association](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#422---amount-of-users-that-achieved-the-minimum-physical-activity-recommended-by-the-american-heart-association)<br/>
> > [4.2.3 - Is there a preferred day of week for doing physical activity ?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#423---is-there-a-preferred-day-of-week-for-doing-physical-activity-)<br/>
> > [4.2.4 - In what period of the day users do more physical activity ?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#424---in-what-period-of-the-day-users-do-more-physical-activity-)<br/>
> > [4.2.5 - In what period of the day users spent more calories ?](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#425---in-what-period-of-the-day-users-spent-more-calories-)<br/>
> > [4.2.6 - The difference in activities betweens periods of the day and day of week](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#426---the-difference-in-activities-betweens-periods-of-the-day-and-day-of-week)<br/>
> > [4.2.7 - The difference in calories spent betweens periods of the day and day of week](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#427---the-difference-in-calories-spent-betweens-periods-of-the-day-and-day-of-week)<br/>
> > [4.2.8 - The difference in steps betweens periods of the day and day of week](https://github.com/leticiamchd/Google-Data-Analytics-Certificate/blob/main/Complete%20Report.md#428---the-difference-in-steps-betweens-periods-of-the-day-and-day-of-week)<br/>


## Introduction

### The Company
Bellabeat is a high-tech manufacturer of health-focused products for women. Is a successful small company, but they have the potential to become a larger player in the global smart device market.

- The Golden Circle <br/>
**Why** : The mission of Bellabeat is to empower women to reconnect with themselves, unleash their inner strengths and be what they were meant to be. <br/>
**How** : They do that with an ecosystem of products and services that focus on women’s health. <br/>
**What** : Wearables using feminine design and technology adjusted to female bodies.

### Why tracking health habits ?

Chronic disease can result in loss of independence, years of disability, or death, and impose a considerable economic burden on health services.
Today, chronic diseases are a major public health problem worldwide. In 2005, the World Health Organization (WHO) estimated that 61 per cent of all deaths -- 35 million -- and 49 per cent of the global burden of disease were attributable to chronic diseases. By 2030, the proportion of total global deaths due to chronic diseases is expected to increase to 70 per cent and the global burden of disease to 56 per cent.
The combination of four healthy lifestyle factors -- maintaining a healthy weight, exercising regularly, following a healthy diet, and not smoking -- seem to be associated with as much as an 80 per cent reduction in the risk of developing the most common and deadly chronic diseases.

https://www.un.org/en/chronicle/article/lifestyle-diseases-economic-burden-health-services 

## 1. Ask

### 1.1 - Business Task 

Identify trends in how consumers use non-Bellabeat smart devices and how these insights can be applied into Bellabeat’s marketing strategy.

**Stakeholders**<br/>
Urška Sršen - Bellabeat cofounder and Chief Creative Officer<br/>
Sando Mur - Bellabeat cofounder and key member of Bellabeat executive team<br/>
Bellabeat Marketing Analytics team

## 2. Prepare

### 2.1 - Where is the data stored ?

The Dataset named FitBit Fitness Tracker Data is available on Kaggle, in this link . It is available by the user Mobius.
 
For the analysis all dataset is going to be downloaded and stored into google’s drive folder.

### 2.2 - How is the data organized ?
 
The Dataset contains 18 files, listed below, and ordered by name.

**TABELA**

### 2.3 - Bias and credibility

**Reliable**: Not reliable because it doesn’t represent the overall population. Sample too small.<br/>
**Original**: Not original. Third party provider. Generated by respondents to a distributed survey via Amazon Mechanical Turk<br/>
**Comprehensive**: some information like demographics are missing<br/>
**Current**: Not Current. For the moment that this report is being made, this dataset is outdated (distributed between 03.12.2016 and 05.12.2016)<br/>
**Cited**: Unknown because was collected by a third party provider
 
### 2.4 - Security and Privacy 

The dataset has a license CC0: Public domain. So is permitted to copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.


## 3. Process

### 3.1 - Storage 
 
Download of all 18 csv files from kaggle database.

Storaged everything on google`s drive folder.

### 3.2 -  Filtering (Used Spreadsheets)

Approached each table and used "Filter" to check for Null values.

In Table 18, for the column "Fat" there was 65 blank spaces, corresponding for 97,01%, because of that, the entire column was deleted.

### 3.3 -  Changes (Used Spreadsheets)

All columns that contains DateTime was change for a 24h DateTime.<br/>

###  3.4 -  Unique users (Used SQL - Bigquery)

For access unique users in each tables

```sql
SELECT COUNT(distinct Id)
FROM **each table directory**
```


**Results**

**Table 1:**  dailyActivity_merged.csv - 33 unique users<br/>
**Table 2:** dailyCalories_merged.csv - 33 unique users<br/>
**Table 3:** dailyIntensities_merged.csv - 33 unique users<br/>
**Table 4**: dailySteps_merged.csv - 33 unique users<br/>
**Table 5:** heartrate_seconds_merged.csv - 14 unique users<br/>
**Table 6:** hourlyCalories_merged.csv - 33 unique users <br/>
**Table 7:**  hourlyIntensities_merged.csv - 33 unique users <br/>
**Table 8:**  hourlySteps_merged.csv - 33 unique users <br/>
**Table 9:** minutescaloriesNarrow_merged.csv - 33 unique users <br/>
**Table 10:** minuteCaloriesWide_merged.csv - 33 unique users <br/>
**Table 11:** minuteIntensitiesNarrow_merged.csv - 33 unique users <br/>
**Table 12:** minuteIntensitiesWide_merged.csv - 33 unique users <br/>
**Table 13:** minuteMETsNarrow_merged.csv - 33 unique users <br/>
**Table 14:** minuteSleep_merged.csv - 24 unique users <br/>
**Table 15:** minuteStepsNarrow_merged - 33 unique users <br/>
**Table 16:** minuteStepsWide_merged - 33 unique users <br/>
**Table 17:** sleepDay_merged.csv - 24 unique users <br/>
**Table 18:** weightLogInfo_merged - 8 unique users <br/>
 
### 3.5 - Round (Used SQL - Bigquery)
 
To make the number better for reading, some numbers were rounded with 2 decimals. Below, the information about each table. All columns that were motificated stayed with the same name previous the change adding "cleaned" in the end, and they were stored into a different dataset in Bigquery. <br/>
 
Table 1 - <br/>
Table 17 - 0 columns<br/>
Table 18 -  3 columns (WeightKg,WeightPounds,BMI)<br/>

## 4. Analyze 
### 4.1 - First, we are going to analyze the characteristics of app use 

#### 4.1.1 -  Adherence of each user, and classification in daily activities 

Using Table 1 that contains all users, we are going to check the adherence of each one per day. After that, classify them into: 

**Very low use:** < 25 % of the month<br/>
**Low use:** 25 ~ 50 % of the month<br/>
**Moderate use:** 50 ~ 75% of the month<br/>
**High use:** > 75% of the month<br/>

**SQL QUERY:** 
```sql
SELECT Id, frequency, frequency_percent,
CASE
  WHEN frequency_percent < 25 THEN 'Very Low Use'
  WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
  WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
  WHEN frequency_percent >= 75 THEN 'High Use'
  ELSE ''
  END AS use_classification
FROM
(
SELECT Id,
COUNT(Id) AS frequency, 
ROUND(COUNT(Id) / 31 * 100,2) AS frequency_percent
FROM `resonant-cairn-350019.Cleaned_google_capstone_CaseStudy.dailyActivity_cleaned` 
GROUP BY Id
) AS inner_query
 
GROUP BY Id, frequency, frequency_percent
ORDER BY frequency DESC
```
 
**RESULT:**
TABELA 

##### Now grouping by use_classification 

**SQL QUERY:**
```sql
SELECT
use_classification,
ROUND(COUNT(use_classification) / 33 *100,2) AS classification_percent
FROM
(
  SELECT Id, frequency, frequency_percent,
  CASE
   WHEN frequency_percent < 25 THEN 'Very Low Use'
   WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
   WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
   WHEN frequency_percent >= 75 THEN 'High Use'
   ELSE ''
   END AS use_classification
  FROM
    (
    SELECT Id,
    COUNT(Id) AS frequency, 
    ROUND(COUNT(Id) / 31 * 100,2) AS frequency_percent
    FROM `resonant-cairn-350019.Cleaned_google_capstone_CaseStudy.dailyActivity_cleaned` 
    GROUP BY Id
    ) AS inner_query
 
  GROUP BY Id, frequency, frequency_percent
  ORDER BY frequency DESC
)
 
GROUP BY use_classification
```
 
**RESULTS:**

TABELA

#### 4.1.2 - Adherence of each user, and classification in sleep
 
Like it was said before, not all 33 users tracked their sleep. Of 33 users, only 24 tracked their sleep (72,72%) . Now we are going to find how many days these 24 users tracked their sleeps, and classificate them.
 
**SQL QUERY:**
 
```sql
SELECT Id, frequency, frequency_percent,
CASE
  WHEN frequency_percent < 25 THEN 'Very Low Use'
  WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
  WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
  WHEN frequency_percent >= 75 THEN 'High Use'
  ELSE ''
  END AS use_classification
FROM
(
SELECT Id,
COUNT(distinct SleepDay) AS frequency, 
ROUND(COUNT(distinct SleepDay) / 31 * 100,2) AS frequency_percent
FROM `resonant-cairn-350019.google_case_study_2.sleep_day`
GROUP BY Id
) AS inner_query
 
GROUP BY Id, frequency, frequency_percent
ORDER BY frequency DESC
```
 
*Obs: The use of “distinct” before SleepDay was because one of the users tracked 2 naps in the same day.
 
**RESULTS**

TABELA

##### Now grouping by use_classification 

**SQL QUERY:**
 
```sql
SELECT
use_classification,
ROUND(COUNT(use_classification) / 24 *100,2) AS classification_percent
FROM
(
  SELECT Id, frequency, frequency_percent,
  CASE
   WHEN frequency_percent < 25 THEN 'Very Low Use'
   WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
   WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
   WHEN frequency_percent >= 75 THEN 'High Use'
   ELSE ''
   END AS use_classification
  FROM
    (
    SELECT Id,
    COUNT(distinct SleepDay) AS frequency, 
    ROUND(COUNT(distinct SleepDay) / 31 * 100,2) AS frequency_percent
    FROM `resonant-cairn-350019.google_case_study_2.sleep_day`
    GROUP BY Id
    ) AS inner_query
 
  GROUP BY Id, frequency, frequency_percent
  ORDER BY frequency DESC
)
 
GROUP BY use_classification
ORDER BY classification_percent DESC
```
 
**RESULTS:**

TABELA

#### 4.1.3 -Adherence of each user, and classification in weight
Not all 33 users tracked their weight. Of 33 users, only 8 tracked (24,24%) . Now we are going to find how many days these 8 users tracked their weight, and classificate them.
 
**SQL QUERY:**
 
```sql
SELECT Id, frequency, frequency_percent,
CASE
  WHEN frequency_percent < 25 THEN 'Very Low Use'
  WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
  WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
  WHEN frequency_percent >= 75 THEN 'High Use'
  ELSE ''
  END AS use_classification
FROM
(
SELECT Id,
COUNT(Date) AS frequency, 
ROUND(COUNT(Date) / 31 * 100,2) AS frequency_percent
FROM `resonant-cairn-350019.google_capstone_CaseStudy.weightLogInfo`
GROUP BY Id
) AS inner_query
 
GROUP BY Id, frequency, frequency_percent
ORDER BY frequency DESC
```
 
**RESULTS**

TABELA

##### Now grouping by use_classification 

**SQL QUERY:**
 
```sql
SELECT
use_classification,
ROUND(COUNT(use_classification) / 8 *100,2) AS classification_percent
FROM
(
  SELECT Id, frequency, frequency_percent,
  CASE
   WHEN frequency_percent < 25 THEN 'Very Low Use'
   WHEN frequency_percent >= 25 AND frequency_percent < 50 THEN 'Low Use'
   WHEN frequency_percent >= 50 AND frequency_percent < 75 THEN 'Moderate Use'
   WHEN frequency_percent >= 75 THEN 'High Use'
   ELSE ''
   END AS use_classification
  FROM
    (
    SELECT Id,
    COUNT(Date) AS frequency, 
    ROUND(COUNT(Date) / 31 * 100,2) AS frequency_percent
    FROM `resonant-cairn-350019.google_capstone_CaseStudy.weightLogInfo`
    GROUP BY Id
    ) AS inner_query
 
  GROUP BY Id, frequency, frequency_percent
  ORDER BY frequency DESC
)
 
GROUP BY use_classification
ORDER BY classification_percent DESC
```
 
**RESULTS:**

TABELA

#### 4.1.4 - Adherence of users in tracking their daily activities + sleep + weight

**SQL QUERY :**

**RESULTS:**

**VISUALIZATION:**

![Fig 4 1 4](https://user-images.githubusercontent.com/66830501/178830645-b0d4c4ea-27be-4c3f-afb1-5377cc494e65.png)

#### 4.1.5 -How many users tracked all 3 pillars (Activity, sleep, weight)?

First, create a table of frequency in each pilar

##### Daily activity

**SQL QUERY:**

```sql
SELECT 
Id, 
COUNT(distinct ActivityDate) As amount
 
FROM `resonant-cairn-350019.google_case_study_2.daily_activity`
 
GROUP BY Id
ORDER BY amount DESC
```

##### Sleep:

SQL QUERY:

```sql
SELECT 
Id, 
COUNT(distinct SleepDay) As amount # Distinct was used to remove duplicate day naps 
 
FROM `resonant-cairn-350019.google_case_study_2.sleep_day`
 
GROUP BY Id
ORDER BY amount DESC
```
 
##### Weight:

SQL QUERY:

```sql
SELECT 
Id, 
COUNT(distinct Date) As amount 
 
FROM `resonant-cairn-350019.google_case_study_2.weight_day`
 
GROUP BY Id
ORDER BY amount DESC
```

##### Joining all 3 tables:

SQL QUERY:

```sql
SELECT 
daily.Id, 
daily.amount AS DailyActivity_amount,
sleep.amount AS sleep_amount,
weight.amount AS weight_amount
 
FROM `resonant-cairn-350019.google_case_study_2.DailyActivity_frequency_users` AS daily
LEFT JOIN `resonant-cairn-350019.google_case_study_2.sleep_frequency_users` AS sleep
ON daily.Id = sleep.Id
LEFT JOIN `resonant-cairn-350019.google_case_study_2.weight_frequency_users` AS weight
ON daily.Id = weight.Id
```

##### Knowing how many completed at least one of all activities

```sql
SELECT 
COUNT(daily.Id)
 
FROM `resonant-cairn-350019.google_case_study_2.DailyActivity_frequency_users` AS daily
LEFT JOIN `resonant-cairn-350019.google_case_study_2.sleep_frequency_users` AS sleep
ON daily.Id = sleep.Id
LEFT JOIN `resonant-cairn-350019.google_case_study_2.weight_frequency_users` AS weight
ON daily.Id = weight.Id
 
WHERE sleep.amount IS NOT null AND weight.amount IS NOT null
```

6 of 33 user completed at least of all pillars (Activity/Sleep/Weight)

##### Knowing Who completed at least half of all activities, and how many days of each acitivity the person completed

```sql
SELECT 
daily.Id, 
daily.amount AS DailyActivity_amount
, sleep.amount AS sleep_amount
, weight.amount AS weight_amount
 
FROM `resonant-cairn-350019.google_case_study_2.DailyActivity_frequency_users` AS daily
LEFT JOIN `resonant-cairn-350019.google_case_study_2.sleep_frequency_users` AS sleep
ON daily.Id = sleep.Id
LEFT JOIN `resonant-cairn-350019.google_case_study_2.weight_frequency_users` AS weight
ON daily.Id = weight.Id
 
WHERE (sleep.amount IS NOT null AND weight.amount IS NOT null) AND (daily.amount >= 15 AND sleep.amount >= 15 AND weight.amount >=15)
```

**RESULTS:**

TABELA

The user 6962181067 tracked 31 days of activity, 31 days of sleep and 30 days of weight. This is the ideal user to compare the effects of all pillars together.

#### 4.1.6 - App usage of each user, per month

**SQL QUERY**

```sql
SELECT Id,
SUM(hour_per_day) AS hour_per_month,
ROUND(SUM(hour_per_day) / 744 *100,2) AS percentage_use_perMonth # 744 é a quantidade de horas em 31 dias
FROM
(
SELECT Id,
COUNT(ActivityHour) AS hour_per_day
FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyCalories`
GROUP BY Id 
) AS inner_query
 
GROUP BY Id
ORDER BY Id
```
 
**RESULTS**

This gave us a better look into the adherence of each user. In the previous analysis we could see the adherence in days, which gives us good information, but not complete. Someone can use everyday, but only 5 hour per day, or someone can use just for 10 days, but each day he used for 24 hours. So this query gives us a deep knowledge about adherence. So, knowing this, what happened with low users ? They just lowered the adherence through days or suddenly stopped using it ?

#### 4.1.7 - Average of device usage per day through time


**SQL QUERY:**

```sql
SELECT date,
ROUND(AVG(hour_per_day),2) AS avg_hour_per_day
FROM
(
  SELECT Id,
  EXTRACT(DATE FROM ActivityHour) AS date,
  COUNT(ActivityHour) AS hour_per_day
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyCalories`
  GROUP BY Id,date
)
WHERE hour_per_day != 0
GROUP BY date
```

**RESULTS:**

TABELA 

**VISUALIZATION:**

![Fig 4 1 7](https://user-images.githubusercontent.com/66830501/178831399-36af9fe4-adc1-4b95-893e-0e6b7fecfa5b.png)


O uso do aparelho se mantém bem perto das 24 horas, tendo algumas variações no caminho, provavelmente pela interrupção do uso de poucos usuários. Porém há uma queda brusca no último dia dos dados disponíveis. Isso levanta algumas questões: 1. O uso pode ter caído apenas porque não foram disponibilizados mais dados; 2. É um tempo médio de duração da bateria, sendo nesse dia necessário a retirada do aparelho para carregar

#### 4.1.8 -Digging into low adherence users 

With this query I can analyze the previous adherence of the user, and the day that he stops using or that has any changes into the hours per day. The chosen users for this deeper analysis were all that the time used per month was below the mean (90%). 

In one month, people was wearing the wearable at least 90% of the time 

**SQL QUERY**

```sql
SELECT Id,
EXTRACT(DATE FROM ActivityHour) AS date,
COUNT(ActivityHour) AS hour_per_day
 
FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyCalories`
 
WHERE id = 2347167796 
 
GROUP BY Id,date
```

**RESULTS**

##### For Id = 2347167796

TABELA

Suddenly stop in 29/04

##### For Id = 3372868164

TABELA

Suddenly stop in 01/05

##### For Id = 4057192912

TABELA

This user didn’t have a good adherence and then just stopped using on 15/04.

##### For Id = 6117666160

TABELA 

This user had a good adherence and then just stopped using on 09/05

##### For Id = 6290855005

TABELA

This user had a good adherence and then just stopped using on 09/05

##### For Id = 7007744171

TABELA

This user had a good adherence and then just stopped using on 07/05

##### For Id = 8253242879

TABELA

 
This user had a good adherence and then just stopped using on 29/04

We identificated a total of 7 users that didn’t use at least the mean number. And when digging into the way that these 7 users stopped using, we see that the majority suddenly stopped. Lost ? Got robbed ?

##### Visualization of all 7 users

![Fig 4 1 8 (1)](https://user-images.githubusercontent.com/66830501/178831986-607adcc5-8aab-4293-abe0-434f985d75a7.png)

### 4.2 - Understand the users habits 

#### 4.2.1 - Steps classification 
https://www.10000steps.org.au/articles/counting-steps/#:~:text=Low%20active%20is%205%2C000%20to,active%20is%20more%20than%2012%2C500

According to this, we are going to classificate de users:

Sedentary < 5,000 steps per day 
Low Active 5,000 ~ 7,499 steps per day 
Somewhat Active 7,500 ~ 9,999 steps per day 
Active > 10,000 steps per day 
Highly Active > 12,500 steps per day 
 
**SQL QUERY:**
 
```sql
SELECT Id,avg_steps, 
CASE 
  WHEN avg_steps < 5000 THEN 'Sedentary'
  WHEN avg_steps >= 5000 AND avg_steps < 7500 THEN 'Low Active'
  WHEN avg_steps >= 7500 AND avg_steps < 10000 THEN 'Somewhat Active'
  WHEN avg_steps >= 10000 AND avg_steps < 12500 THEN 'Active'
  WHEN avg_steps >= 12500 THEN 'Highly Active'
  ELSE ''
  END AS steps_classification
FROM 
(
SELECT Id, 
ROUND(AVG(StepTotal),2) AS avg_steps
FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailySteps`
GROUP BY Id
ORDER BY avg_steps DESC
) AS inner_query
```

**RESULTS:**

TABELA 

And for we know the percentage of each classification:

```sql
SELECT steps_classification, 
ROUND(COUNT(steps_classification) /33 * 100,2) AS percentage_stepsClassification
FROM
(
  SELECT Id,avg_steps, 
  CASE 
    WHEN avg_steps < 5000 THEN 'Sedentary'
    WHEN avg_steps >= 5000 AND avg_steps < 7500 THEN 'Low Active'
    WHEN avg_steps >= 7500 AND avg_steps < 10000 THEN 'Somewhat Active'
    WHEN avg_steps >= 10000 AND avg_steps < 12500 THEN 'Active'
    WHEN avg_steps >= 12500 THEN 'Highly Active'
    ELSE ''
    END AS steps_classification
  FROM 
  (
  SELECT Id, 
  ROUND(AVG(StepTotal),2) AS avg_steps
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailySteps`
  WHERE StepTotal != 0
  GROUP BY Id
  ORDER BY avg_steps DESC
  ) AS inner_query
)
 
GROUP BY steps_classification
ORDER BY percentage_stepsClassification DESC
```

**RESULTS:**

TABELA


**VISUALIZATION**

![Fig 4 2 1](https://user-images.githubusercontent.com/66830501/178832236-b5b87d6a-0605-4cf6-9a34-f8809461cc29.png)

#### 4.2.2 - Amount of users that achieved the minimum physical activity recommended by the American Heart Association 
https://www.heart.org/en/healthy-living/fitness/fitness-basics/aha-recs-for-physical-activity-in-adults

Very Active Minutes = Vigorous activity 
Fairly Active Minutes = Moderate activity

**SQL QUERY:**

```sql
SELECT  week, 
SUM(CASE
  WHEN sum_moderateActivity >= 150 OR sum_vigorousActivity >= 75 THEN 1
  ELSE 0
  END) AS recommendation_achieved
FROM
(
  SELECT Id,
  EXTRACT(WEEK FROM ActivityDate) AS week,
  ROUND(SUM(VeryActiveMinutes),2) AS sum_vigorousActivity ,
  ROUND(SUM(FairlyActiveMinutes),2) As sum_moderateActivity
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailyActivity`
 
  GROUP BY Id, week
) AS inner_query
 
WHERE week != 0
GROUP BY week
```

**RESULTS:**

TABELA 

But like we already saw, some users stopped tracking before the end of 31 days. So, for we know the percentage that achieved the activity recommendation in each week, we need to know how many users were still tracking their activity 

**SQL QUERY:**

```sql
SELECT week, users_remaining, recommendation_achieved,
ROUND(recommendation_achieved / users_remaining * 100,2) AS percentage_recommedationAchieved
 
FROM
(
  SELECT  week, COUNT(Id) AS users_remaining,
  SUM(CASE
    WHEN sum_moderateActivity >= 150 OR sum_vigorousActivity >= 75 THEN 1
    ELSE 0
    END) AS recommendation_achieved
  FROM
  (
    SELECT Id,
    EXTRACT(WEEK FROM ActivityDate) AS week,
    ROUND(SUM(VeryActiveMinutes),2) AS sum_vigorousActivity ,
    ROUND(SUM(FairlyActiveMinutes),2) As sum_moderateActivity
 
    FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailyActivity`
 
    GROUP BY Id, week
  ) AS inner_query
 
  WHERE week != 0
  GROUP BY week
)
```

**RESULTS:**


TABELA


This doesn’t show a high change between weeks.
If we see the average for the period of 31 days, 53,83% achieve the minimum recommendation by the American Heart Association, lower than we see in the hole population ( global prevalence of insufficient physical activity of 23·3% by The Lancet).


**VISUALIZATION:**

![Fig 4 2 2 (1)](https://user-images.githubusercontent.com/66830501/178832489-4a307c2c-0628-4d28-ba29-1615242a66da.png)

#### 4.2.3 - Is there a preferred day of week for doing physical activity ?

**SQL QUERY:**

```sql
SELECT 
CASE
  WHEN weekday = 1 THEN 'Sunday'
  WHEN weekday = 2 THEN 'Monday'
  WHEN weekday = 3 THEN 'Tuesday'
  WHEN weekday = 4 THEN 'Wednesday'
  WHEN weekday = 5 THEN 'Thursday'
  WHEN weekday = 6 THEN 'Friday'
  WHEN weekday = 7 THEN 'Saturday'
  ELSE ''
  END AS day_of_week,
ROUND(AVG(total_activity_minutes),2) AS avg_activity_week
FROM
(
  SELECT Id, ActivityDay,
  EXTRACT(DAYOFWEEK FROM ActivityDay) AS weekday,
  LightlyActiveMinutes + FairlyActiveMinutes + VeryActiveMinutes AS total_activity_minutes
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailyIntensities`
  WHERE Id != 0
) AS inner_query
 
 
GROUP BY day_of_week
ORDER BY avg_activity_week DESC
 ```
 
**RESULTS:**

TABELA

Saturday is the preferred day for doing physical activity, despite intensity. 
We have a bias here because any movement is considered Light Activity. So if we disconsider Light Activity is going to have any changes ?

**SQL QUERY:**

```sql
SELECT 
CASE
  WHEN weekday = 1 THEN 'Sunday'
  WHEN weekday = 2 THEN 'Monday'
  WHEN weekday = 3 THEN 'Tuesday'
  WHEN weekday = 4 THEN 'Wednesday'
  WHEN weekday = 5 THEN 'Thursday'
  WHEN weekday = 6 THEN 'Friday'
  WHEN weekday = 7 THEN 'Saturday'
  ELSE ''
  END AS day_of_week,
ROUND(AVG(total_activity_minutes),2) AS avg_activity_week
FROM
(
  SELECT Id, ActivityDay,
  EXTRACT(DAYOFWEEK FROM ActivityDay) AS weekday,
  FairlyActiveMinutes + VeryActiveMinutes AS total_activity_minutes
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.dailyIntensities`
  WHERE Id != 0
) AS inner_query
 
 
GROUP BY day_of_week
ORDER BY avg_activity_week DESC
```

**RESULTS:**

TABELA 

When we only consider fairly and highly activities, Tuesday becomes the preferred day of week for doing physical activity. 

#### 4.2.4 - In what period of the day users do more physical activity ?

**SQL QUERY:**

```sql
SELECT 
CASE
  WHEN hour >= 0 AND hour < 6 THEN 'Dawn'
  WHEN hour >= 6 AND hour < 12 THEN 'Morning'
  WHEN hour >= 12 AND hour < 18 THEN 'Afternoon'
  WHEN hour >= 18 THEN 'Night'
  ELSE ''
  END AS period_of_day,
ROUND(AVG(TotalIntensity),2) AS avg_intensity
 
FROM
(
  SELECT  TotalIntensity,
 
  EXTRACT(HOUR FROM ActivityHour) AS hour,
  
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyIntensities`
  WHERE TotalIntensity != 0
  GROUP BY  hour,TotalIntensity
)
GROUP BY period_of_day
ORDER BY avg_intensity DESC
```

**RESULTS:**

TABELA

#### 4.2.5 - In what period of the day users spent more calories ?

**SQL QUERY:**

```sql
SELECT 
CASE
  WHEN hour >= 0 AND hour < 6 THEN 'Dawn'
  WHEN hour >= 6 AND hour < 12 THEN 'Morning'
  WHEN hour >= 12 AND hour < 18 THEN 'Afternoon'
  WHEN hour >= 18 THEN 'Night'
  ELSE ''
  END AS period_of_day,
ROUND(AVG(avg_calories),2) AS calories
FROM
(
  SELECT  
 
  EXTRACT(HOUR FROM ActivityHour) AS hour,
  AVG(calories) AS avg_calories
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyCalories`
 
  GROUP BY  hour
)
GROUP BY period_of_day
ORDER BY calories DESC
```

**RESULTS:**

TABELA 

#### 4.2.6 - The difference in activities betweens periods of the day and day of week

**SQL QUERY:**

```sql
SELECT
CASE
  WHEN weekday = 1 THEN 'Sunday'
  WHEN weekday = 2 THEN 'Monday'
  WHEN weekday = 3 THEN 'Tuesday'
  WHEN weekday = 4 THEN 'Wednesday'
  WHEN weekday = 5 THEN 'Thursday'
  WHEN weekday = 6 THEN 'Friday'
  WHEN weekday = 7 THEN 'Saturday'
  ELSE ''
  END AS day_of_week,
CASE
  WHEN hour >= 0 AND hour < 6 THEN 'Dawn'
  WHEN hour >= 6 AND hour < 12 THEN 'Morning'
  WHEN hour >= 12 AND hour < 18 THEN 'Afternoon'
  WHEN hour >= 18 THEN 'Night'
  ELSE ''
  END AS period_of_day,
ROUND(AVG(avg_intensity)) avgIntensity
 
FROM
(
  SELECT  
  EXTRACT(DAYOFWEEK FROM ActivityHour) AS weekday,
  EXTRACT(HOUR FROM ActivityHour) AS hour,
  ROUND(AVG(TotalIntensity),2) AS avg_intensity 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyIntensities`
  WHERE Id != 0
  --GROUP BY  hour,TotalIntensity
  GROUP BY weekday,hour
)
 
GROUP BY day_of_week, period_of_day
```

**RESULTS:**

TABELA

##### AFTER TURNING WIDE INTO SPREADSHEETS

TABELA

#### 4.2.7 - The difference in calories spent betweens periods of the day and day of week

For this, I chose Table 6 - hourlyCalories , because the other tables that were separated by hours (steps and totalintensity) weren't adequate. The amount of steps can’t give the answer to this question, and the table of total intensities I couldn't understand exactly what it was measuring. 

**SQL QUERY**

```sql
SELECT
CASE
  WHEN weekday = 1 THEN 'Sunday'
  WHEN weekday = 2 THEN 'Monday'
  WHEN weekday = 3 THEN 'Tuesday'
  WHEN weekday = 4 THEN 'Wednesday'
  WHEN weekday = 5 THEN 'Thursday'
  WHEN weekday = 6 THEN 'Friday'
  WHEN weekday = 7 THEN 'Saturday'
  ELSE ''
  END AS day_of_week,
CASE
  WHEN hour >= 0 AND hour < 6 THEN 'Dawn'
  WHEN hour >= 6 AND hour < 12 THEN 'Morning'
  WHEN hour >= 12 AND hour < 18 THEN 'Afternoon'
  WHEN hour >= 18 THEN 'Night'
  ELSE ''
  END AS period_of_day,
ROUND(AVG(avg_calories)) avgCalories
 
FROM
(
 SELECT  
  EXTRACT(DAYOFWEEK FROM ActivityHour) AS weekday,
  EXTRACT(HOUR FROM ActivityHour) AS hour,
  AVG(calories) AS avg_calories
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlyCalories`
  WHERE Id != 0
  --GROUP BY  hour,TotalIntensity
  GROUP BY weekday,hour
)
 
GROUP BY day_of_week, period_of_day
```

**RESULTS:**


##### AFTER TURNING WIDE INTO SPREADSHEETS


**VISUALIZATION:**

![Fig 4 2 7](https://user-images.githubusercontent.com/66830501/178833412-8498afd0-3810-4985-a624-894c97009f65.png)

#### 4.2.8 - The difference in steps betweens periods of the day and day of week

**SQL QUERY **

```sql
SELECT
CASE
  WHEN weekday = 1 THEN 'Sunday'
  WHEN weekday = 2 THEN 'Monday'
  WHEN weekday = 3 THEN 'Tuesday'
  WHEN weekday = 4 THEN 'Wednesday'
  WHEN weekday = 5 THEN 'Thursday'
  WHEN weekday = 6 THEN 'Friday'
  WHEN weekday = 7 THEN 'Saturday'
  ELSE ''
  END AS day_of_week,
CASE
  WHEN hour >= 0 AND hour < 6 THEN 'Dawn'
  WHEN hour >= 6 AND hour < 12 THEN 'Morning'
  WHEN hour >= 12 AND hour < 18 THEN 'Afternoon'
  WHEN hour >= 18 THEN 'Night'
  ELSE ''
  END AS period_of_day,
ROUND(AVG(avg_steps)) avgSteps
 
FROM
(
 SELECT  
  EXTRACT(DAYOFWEEK FROM ActivityHour) AS weekday,
  EXTRACT(HOUR FROM ActivityHour) AS hour,
  AVG(StepTotal) AS avg_steps
 
  FROM `resonant-cairn-350019.google_capstone_CaseStudy.hourlySteps`
  WHERE Id != 0
  --GROUP BY  hour,TotalIntensity
  GROUP BY weekday,hour
)
 
GROUP BY day_of_week, period_of_day
 ```

**RESULTS:**

TABELA


**VISUALIZATION**

![Fig 4 2 8 (1)](https://user-images.githubusercontent.com/66830501/178833584-29faf6c3-6b4b-4578-a644-7e4fa34b8583.png)









 
















 

 


