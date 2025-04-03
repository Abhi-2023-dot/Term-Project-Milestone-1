# Data Wrangling Documentation

## 1. Introduction
This document outlines the data wrangling steps taken to clean and prepare the dataset(s) used for analysis in **Milestone 2**. The following datasets were processed:

- **Dataset 1:** Education Access Rate - This dataset, managed by UNICEF, focuses on the out-of-school children rate (SDG4.1.4), tracking the percentage of children not attending pre-primary to higher education. It includes: primary and lower sheets which highlights the country level data compared with many countries.

    Data Cleaning Steps: (KPI 1)
- Removing Duplicates: There were some duplicate entries in my data named as 'Region and Sub Region were removed to avoid bias in analysis.
- Standardizing Formats: 'Total Enrollment' was converted to Number(decimal)' format for consistency.
- Filtering Data: Removed rows of Wealth quintile e.g. poorest, second and richest etc. to focus on meaningful data.

- **Dataset 2:** Gender Parity Index - This dataset provides the Gender Parity Index (GPI) for primary and secondary school enrollment across various economies, measured as the ratio of female-to-male enrollment rates. 

    Data Cleaning Steps: (KPI 2)
- Standardizing Formats: 'Year' was converted to Number(decimal)' format for consistency.
- Filtering Data: Changed rows name from "Economy" to "Country" and "Economy Code to "Counrty Code"

- **Dataset 3:** Literacy Rate - This dataset provides literacy rates for youth (aged 15-24) and adults (aged 15+) across various countries, sourced from the UNESCO Institute for Statistics (UIS). It includes data on total literacy rates, as well as gender-specific rates (female and male), along with regional classifications and development statuses.

    Data Cleaning Steps: (KPI 3)
- Standardizing Formats: 'Total Enrollment', 'Male' and 'Female' were converted to Number(decimal)' format for consistency.
- Filtering Data: Changed rows name from "Countries and areas" to "Country" for better understanding.

- **Dataset 4:** School Completition - This dataset, provides detailed statistics on school completion rates globally, focusing on primary and lower secondary education levels. It includes data on completion rates by gender, residence (urban/rural), and wealth quintile, along with population demographics for various countries.

     Data Cleaning Steps: (KPI 4)
- Standardizing Formats: 'Total Enrollment', 'Male','Female', 'Rural' and 'Urban' were converted to Number(decimal)' format for consistency.
- Filtering Data: Changed rows name from "ISO3" to "Country Code" for better understanding.
- Removing Duplicates: There were some unneccesary data named as 'wealth quantile' and 'source'were removed to avoid bias in analysis.

- **Dataset 5:** Education Investment - This dataset, provides information on public spending on tertiary education as a percentage of total education spending in 2020 for various countries. It highlights the proportion of education budgets allocated to higher education, with Norway, Finland, and Luxembourg leading the list with the highest percentages.

     Data Cleaning Steps: (KPI 5)
- Standardizing Formats: 'Spending on Tertiary Education' was converted to Number(decimal)' format for consistency.
- Filtering Data: Changed rows name from "Category" to "Country" for better understanding.

## 2. Tool Used
- **Tableau Prep**

## 3. Description of the visualizations:

**KPI 1 (Education Access Rate)**
![Gender Distribution of Enrollment](img/EducationAccessRate.png)
This bar chart compares the enrollment rates of **female** and **male** students in the top 5 countries (Albania, Afganistan, Algeria, Angola, and Armenia). The visualization highlights gender disparities in education access, with some countries showing a higher enrollment rate for females, while others have a more balanced distribution. This analysis helps identify regions where targeted interventions may be needed to improve gender equality in education.

**KPI 2 (Gender Parity Index)**
![Geographic Distribution of Gender Parity](img/GenderParityIndex.png)
It shows the geographic distribution of the School Enrollment Gender Parity Index (GPI) across different countries. The map indicates color encoding to represent variations in GPI values, where higher values (closer to 1) indicate better gender parity and lower values indicate gender disparities.

**KPI 3 (Literacy Rate)**
![Average Enrollment Rates by Countires](img/LiteracyRates.png)
It shows the average enrollment rates by countries, all nations are defined by different colours and the numbers which are on top of the bars are "Total Enrollment" but on Y axis it shows in average.

**KPI 4 (School Completion)**
![Rural vs. Urban Enrollment Disparities by Country](img/SchoolCompletion.png)
It shows the total enrollment of students in schools from rural and urban areas according to top 5 countries. The disparity in Armenia is at the peak in urban area and least one is in Angola in rural.

**KPI 5 (Education Investment)**
![Spending on tertiary education by country](img/EducationInvestment.png)
This horizontal bar chart compares spending on tertiary education across different countries. The countries are listed on the Y-axis, and the percentage of spending is shown on the X-axis. The bars are sorted in descending order, so the countries with the highest spending appear at the top (e.g., Norway, Finland, Luxembourg)
