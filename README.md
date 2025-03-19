

# **Market Strategy Analysis (ROI) Project**

---

## **Project Overview**
This project analyzes the impact of various marketing strategies and sales visits on sales performance (Amount Collected) across different client types. The goal is to identify the most effective strategies for maximizing ROI and provide actionable recommendations for the marketing team.

---

## **Project Structure**
The project is organized into the following sections:

1. **Introduction**: Overview of the project objectives and key questions.
2. **Data Loading and Quality**: Loading the dataset and ensuring data quality.
3. **Exploratory Data Analysis (EDA)**: Exploring the data and performing statistical tests to answer key questions.
4. **Statistical Analysis**: Using correlation and regression to quantify the impact of strategies.
5. **Final Recommendations**: Summarizing findings and providing actionable insights.

---

## **Key Questions Addressed**
1. What is the impact of each marketing strategy and sales visit on Sales (Amount Collected)?
2. Is the same strategy valid for all the different client types?

---

## **Data Description**
The dataset contains the following key variables:
- **Client Type**: Type of client (e.g., Large Facility, Medium Facility, Small Facility, Private Facility).
- **Number of Customers**: Number of customers in the account.
- **Monthly Target**: Monthly sales target for the account.
- **Amount Collected**: Total sales amount collected.
- **Unit Sold**: Number of units sold.
- **Campaigns**: Marketing campaigns (Email, Flyer, Phone).
- **Sales Contacts**: Sales visits (Sales_Contact_1 to Sales_Contact_5).
- **Number of Competition**: Number of competitors in the market.
- **Calendar_Month** and **Calendar_Year**: Time-related variables.

---

## **Results and Outputs**
- **Correlation Matrix**: Visualizes relationships between variables.
- **Regression Summary**: Provides coefficients and statistical significance of each strategy.
- **ROI Summary**: Highlights the most effective strategies for each client type.

## **Recommendation**
- Prioritize Campaign_Flyer and Sales_Contact_2 for most client types.

- Tailor strategies based on client type (e.g., focus on Sales_Contact_4 for Large Facilities).

- Discontinue or refine low-ROI strategies like Campaign_Phone and Campaign_Email.

- Address competitive markets by adopting differentiated strategies.
