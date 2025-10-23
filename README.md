# AirBnB Data Analysis Dashboard

### [Click Here for the Live Interactive Dashboard](https://public.tableau.com/app/profile/dev.adapa/viz/AirBnBFullProject_17612127068370/Dashboard1?publish=yes)

---

### Dashboard Preview
<img width="1838" height="730" alt="Dashboard 1" src="https://github.com/user-attachments/assets/53eb382b-c3e0-46e9-9818-af5d6251ee4b" />


---

## 1. Project Overview
The goal of this project was to analyze AirBnB listing data to identify pricing trends, property distribution, and key factors influencing host success.

This dashboard answers key business questions, such as:
* What is the average price per night based on neighborhood or room type?
* Where are the most popular listings concentrated?
* What are the top 5 most expensive zipcodes in our market?
* Did our revenue grow consistently, or were there specific periods of high growth?
* What is our most common listing type (in terms of bedroom count)?


---

## 2. Data Source
The data used for this dashboard analysis is publicly available from **Inside Airbnb**.

* **Website:** [Inside Airbnb](https://insideairbnb.com/get-the-data/)
* **Dataset:** The specific file used contains **3,815 rows** of Airbnb listings.
* **Key Fields Used:** The analysis primarily focused on the following columns:
    * `neighbourhood`
    * `room_type`
    * `price`
    * `zipcode`
    * `latitude`
    * `longitude`
    * `number_of_reviews`

Data was cleaned in Excel to remove null values and standardize room_type entries.

---

## 3. Key Insights & Findings
* **Finding 1:** The most expensive zipcode is 98134, with an average price significantly over $200. This is followed by 98109, 98121, and 98136.
* **Finding 2:** The market is dominated by 1-bedroom listings (1,811 units). The number of available listings drops sharply as the bedroom count increases, with only 55 listings for 4-bedroom properties.
* **Finding 3:** The most significant growth occurred between March and late May

---

## 4. Tools Used
* **Tableau:** For all data visualization and dashboard creation.
* **Excel:** For data cleaning.
