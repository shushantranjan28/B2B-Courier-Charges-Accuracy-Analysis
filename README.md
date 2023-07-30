# B2B-Courier-Charges-Accuracy-Analysis

This repository contains the code and data for the B2B-Courier-Charges-Accuracy-Analysis project. The project involves analyzing the accuracy of courier charges applied by ABC Couriers for B2B shipments. The goal is to identify instances where the charges were over or undercharged compared to the charges calculated as per the company's internal system.

## Data Sources

- **Order Report**: Contains information about B2B orders, SKUs, and quantities.
- **SKU Master**: Provides SKU details, including weight in grams.
- **Pincode Mapping**: Maps warehouse and customer pincodes to delivery zones.
- **Courier Invoice**: Includes courier charges applied for each order.
- **Courier Company Rates**: Holds rates for different weight slabs and zones.

## Project Steps

1. **Data Preprocessing**: Clean and merge the datasets to create a consolidated view.
2. **Weight Slab Calculation**: Derive weight slabs for each order based on the SKU weight.
3. **Expected Charge Calculation**: Calculate the expected charges as per ABC's internal rates.
4. **Difference Calculation**: Compare the expected charges with the charges applied by the courier company.
5. **Summary Statistics**: Summarize the findings to understand overcharged, undercharged, and correctly charged orders.

## Project Outcomes

By conducting this analysis, valuable insights were provided to the finance and logistics teams at ABC Couriers. The information will help optimize the courier charges process, ensure accurate billing for clients, and potentially lead to cost savings and improved customer satisfaction.

## Tools and Skills Used

- Python
- Pandas
- Data Cleaning and Preprocessing
- Data Analysis and Visualization
- Matplotlib
