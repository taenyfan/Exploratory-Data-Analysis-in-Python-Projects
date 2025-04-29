# Testing for ShoeFly.com

##  Introduction

This is a project from **Codecademy** designed to practice A/B testing techniques. The fictional company under analysis is an online shoe store called **ShoeFly.com**.

ShoeFly is currently running two different versions of an ad. These ads are placed in:

- Emails  
- Banner ads on Facebook  
- Twitter  
- Google  

The company wants to analyze how these ads are performing across different platforms and days of the week. Your task is to help interpret the data using aggregate measures.

---

## Project Goals

Analyze the data from an A/B test using **Python**. Key questions to answer:

- How many views came from each `utm_source`?
- Was there a difference in click rates for each source?
- Were approximately the same number of people shown both ads?
- Did clicks vary by day of the week?
- Based on the data, do you recommend using **Ad A** or **Ad B**?

---

## Data Description

ShoeFly has provided the dataset in a CSV file named `ad_clicks.csv`, which contains the following columns:

- `user_id` – Unique ID of the user
- `utm_source` – Location where the ad was placed (e.g., Google, Facebook)
- `day` – Day of the week the ad was viewed
- `ad_click_timestamp` – Timestamp of the ad click (NaN if not clicked)
- `experimental_group` – The version of the ad the user saw: **A** or **B**

---
