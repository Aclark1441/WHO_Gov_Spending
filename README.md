# WHO_Gov_Spending
An Excel based project camparing government spending on maternal health with data sourced from the World Health Organization. Special Attention was given to data cleaning, transformation, and Exploratory Analysis. 

## Exploratory Analysis
*Questions used to drive analysis were as follows:*</br>
- Which countries spent the most on contraceptive, reproductive, and maternal health conditions as a percentage of their health care spending in 2019?</br>
- Is there a correlation between the percentage of health care spending on reproductive health and maternal conditions?</br>
- Is there a correlation between the percentage of health care spending on contraceptive and maternal conditions?</br>

#Explaoratory Visualizations
The following visualizations were used to answer the first question if which countries spent the most in each of the three areas. 
<<Insert >>

The following visualizations were created to evaluate the correlations between spending on reproductive health or contraception and spending on maternal conditions. 
<<insert>>


# Results 
In regards to a correlation between Reproductive health spending and spending on maternal conditions; There was a slight correlation between the two variables. For most cases, countries spent a similar percentage of their total health expenditures on both supporting reproductive health and treating maternal conditions in 2019.  Countries that stand out from this pattern are Liberia and Comoros who each spent approximately 75% less on treating maternal health conditions than reproductive health. 

When exploring a correlation between contraceptive spending and maternal condition spending; the negative correlation was smaller than early assumptions. The 2019 data did show a tendency for countries with lower contraceptive spending to have a higher percentage of spending on maternal conditions; however, mathematical calculations did not give a reliable r2 value to deny coincidence in the observation.  Interestingly, Liberia and Comoros spent nearly three times the percentage of their total healthcare spending on contraceptives than countries like Chad, Burundi, and Namibia. As a result Liberia's and Comoros's maternal condition spending is less than a quarter of the other 3 countries 

When considering contraceptive spending, it is important to note that  the majority of the countries spend less than 4% of their total health care spending on contraception and family planning with documented maternal condition spending between 0.5 % and 25% of their health spending therefore a lack of spending on contraception cannot determine a high percentage of spending on maternal conditions.

# Limitations
The scope of the data set analyzed does not allow us to make concrete conclusions about whether spending in contraceptive and reproductive health reduces spending on maternal condition. External factors like each country's GDP and budget in terms of an international currency would aid in presenting the data to the lay person. 

Furthermore, the percent of the budget used does not attest to the efficiency of the money spent. More efficient health care systems can reduce costs, thus allowing a smaller budget to assist more patients.

## Data Exploration & Cleaning


## Data Acquisition

The data used in this analysis was downloaded from the WHO Global Health Expenditure Database on December 4th, 2023. [WHO Data Platform](https://platform.who.int/data/maternal-newborn-child-adolescent-ageing)


## Data Cleaning & Transformation

Data cleaning was limited too adjusting formatting and filtering data. Instances of null values were not included in visualizations or calculations.  

The original data set included the numeric data-- the percent of spending in each category-- in 2 formats  labeled "Value Numeric"  and  "Value String" which is formatted as numeric data and a string being the numeric value rounded to the nearest whole number.  During the data exploration phase, an additional column was created to portray the numeric data as a percentage for ease of interpretation. ("Value Percent")

A pivot table was then made to group countries spending data. The original data separated each country's spending by the source of funding; government, private, and external aid. Bar graphs created from this pivot table are included ___HERE_____.
