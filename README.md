# Education for Sustainable Development (ESD)  

*By: Abhishek Verma*
## A Decision Intelligence Approach to Understanding Sustainable Development Goal (SDG) 4  

# Executive Summary


In order to achieve Sustainable Development Goal 4 (SDG 4), which is to guarantee inclusive and high-quality education for all, this project focuses on examining global trends in education. It investigates learning outcomes, gender equality, and accessibility to education in various geographical areas using global datasets. Finding important issues, patterns, and policy suggestions to enhance educational systems around the world is the aim.

[Read the full background here](Background.md)

## Key performance Indicators (KPIs)

### Education Access Rate (EAR)

<!-- It would be good to place a value proposition to measuring this in this space.  For example: -->
Measuring the Education Access Rate provides a framework for assessing progress, identifying disparities, informing policy, and fostering inclusivity in education, ultimately contributing to sustainable development and social equity.

Summary Details:
* Calculates the proportion of kids with primary and secondary school enrollment.
* Goal: - 95% worldwide enrollment rate

<!-- Repeat for the KPIs below -->
### Gender Parity Index (GPI)

The GPI is a measure used to assess the relative access to education between genders. It is calculated by dividing the number of female students by the number of male students in a specific educational level. A GPI of 1 indicates gender parity, while values below or above 1 highlight disparities. This index is vital for monitoring progress toward gender equality in education (aligned with UN SDG #4), identifying gaps, and informing policies aimed at promoting equal access and opportunities for all genders in educational settings.

Summary Details:
* Compares the rates of education enrollment for men and women.
* Goal: At every level, reach a ratio of 1.0 (equal access).

### Literacy Rate (LR)

* Proportion of the people with basic reading and writing skills.
* The goal is to raise global literacy rates to 90%.

### School Completion Rate (SCR)

* Determines what proportion of students finish each educational level.
* Goal: 85% of secondary school students should finish.

### Education Investment Index (EII)

* Calculates the proportion of GDP allocated to education by the government.
* Goal: Education should account for at least 4% of GDP.

# Analysis:

![Gender Distribution of Enrollment](img/EducationAccessRate.png)
This bar chart compares the enrollment rates of female and male students in the top 5 countries (Albania, Afganistan, Algeria, Angola, and Armenia). The visualization highlights gender disparities in education access, with some countries showing a higher enrollment rate for females, while others have a more balanced distribution. This analysis helps identify regions where targeted interventions may be needed to improve gender equality in education.
![Geographic Distribution of Gender Parity](img/GenderParityindex.png)
It shows the geographic distribution of the School Enrollment Gender Parity Index (GPI) across different countries. The map indicates color encoding to represent variations in GPI values, where higher values (closer to 1) indicate better gender parity and lower values indicate gender disparities
![Average Enrollment Rates by Countires](img/LiteracyRates.png)
It shows the average enrollment rates by countries, all nations are defined by different colours and the numbers which are on top of the bars are "Total Enrollment" but on Y axis it shows in average.
![Rural vs. Urban Enrollment Disparities by Country](img/SchoolCompletion.png)
It shows the total enrollment of students in schools from rural and urban areas according to top 5 countries. The disparity in Armenia is at the peak in urban area and least one is in Angola in rural.
![Spending on tertiary education by country](img/EducationInvestment.png)
This horizontal bar chart compares spending on tertiary education across different countries. The countries are listed on the Y-axis, and the percentage of spending is shown on the X-axis. The bars are sorted in descending order, so the countries with the highest spending appear at the top (e.g., Norway, Finland, Luxembourg)

### Heat Map:
![(Heat Map](https://github.com/Abhi-2023-dot/Term-Project-Milestone-1/blob/main/img/Heatmap_Termproject.png?raw=true)

Analyzing the heat map, we can observe the following important relationships:

**1. Color Coding:**

  -Red indicates a strong positive correlation (+1).
  
  -Blue represents a negative correlation.
  
  -White or light colors indicate weak or no correlation (~0).

  **2. Key observations:**

  **Positive Correlation**

"Total Enrollment" and "Female" (1.00)

"Total Enrollment" and "Male" (0.99)

"Female" and "Male" (0.98)

  **Negative Correlation:**

"Urban percentage" negatively correlates with "Total Enrollment" (-0.38) and "Female" (-0.38).

  **Weak Correlations:**

"Pop total" has weak correlations with all variables (~0.02).

**3. Interpretation:**

The strong correlation between "Total Enrollment" and gender-specific enrollment (Female/Male) suggests that total enrollment is nearly equally influenced by both genders.

The negative correlation between "Urban percentage" and total enrollment might suggest that rural areas have higher enrollment rates.

# Conclusion
Both male and female students contributed equally, as shown by the heatmap's strong positive correlations between overall enrollment and gender-specific enrollments.  Nonetheless, the opposite correlation between the percentage of urban residents and overall enrollment raises the possibility that enrollment rates are higher in rural regions.  Furthermore, there are weak correlations between the population total and other KPIs, suggesting that enrollment trends may not be significantly influenced by it.  Demographic influences on school enrollment can be better understood with the aid of this analysis.

[Background](Background.md)

[Table of Contents](Table_of_contents.md)

[Data Wrangling Methods](src/Wrangling.md)

