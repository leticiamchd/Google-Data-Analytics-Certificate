

#### 1. Adherence of each user 

```sql 
SELECT Id,
COUNT(Id) AS frequency
FROM `resonant-cairn-350019.google_case_study_2.daily_activity` 


GROUP BY Id
ORDER BY frequency DESC
```

User X Frequency 

```sql 
SELECT Id,
COUNT(Id) AS frequency,
COUNT(Id) / 31 * 100 AS frequency_percent
FROM `resonant-cairn-350019.google_case_study_2.daily_activity` 


GROUP BY Id
ORDER BY frequency DESC
```

User X Frequency percentage 
 * The majority of user (32 of 33) used at least half days
 * More than the half users (21 of 33) used all 31 days 

#### 2. Average of all users

```sql
SELECT 
ROUND(AVG(TotalSteps),2) AS avg_total_steps,
ROUND(AVG(TotalDistance),2) AS avg_total_distance,
ROUND(AVG(Calories),2) AS avg_calories,
ROUND(AVG(VeryActiveMinutes),2) AS avg_VeryActiveMinutes,
ROUND(AVG(FairlyActiveMinutes),2) AS avg_FairlyActiveMinutes,
ROUND(AVG(LightlyActiveMinutes),2) AS avg_LightlyActiveMinutes,
ROUND(AVG(SedentaryMinutes),2) AS avg_SedentaryMinutes
FROM `resonant-cairn-350019.google_case_study_2.daily_activity` 

```

avg_total_steps	7637.91
avg_total_distance	5.49
avg_calories	2303.61
avg_VeryActiveMinutes	21.16
avg_FairlyActiveMinutes	13.56
avg_LightlyActiveMinutes	192.81
avg_SedentaryMinutes 991.21

#### 3. Adherence of user in each pilar (Daily Activity / Sleep / Weight)

First, create a table of frequency in each pilar 

Daily activity 
```sql 
SELECT 
Id, 
COUNT(distinct ActivityDate) As amount

FROM `resonant-cairn-350019.google_case_study_2.daily_activity`

GROUP BY Id
ORDER BY amount DESC
``` 

Sleep 
```sql
SELECT 
Id, 
COUNT(distinct SleepDay) As amount # Distinct was used to remove duplicate day naps 

FROM `resonant-cairn-350019.google_case_study_2.sleep_day`

GROUP BY Id
ORDER BY amount DESC
```

Weight

```sql 
SELECT 
Id, 
COUNT(distinct Date) As amount 

FROM `resonant-cairn-350019.google_case_study_2.weight_day`

GROUP BY Id
ORDER BY amount DESC
```

Joining all 3 tables 

```sql 
SELECT 
daily.Id, 
daily.amount AS DailyActivity_amount,
sleep.amount AS sleep_amount,
weight.amount AS weight_amount

FROM ...DailyActivity_frequency_users` AS daily
LEFT JOIN ...sleep_frequency_users` AS sleep
ON daily.Id = sleep.Id
LEFT JOIN ...weight_frequency_users` AS weight
ON daily.Id = weight.Id
```

#### Knowing how many completed at least one of all activities 

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

6 of 33 user completed at least of all activities

#### Knowing how many completed at least half of all activities 

```sql 
SELECT 
COUNT(daily.Id)

FROM `resonant-cairn-350019.google_case_study_2.DailyActivity_frequency_users` AS daily
LEFT JOIN `resonant-cairn-350019.google_case_study_2.sleep_frequency_users` AS sleep
ON daily.Id = sleep.Id
LEFT JOIN `resonant-cairn-350019.google_case_study_2.weight_frequency_users` AS weight
ON daily.Id = weight.Id

WHERE (sleep.amount IS NOT null AND weight.amount IS NOT null) AND (daily.amount >= 15 AND sleep.amount >= 15 AND weight.amount >=15)
```
 Just 1 person completed at least half of all activities 
 
#### Knowing Who completed at least half of all activities, and how many days of each acitivity the person completed 

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
The user 6962181067 tracked 31 days of activity,  31 days of sleep and 30 days of weight. 
This is the ideal user to compare the effects of all pilars together 







						
