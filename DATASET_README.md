# 🛒 E-Commerce Customer Behavior and Sales Dataset

## 📊 Dataset Overview

This comprehensive dataset contains **5,000 e-commerce transactions** from a Turkish online retail platform, spanning from January 2023 to March 2024. The dataset provides detailed insights into customer demographics, purchasing behavior, product preferences, and engagement metrics.

## 🎯 Use Cases

This dataset is perfect for:
- **Customer Segmentation Analysis**: Identify distinct customer groups based on behavior
- **Sales Forecasting**: Predict future sales trends and patterns
- **Recommendation Systems**: Build product recommendation engines
- **Customer Lifetime Value (CLV) Prediction**: Estimate customer value
- **Churn Analysis**: Identify customers at risk of leaving
- **Marketing Campaign Optimization**: Target customers effectively
- **Price Optimization**: Analyze price sensitivity across categories
- **Delivery Performance Analysis**: Optimize logistics and shipping

## 📁 Dataset Structure

The dataset contains **18 columns** with the following features:

### Order Information
- **Order_ID**: Unique identifier for each order (ORD_XXXXXX format)
- **Date**: Transaction date (2023-01-01 to 2024-03-26)

### Customer Demographics
- **Customer_ID**: Unique customer identifier (CUST_XXXXX format)
- **Age**: Customer age (18-75 years)
- **Gender**: Customer gender (Male, Female, Other)
- **City**: Customer city (10 major Turkish cities)

### Product Information
- **Product_Category**: 8 categories (Electronics, Fashion, Home & Garden, Sports, Books, Beauty, Toys, Food)
- **Unit_Price**: Price per unit (in TRY/Turkish Lira)
- **Quantity**: Number of units purchased (1-5)

### Transaction Details
- **Discount_Amount**: Discount applied (if any)
- **Total_Amount**: Final transaction amount after discount
- **Payment_Method**: Payment method used (5 types)

### Customer Behavior Metrics
- **Device_Type**: Device used for purchase (Mobile, Desktop, Tablet)
- **Session_Duration_Minutes**: Time spent on website (1-120 minutes)
- **Pages_Viewed**: Number of pages viewed during session (1-50)
- **Is_Returning_Customer**: Whether customer has purchased before (True/False)

### Post-Purchase Metrics
- **Delivery_Time_Days**: Delivery duration (1-30 days)
- **Customer_Rating**: Customer satisfaction rating (1-5 stars)

## 📈 Key Statistics

- **Total Records**: 5,000 transactions
- **Date Range**: January 2023 - March 2024 (15 months)
- **Average Transaction Value**: ~450 TRY
- **Customer Satisfaction**: 3.9/5.0 average rating
- **Returning Customer Rate**: 60%
- **Mobile Usage**: 55% of transactions

## 🔍 Data Quality

- ✅ No missing values
- ✅ Consistent formatting across all fields
- ✅ Realistic data distributions
- ✅ Proper data types for all columns
- ✅ Logical relationships between features

## 💡 Sample Analysis Ideas

1. **Customer Segmentation with K-Means Clustering**
   - Segment customers based on spending, frequency, and recency
   
2. **Sales Trend Analysis**
   - Identify seasonal patterns and peak shopping periods
   
3. **Product Category Performance**
   - Compare revenue, ratings, and return rates across categories
   
4. **Device-Based Behavior Analysis**
   - Understand how device choice affects purchasing patterns
   
5. **Predictive Modeling**
   - Build models to predict customer ratings or purchase amounts
   
6. **City-Level Market Analysis**
   - Compare market performance across different cities

## 🛠️ Technical Details

- **File Format**: CSV (Comma-Separated Values)
- **Encoding**: UTF-8
- **File Size**: ~500 KB
- **Delimiter**: Comma (,)

## 📚 Column Descriptions

| Column Name | Data Type | Description | Example |
|------------|-----------|-------------|---------|
| Order_ID | String | Unique order identifier | ORD_001337 |
| Customer_ID | String | Unique customer identifier | CUST_01337 |
| Date | DateTime | Transaction date | 2023-06-15 |
| Age | Integer | Customer age | 35 |
| Gender | String | Customer gender | Female |
| City | String | Customer city | Istanbul |
| Product_Category | String | Product category | Electronics |
| Unit_Price | Float | Price per unit | 1299.99 |
| Quantity | Integer | Units purchased | 2 |
| Discount_Amount | Float | Discount applied | 129.99 |
| Total_Amount | Float | Final amount paid | 2469.99 |
| Payment_Method | String | Payment method | Credit Card |
| Device_Type | String | Device used | Mobile |
| Session_Duration_Minutes | Integer | Session time | 15 |
| Pages_Viewed | Integer | Pages viewed | 8 |
| Is_Returning_Customer | Boolean | Returning customer | True |
| Delivery_Time_Days | Integer | Delivery duration | 3 |
| Customer_Rating | Integer | Satisfaction rating | 5 |

## 🎓 Learning Outcomes

By working with this dataset, you can learn:
- Data cleaning and preprocessing techniques
- Exploratory Data Analysis (EDA) with Python/R
- Statistical analysis and hypothesis testing
- Machine learning model development
- Data visualization best practices
- Business intelligence and reporting

## 📝 Citation

If you use this dataset in your research or project, please cite:

```
E-Commerce Customer Behavior and Sales Dataset (2024)
Turkish Online Retail Platform Data (2023-2024)
Available on Kaggle
```

## ⚖️ License

This dataset is released under the **CC0: Public Domain** license. You are free to use it for any purpose.

## 🤝 Contribution

Found any issues or have suggestions? Feel free to provide feedback!

## 📞 Contact

For questions or collaborations, please reach out through Kaggle.

---

**Happy Analyzing! 🚀**

*Keywords: e-commerce, customer behavior, sales analysis, Turkish market, retail analytics, machine learning, data science, customer segmentation, predictive analytics*
