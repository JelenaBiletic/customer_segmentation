# customer_segmentation
This project focuses on customer segmentation, where we use SQL and Python to analyze customer data and assign tailored perks to different customer groups based on their preferences and behaviors. The goal is to leverage data‬
to better understand our customers and, ultimately, enhance customer retention.

<img width="269" alt="Screenshot 2024-09-04 at 23 51 48" src="https://github.com/user-attachments/assets/86fb261e-a71a-4f33-b4d0-eef4f94f7fb7">

# **TravelTide: Loyalty Perks Program**
### **Executive Summary - Jelena Biletic**
## **INTRODUCTION**
Our company has experienced rapid growth by leveraging its superior data aggregation and search technology, which provides customers with the largest travel inventory in the industry. However, this focus on expansion has led to an underdeveloped customer experience, resulting in low retention rates. To address this challenge, our company has initiated a strategic project aimed at developing loyalty perks for our customers. This initiative focuses on deeply understanding customer behavior, identifying key personalization opportunities, and implementing data-driven strategies designed to enhance customer retention and improve the overall customer experience. This report summarizes the findings from our comprehensive data analysis, which involved segmenting our user base into five distinct groups, and provides actionable recommendations for moving forward.
## **METHODOLOGY**
Our analysis involved a comprehensive review of customer demographics, booking patterns, engagement metrics, and transaction data. To ensure that we focused on customers who are currently active, we selected a cohort of users who had logged eight or more sessions on the platform since January 4, 2023. For customer segmentation, we employed a rule-based approach, utilizing criteria such as the number of trips, discount rates, and other relevant factors. After segmenting the customers into distinct groups, we conducted a detailed analysis of each segment to identify their unique user profiles, travel behaviors, and the types of benefits that would most effectively meet the needs of each group.
## **KEY FINDINGS**
We identified five key customer segments based on purchasing behavior, demographics and engagement levels.

<img width="655" alt="Screenshot 2024-09-04 at 21 09 36" src="https://github.com/user-attachments/assets/0e84fd48-c5de-40e5-9cc7-ab77dd7b1027">

The **Dreamers** are active customers who plan trips but never complete them (average trips: 0.0, cancellation rate: 100%). They tend to plan high-cost, long-distance travel (average flight price: 2,004.40, average hotel price: 1,764.89, average flight distance: 11,985 km), indicating a preference for top-tier destinations. To help this segment turn their travel aspirations into reality, we recommend offering **Exclusive Planning Tools**, which will support them in better organizing and committing to their travel plans.

<img width="667" alt="Screenshot 2024-09-04 at 23 35 28" src="https://github.com/user-attachments/assets/2e8c81f7-0afb-4864-a4f2-dca94bb5a524">

**Business Travelers** are our most loyal customers, with a high frequency of travel primarily for work (average trips: 4.53, average flights: 4.04, cancellation rate: 19%). They are less motivated by discounts (discount flight rate utilization: 30%) and prioritize time-saving benefits, perks, and loyalty rewards that enhance their experience. We recommend offering **Lounge Access** as a key perk to improve their comfort during frequent trips.

<img width="731" alt="Screenshot 2024-09-04 at 20 51 37" src="https://github.com/user-attachments/assets/e453fcfb-3f19-4d2a-b87a-9f7ecacaf721">

**Globetrotters** are highly motivated by discounts, with significant use of hotel (70%) and flight (80%) discounts. Although they travel less frequently (average trips: 1.74), they prefer distant, culturally rich destinations (average distance flown: 4,899.5 km). We recommend offering **Exclusive Discount Alerts** to help them find the best deals and encourage more frequent travel.

![Screenshot 2024-09-04 at 20 49 13](https://github.com/user-attachments/assets/2250ad67-35cf-4ef4-9001-54cecce8d57c)

**Family Adventurers** journey occasionally (average trips: 1.66), often with children (average of children: 37%) and prioritize flexibility due to unpredictable schedules (cancellation rate: 39%). They value destinations that offer good family value (hotel and flight discounts: 46%). We recommend offering an **Interest-Free Installment Plan** to help manage costs by spreading payments over time.

**Exploring Empty-Nesters** travel moderately (average trips: 3.0), often with a partner (46% married), and seek well-rounded experiences (average hotel stays: 2.77, flights: 2.67). They value comfort, relaxation, and destinations that offer both adventure and leisure. We recommend providing **One Free Hotel Night with a Flight** to reward their desire for a balanced, value-driven journey.

## **RECOMMENDATIONS**

**A/B Testing:**
* Divide customer segments randomly into control and test groups.
* Offer new loyalty perks to the test group and measure key metrics like trip completion, retention, and engagement.

**Metrics Analysis:**
* Use statistical tests (e.g., t-test, chi-squared) to determine if the perk has a significant impact on customer behavior.
* Focus on metrics such as booking frequency, retention, and cancellation rates.

**Supervised Machine Learning:**
* Once perks prove effective, implement supervised learning models (e.g., logistic regression, random forests) to automate perk assignment.
* Use customer attributes and behavior to predict which perks will drive engagement and optimize retention.

**Continuous Improvement:**
* Continuously feed data from future tests into the model to refine and enhance its predictions for better targeting of loyalty perks.

## Project Summary
Watch my video presentation of this project [TravelTideVideo](https://drive.google.com/file/d/1vPnWSH48qexMkZ8WJolIr_0U-3qQHMkL/view?usp=sharing).

View the project presentation [TravelTidePresentation](https://docs.google.com/presentation/d/1r5Z-1vtB5iVaZ9Z3DLQo-hoEuKcA2zQq8Xbs2Svcv0A/edit?usp=sharing).
