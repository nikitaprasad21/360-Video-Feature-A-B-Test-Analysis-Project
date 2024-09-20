# 360-Video-Feature-A-B-Test-Analysis-Project


## Project Background

This project was conducted for an E-commerce platform in the fashion industry. The objective was to evaluate the impact of adding 360-degree product videos on product pages to assess whether this feature increases conversion rates and revenue. The platform operates in a highly competitive industry, employing a customer-centric business model with millions of active users. 

A/B testing was employed to compare the performance of a product page with the 360-degree video feature against a standard page with static images, with the goal of identifying if the new feature leads to a measurable increase in conversion rates and overall revenue.

![Screenshot 2024-06-17 141822](https://github.com/nikitaprasad21/360-Video-Feature-A-B-Test-Analysis-Project/assets/84131752/df3047a5-467c-4133-870a-af146f7d8648)

**Key performance indicators (KPIs)** included user interaction, conversion rate, and revenue generation.

## Executive Summary

The 360-degree product video feature had a significant positive impact on user engagement and revenue generation:

* **Conversion Rates**: The treatment group had a 16.24% conversion rate, significantly higher than the control group’s 9.85% conversion rate.
* **Revenue**: The treatment group saw a 2.87% increase in ARPU compared to the control group.
* **User Engagement**: The 360-degree videos led to a 64.77% increase in user interaction, indicating a substantial improvement in engagement.

  ![Chi-Square-Plot-1 jpg](https://github.com/user-attachments/assets/94af8c48-1345-4332-8f25-b2a3cd2045b3)

## Codes
The Python Codes used to inspect and determined whether observed differences were statistically significant using **Chi-square test χ² of Independences** can be found [here](https://github.com/nikitaprasad21/360-Video-Feature-A-B-Test-Analysis-Project/blob/main/notebooks/AB_Test_Experiment_Evaluation_Results.ipynb).

## Insights 
#### Category 1: Conversion Rate Analysis

  * Conversion rates in the treatment group were 16.24%, compared to 9.85% in the control group, a significant improvement.
  
    [Visualization: Conversion Rate Comparison](https://github.com/user-attachments/assets/8210ba7a-5b1a-491a-b2dc-7beb99e043fd)

#### Category 2: User Engagement
  * User engagement, measured by session duration, increased by 64.77% for the treatment group, indicating that 360-degree videos retain user attention longer.

#### Category 3: Revenue Impact
   *  The treatment group showed a 2.87% rise in ARPU, indicating that users exposed to 360-degree videos were more likely to purchase higher-value items.

#### Category 4: Statistical Significance

   * A chi-square test resulted in a p-value of 1.2051806921819425e-197, confirming a statistically significant difference between the control and treatment groups.

     [Visualization: Mosaic Plot of Chi-square Test](https://github.com/user-attachments/assets/78e90b27-eb18-401e-92ec-a21aa42f8fe6), further supporting the observed impact on conversion rates.

## Recommendations
Based on the insights, the following recommendations are suggested:

1. **Full Rollout of 360-Degree Videos**: Given the clear improvement in user engagement and revenue, the 360-degree video feature should be fully deployed across all product categories, prioritizing high-value items.
2. **Continuous Testing**: Continue A/B testing with additional product types (such as shoes or bags) to fine-tune the impact.
3. **Cross-Device Optimization**: Ensure the feature is optimized for mobile users to maximize engagement, as interaction rates were notably higher on desktops during the test.


## Assumptions and Caveats
* Users in both control and treatment groups were randomly assigned, ensuring no bias in the selection process.
* The test was conducted over a limited timeframe (for January 2024); longer-term trends may differ.
