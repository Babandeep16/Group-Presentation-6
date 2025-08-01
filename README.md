#  Fashion Retail Analytics – Group Presentation 6

This project explores customer behavior, pricing strategies, and profitability patterns using real-world data from a global fashion retail business. It is part of our term project for the Applied AI & ML course.

##  Datasets Used

We used four datasets sourced from Kaggle and class files:

- `transactions.csv`: Contains 175,000 records of sales and return transactions.
- `products.csv`: Metadata for 17,000+ fashion products, including categories and production costs.
- `stores.csv`: Information about 35 store locations, staff size, and city/country data.
- `discounts.csv`: Historical promotional events categorized by subcategory and time period.

## Project Goals

- Merge multiple datasets to create enriched records for analysis.
- Identify correlations between price, discount, and profitability.
- Predict high-profit transactions using Logistic Regression.
- Model return likelihood using Probabilistic Reasoning (Naive Bayes).

##  Key Features Engineered

- `Profit` = Line Total – Production Cost  
- `High Profit` = Profit > Median  
- `Is Return` = Transaction Type == "Return"  
- `Discount Applied` = Binary flag from discount column  

##  Implemented Methods

- **Pearson Correlation Matrix** – Visualized linear relationships between pricing and profitability.
- **Logistic Classification** – Predicted high-profit transactions (Accuracy: ~83%).
- **Naive Bayes Classification** – Modeled return behavior (Recall: 1.00, Precision: low).
- **OOP Refactoring** – Code is modularized via `FashionRetailAnalyzer` class.

##  Results

- Unit Price and Line Total have strong positive correlation with Profit.
- Discount weakly reduces profitability — supporting our revised hypothesis.
- High profit predictions were reliable; return modeling may require more features.

##  Conclusion

The analysis supports the hypothesis that moderate discounts and low-cost products increase profitability. Our model provides retailers with data-driven insights into promotion planning, pricing, and operational optimization.

---

© 2025 | Team: Babandeep, Mandeep, Hasyashri | Conestoga College | Applied AI & ML
