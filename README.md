# Coupon Acceptance Analysis

## Overview
This project analyzes customer behavior in response to driving coupons across different categories, such as bars, coffee houses, and restaurants. The data was collected through a survey on Amazon Mechanical Turk and describes various driving scenarios, including the destination, current time, weather, and passenger type. The objective is to determine the factors that influence whether a customer accepts a coupon (`Y=1`) or rejects it (`Y=0`).

## Dataset
The dataset contains user attributes like age, income, and marital status, along with contextual information like destination, time, weather, and passenger. It includes five types of coupons:
1. Less expensive restaurants (under $20)
2. Coffee houses
3. Carry out & takeaway
4. Bars
5. More expensive restaurants ($20 - $50)

## Key Findings

### Bar Coupons
- **Problem Statement**: The analysis focuses on understanding which factors influence the acceptance of bar coupons. Key attributes such as age, bar visit frequency, and passenger type were explored.
- **Acceptance Rate**: 49.3% of bar coupons were accepted, with acceptance rates significantly higher for frequent bar visitors (more than once a month) and drivers over 25.
- **Key Insights**:
  - Frequent bar visitors are more likely to accept coupons, making this a key target group.
  - Older customers (over 25) and those without children are more likely to accept bar coupons.

### Coffee House Coupons
- **Problem Statement**: We analyzed coffee house coupons to see how factors like visit frequency and age influence acceptance.
- **Acceptance Rate**: 60.2% of coffee house coupons were accepted, with higher acceptance rates among younger frequent visitors.
- **Key Insights**:
  - Younger customers and frequent visitors to coffee houses (more than once a month) tend to accept coupons more often.


Jupyter Notebook
You can find the full analysis in the Jupyter Notebook here: [Link to the Jupyter Notebook](notebooks/coupon_analysis.ipynb)
