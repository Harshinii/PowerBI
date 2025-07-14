# Customer Satisfaction and Loyalty Analytics Challenge

As a data analyst at OmniRetail, a U.S. retail chain selling electronics and smart home products through both online and physical stores, help them improve customer satisfaction and retention. The company has collected feedback throughout 2024.
The customer satisfaction dataset provided combines satisfaction scores, purchasing behavior, demographics, support history, and location data.

## Mission
The goal was to create an analytical report that identifies the key factors influencing customer satisfaction and loyalty across different regions, customer demographics, and support experiences.

## Dataset Overview
| Column Name	| Description |
| ----------- | ----------- |
| Customer_ID |	Unique customer identifier (for internal use only) |
| Group	      | Customer classification: A, B, or C • Group A: High-frequency shoppers • Group B: Moderate-frequency • Group C: New or low-frequency |
| Satisfaction_Score | Customer’s rating of their experience (1 = very poor, 10 = excellent) |
| Age and Gender | Demographic attributes |
| Location | City and State (e.g., Austin.TX), with Latitude and Longitude for geographic mapping |
| Purchase_History | Indicates if the customer has made purchases (Yes/No) |
| Support_Contacted	| Whether the customer interacted with support |
| Loyalty_Level | OmniRetail’s internal rating: Low / Medium / High loyalty |
| Satisfaction_Factor	| The main reason influencing the satisfaction score (e.g., Price, Product Variety, Packaging) |

## Dashboard
Screenshots from the visualisation on PowerBI

<img width="1078" height="626" alt="image" src="https://github.com/user-attachments/assets/fe57633a-038c-4abc-85c3-87e87a6b81a5" />

<img width="1075" height="625" alt="image" src="https://github.com/user-attachments/assets/2a52910d-190e-4896-932b-07a3618619f6" />

<img width="1073" height="626" alt="image" src="https://github.com/user-attachments/assets/cffa09ae-5a52-4e9c-992e-630a0adc325f" />

## Insights
1. The main factors contributing to high scores are Product Quality, Packaging and Product Variety
2. Phoenix, Arizona is the most satisfied city
3. The net promotor score is very low at -41%
4. Customers who contact support versus those that do not contact support do not show any significant changes in their satisfaction scores
5. Women prefer Features more whereas men prefer Product Quality
6. Distribution of satisfaction scores against the loyalty levels indicates that high loyalty customers exhibit a broader upper range while low and medium loyalty customers are almost equally distributed in the upper and lower ranges.
7. High Loyalty Customers
Strengths : Brand Reputation, Product Quality, Packaging
Areas to Improve : Features, Ease of Use
8. Low Loyalty Customers
Strengths : Price, Product Quality, Customer Service
Aread to Improve : Brand Reputation, Ease of Use, Support Availability
9. Medium Loyalty Customers
General Trend : More balanced but lower satisfaction across all factors
Top Factors : Packaging, Delivery Speed
Areas to Improve : Features, Ease of Use, Price

## Recommendations
1. In order to improve NPS, focus on Ease of Use, Features and Price as these are the factors that have the least satisfaction scores across the board
2. San Antonio needs to be investigated as it has the least promotors
3. This analysis highlights opportunities to tailor strategies across loyalty segments, whether it's refining the product experience for loyal users or enhancing value perception for medium-tier customers.

## Assumption and Anomalies
1. Data anomaly: 21 customers with no purchase history are grouped as A - High frequency shoppers and 30 customers with no purchase history are grouped as B - Moderate frequency shoppers



