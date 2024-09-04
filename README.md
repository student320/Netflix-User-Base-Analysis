# Netflix User Analysis - Project Overview

## Project Goal
This project aims to analyze the behavior and demographics of Netflix users based on a sample dataset. The analysis focuses on identifying key metrics and providing recommendations to achieve three primary objectives: 1) improve customer retention, 2) increase the number of new subscribers, and 3) increase overall revenue generation.

## Company Background
Netflix is a leading streaming service provider offering a wide variety of television shows, movies, and more across a vast range of genres and languages. With millions of subscribers worldwide, Netflix’s business model relies on different subscription tiers—Basic, Standard, and Premium—each offering varying levels of service.

## Dataset Structure
The dataset used in this analysis consists of the following information:

* User ID: Unique identifier for each user
*Subscription Type: Subscription type (Basic, Standard, or Premium)
* Monthly Revenue: Revenue generated per user per month
* Join Date: Date user joined	
* Last Payment Date: Date user made last payment	
* Country: Country of user
* Age: Age of user
* Gender: Gender of user
* Device: Device type (Tablet, Smartphone, Laptop, Smart TV)

## Insights Summary
In order to evaluate customer performance, we focused on the following key metrics:

- **Revenue**: Revenue generated.
- **Customer Life Time Value (CLTV):** Total revenue generated for the entire duration of a users subscriptiuon.
- **Subscription Length:** Number of months a users stays subscribed. Calculated as number of months multiplied by duration of subscription.
- **Chrun Rate:** The rate at which users disconinue using Netflix.

### Revenue:
- The sample data indicates a **total revenue** of $349.95K USD.
- The **Basic tier** contributed the most to revenue, accounting for approximately 39.96% of the total.
- The **Standard tier** followed with 30.71%, and the **Premium tier** generated the remaining 29%.
- **Revenue distribution across devices** is nearly equal, with each device type contributing close to 25%.


### CLTV:
- The United States has the highest **total CLTV** at $63,336 but ranks 5th in **average CLTV per user** at $140.
- The United Kingdom leads in **average CLTV per user**, reaching $145, compared to the overall average of $139.98 across all users.
- Mexico has the **lowest total CLTV** at $25,218, primarily due to a low subscriber count.
- Canada shows the **lowest average CLTV per user** at $137.49, driven by shorter user duration and a lower percentage of upper-tier subscriptions.

### Average Subscription Duration
- The United Kingdom has the **longest average subscription duration per user** at 11.54 months, while Italy records the shortest duration at 10.83 months.
- The **overall average subscription duration** across all users is 11.59 months.
- **Average subscription duration by device:**
  - Tablet users: 11.28 months
  - Smartphone users: 11.22 months
  - Laptop and smart TV users: 11.14 months
- **Average subscription duration by plan:**
  - Standard plan: 11.45 months
  - Basic plan: 11.07 months
  - Premium plan: 10.93 months (shortest average duration)


### Customer Churn Rate
- **Customer retention rate** is 8.24%, resulting in a **customer churn rate** of 91.76%.
- Among all countries, the **United States** has the lowest churn rate at 90.69%, while **Italy** has the highest at 93.44%.
- **Churn rate by subscription type**:
  - Standard plan: 90.63% (lowest churn rate)
  - Premium plan: 92.50% (highest churn rate)


## Recommendations
### Increase Revenue per User by Upselling to Higher Tiers:
- **Target Countries with High Proportion of Basic Subscription Type:** Focus upselling efforts on Germany, Italy, and Brazil due to their higher Upselling opportunities.
- **Leverage CLTV Data:** Prioritize countries like the UK, France, and Australia with the highest CLTV per user, while investigating why these users upgrade more frequently or stay subscribed longer.
- **Introduce Limited-Time Offers:** Offer trial periods for higher tiers to incentivize upgrades.
- **Early Access Incentives:** Provide early access to premium content to encourage users to experience and upgrade to higher tiers.

### Increase Customer Retention:
- **Annual Subscription Upgrade:** Offer a free tier upgrade for users who maintain a full year of continuous subscription.
- **Churn Analysis:** Investigate reasons for churn with customer surveys or cohort analysis and address their pain points, focusing on high-churn countries like Italy and Germany, and adjust retention strategies accordingly.

### Increase the Number of Subscribers:
- **Incentivize Referrals:** Launch a referral program where current subscribers receive discounts or perks for bringing new users to the platform.
- **Incentivise new signups:** provide discounts and perks for limited time to new subscribers.
- **Marketing Focus:** Increase efforts on social media and SEO in underperforming markets in terms of total users like the UK, Italy, and Mexico.

## Dashboard [Link to Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDNmZmZkNzQtNTI4Zi00OGI0LWJkNDUtMDRiMmMzN2NkYWUzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
![image](https://github.com/user-attachments/assets/f839ec7a-71e9-4d49-94dc-8d52d23eed40)

![image](https://github.com/user-attachments/assets/b3a6ad1e-5160-48f2-90b9-650f1dadd720)

## Presentation Sample [Link to Full Presentation](https://docs.google.com/presentation/d/1m2yux7EM2ghopHhGQKm7nsPT79QW-50hOZXslKWmNbA/edit#slide=id.p)
![image](https://github.com/user-attachments/assets/c4e538ee-2bec-4ab1-a773-3f260162f2ae)







