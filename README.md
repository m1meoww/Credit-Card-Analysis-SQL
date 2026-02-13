# Credit Card Transactions Analysis (SQL)

## Project Overview
This project involves a comprehensive analysis of credit card transaction data to uncover patterns in consumer behavior, city-wise spending, and card type performance. The analysis is performed using advanced SQL techniques to solve complex business questions.

## Data Schema
The dataset `credit_card_transcations` includes the following attributes:
- `transaction_id`: Unique identifier for each transaction.
- `city`: The city where the transaction occurred.
- `transaction_date`: Date of the transaction.
- `card_type`: Type of card used (Gold, Platinum, etc.).
- `exp_type`: Category of expense (Food, Entertainment, etc.).
- `gender`: Gender of the cardholder.
- `amount`: Transaction value.

## Key Business Questions Addressed
1. **Top 5 Cities by Spend:** Calculated total spend per city and its percentage share of global spend.
2. **Peak Months:** Identified the highest spending month for every card type.
3. **Milestone Tracking:** Found the exact transaction where each card type crossed $1,000,000 in cumulative spend.
4. **Gender Insights:** Analyzed percentage contribution of female spenders across expense types.
5. **Growth Metrics:** Evaluated Month-over-Month (MoM) growth for card/expense combinations.
6. **Time-Based Trends:** Analyzed weekend spending ratios and transaction frequency.

## Tech Stack
- **Database:** SQL Server (T-SQL)
- **Concepts:** CTEs, Window Functions (RANK, DENSE_RANK, LAG), Aggregations, Date Functions.
