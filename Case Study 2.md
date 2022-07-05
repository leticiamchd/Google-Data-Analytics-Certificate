

####1. Adherence of each user 

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

####2. Average of all users

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

####3. Average of user that completed all 31 days


						
