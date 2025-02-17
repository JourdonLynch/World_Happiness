# World_Happiness

# Introduction

We all have things that make us happy but it’s hard to quantify exactly what makes us happy. Nonetheless the world happiness index grants us insight into what specific countries value the most. THe purpose of this report is to determine how different facts impact our perceived happiness and draw general conclusions as to what we value most as a people.

# Data Validation and cleaning

 The Pandas, matplotlib.pyplot, and seaborn libraries were imported to conduct the cleaning and analysis.

• The initial dataframe consisted of 135 rows and 10 columns
• The country column contained the object data type and consisted of the names of 135 countries included in the study and had no null values. No changes were made.
• The social_support column contained the float64 data type and ranked countries based on their social support. 1 null value was found and filled with the mean column value instead of removing the row. 
• The freedom column contained the float64 data type and ranked countries based on their freedom. 1 null value was found and filled with the mean column value instead of removing the row. 
• The corruption column contained the float64 data type and ranked countries based on their corruption. 8 null value was found and filled with the mean column value instead of removing the row. 
• The generosity column contained the float64 data type and ranked countries based on their gnerosity. 1 null value was found and filled with the mean column value instead of removing the row.
• The gdp_per_cap column contained the int64 data type and consisted of the gdp of 135 countries included in the study and had no null values. No changes were made.
• The life_exp column contained the float64 data type and consisted of the names of  the lif eexpectancy of 135 countries included in the study and had no null values. No changes were made.
• The happiness column contained the int64 data type and consisted of the happiness scores of the 135 countries included in the study and had no null values. No changes were made.
