# 360-Video-Feature-A-B-Test-Analysis-Project


## Introduction

A/B Testing, also known as **split testing or bucket testing**, used for comparing two versions of features (typically, a webpage or app feature) against each other to determine which one performs better, ensuring data-driven decision-making for the feature implementation on the production.

##  Problem Statement:
Evaluate the impact of adding 360-degree product videos feature on the product page on sales for an E-Commerce Platform. 

![Screenshot 2024-06-17 141822](https://github.com/nikitaprasad21/360-Video-Feature-A-B-Test-Analysis-Project/assets/84131752/df3047a5-467c-4133-870a-af146f7d8648)


The goal is to determine whether including 360-degree product videos increases the conversion rate and overall revenue compared to a product page without these videos and only images of the products.

## Work Process
Using **Chi-square test χ² of Independences**: This test is used to determine if there is a significant association between two categorical variables.

Here, in this case, the two variables are:

* Group (Control vs. Treatment)
* Conversion (0 for no purchase, 1 for purchase)

By constructing a contingency table that cross-tabulates the counts of conversions and non-conversions for both control and treatment groups, the chi-square test assesses whether the observed differences in conversion rates between the groups are statistically significant or if they could have occurred by chance.

##### Hypothesis Formulation:

* **Null Hypothesis (𝐻0)**: There is no difference in conversion rates or revenue between the control and treatment groups.
* **Alternative Hypothesis (𝐻1)**: The treatment group (with 360-degree videos) has a higher conversion rate or revenue than the control group.

##### P-Value: 
To assess the significance of the result, I'll consider the typical p-value (< 0.05) indicates that the differences are unlikely to have occurred by chance, suggesting a significant association between the group and conversion rate.

## Final Conclusion

So, a low p-value indicates that there is a statistically significant difference in Conversion Rates between groups, as the observed differences between the two versions are unlikely to be due to chance.

The conducted A/B test demonstrated a significant positive effect on user engagement and revenue due to 360-degree product videos on the product page.

With 95% confidence level, the treatment group (which included the 360-degree product videos), exhibited a substantial increase of **1072.34% in user interaction** and **2.82% rise in overall revenue** compared to the control group.

This feature not only improved user interaction but also contributed to a notable increase in overall sales performance.
