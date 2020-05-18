# Hypothesis Testing

## Gender pay gap

### Aim: To test if there is a significant difference in the salaries, based on gender.

Refer the excel sheet attached to this folder,

<i>if the values in one sample revel no information about the other, they are **Independent**</i>

Here using hypothesis test for mean salary.
-   H<sub>0</sub> : &micro;<sub>male</sub> - &micro;<sub>female</sub> = 0
-   H<sub>1</sub> : &micro;<sub>male</sub> - &micro;<sub>female</sub> &ne; 0

Data is categorized into two samples as for male and females, therefore we are using t-test since independent samples

Formula to calculate sample variance:
<br>
<img src="./Images/sample_variance.png" />
<br>
Formula to calculate T-Score:
<br>
<img src="./Images/T_Score.png" />
<br>

After calculating the p-value(0.182) and found that 0.182 >> all common levels of significance like 99%, 95%, 90%
We cannot reject the null hypothesis, there isn't enough evidence that there is a gender wage gap in this firm.

Now let's segment the data into two groups as age less than 35 and greater than 35
<img src="./Images/segment_by_age.png" />
