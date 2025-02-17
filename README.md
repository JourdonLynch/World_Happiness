# World_Happiness

# Introduction

We all have things that make us happy but it’s hard to quantify exactly what makes us happy. Nonetheless the world happiness index grants us insight into what specific countries value the most. THe purpose of this report is to determine how different facts impact our perceived happiness and draw general conclusions as to what we value most as a people.

# Data Validation and cleaning

 The Pandas, matplotlib.pyplot, and seaborn libraries were imported to conduct the cleaning and analysis.

The initial dataframe consisted of 135 rows and 10 columns
• The country column contained the object data type and consisted of the names of 135 countries included in the study and had no null values. No changes were made.

• The social_support column contained the float64 data type and ranked countries based on their social support. 1 null value was found and filled with the mean column value instead of removing the row.

• The freedom column contained the float64 data type and ranked countries based on their freedom. 1 null value was found and filled with the mean column value instead of removing the row. 

• The corruption column contained the float64 data type and ranked countries based on their corruption. 8 null value was found and filled with the mean column value instead of removing the row. 

• The generosity column contained the float64 data type and ranked countries based on their gnerosity. 1 null value was found and filled with the mean column value instead of removing the row.

• The gdp_per_cap column contained the int64 data type and consisted of the gdp of 135 countries included in the study and had no null values. No changes were made.

• The life_exp column contained the float64 data type and consisted of the names of  the lif eexpectancy of 135 countries included in the study and had no null values. No changes were made.

• The happiness column contained the int64 data type and consisted of the happiness scores of the 135 countries included in the study and had no null values. No changes were made.

# Exploratory Analysis

Happiness scores were broken down into seven distinct groups representing different regions. Europe, Oceania, North America, South America, Asia, and Africa. While Russia resides in both europe and Asia for the purpose of this analysis it was placed in the European group as the majority of its population resides there. Asia and Europe have the largest interquartile range at 55 while Oceania had the lowest interquartile range at 1.50. North America, South America, and Africa exhibited outliers representing Haiti, Venezuela, and South Sudan respectively.

Figure 1

<img width="616" alt="Screenshot 2025-02-16 at 9 31 03 PM" src="https://github.com/user-attachments/assets/776dae40-ca88-486d-a5a9-2966c712747e" />

#

The top 10 happiest countries were Finland, Denmark, Norway, Iceland, Netherlands, Switzerland, Sweden New Zealand, Canada , and Austria respectively. Eight of the happiest countries reside in Europe while the remaining two being from Oceania and North America. The happiest country in the world was Finland with a happiness score of 155.

Figure 2

<img width="618" alt="Screenshot 2025-02-16 at 9 35 45 PM" src="https://github.com/user-attachments/assets/6a927f36-f03e-4d3b-b771-930287a5c685" />

#

The bottom 10 happiest countries were in the world were South Sudan, Central African Republic, Afghanistan, Tanzania, Rwanda, Yemen, Malawi, Sria, Botswana, and Haiti respectively. Six of the 10 least happy countries reside in Africa with three of the remaining four residing in Asia and one being in North america. The leaat happy country in the world was South Sudan with a happiness score of 0.

Figure 3

<img width="619" alt="Screenshot 2025-02-16 at 10 05 14 PM" src="https://github.com/user-attachments/assets/f3c94162-f5a9-4b51-bbff-365ea55289d9" />


# 

In addition to happiness, countries were ranked on six different metrics: social support, freedom, corruption, generosity, gdp per capita, and life expectancy. To measure the impact different metrics had on the happiness of a country the pearson correlation coefficient was calculated and countries were plotted using a scatterplot including a linear regression line. 

Figure 4

In addition to happiness, countries were ranked on six different metrics: social support, freedom, generosity, gdp per capita, life expectancy, and corruption. To measure the impact different metrics had on the happiness of a country the pearson correlation coefficient was calculated and countries were plotted using a scatterplot including a linear regression line.  The closer a countries rank was to 1 the greater the  social support, freedom, generosity, and gdp per capita it had while also indicating lower corruption. A green to red diverging color map was used to indicate rankings from 1 to 143.  


