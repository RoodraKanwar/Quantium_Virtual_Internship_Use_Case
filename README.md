# Quantium Retail Analytics: Chips Category Analysis
## Project Overview
This project involves analyzing transaction and customer data for a supermarket's chips category to understand customer purchasing behavior. The goal is to provide actionable insights that will inform the Category Manager's strategic decisions for the next half-year.

## Week 1

### 1. Data Cleaning & Validation:
- Examined transaction and customer data for inconsistencies, missing values, and outliers.
- Removed non-chip products (e.g., "Salsa") and corrected brand names (e.g., "Red" → "Red Rock Deli").
- Handled outliers (e.g., a single transaction with 200 units).
- Converted date formats and extracted pack sizes (grams) from product names.

### 2. Exploratory Data Analysis (EDA)
- Analyzed sales distribution by customer segments (LIFESTAGE, PREMIUM_CUSTOMER).
- Identified top-selling brands (Kettle, Doritos, Pringles) and pack sizes (175g most common).
- Discovered missing data for December 25, 2018 (likely due to store closures).

### 3. Customer Segmentation & Insights

- Highest Sales Contributors:
  - Budget: Older Families (8.7% of total sales).
  - Mainstream: Young Singles/Couples (8.2%) and Retirees (8.0%).

- Price Sensitivity:
  - Mainstream customers pay significantly more per unit than Premium/Budget shoppers (*p-value < 0.05*).

- Brand Affinity:
  - Mainstream Young Singles/Couples prefer Tyrrells, Twisties, and Doritos (20–23% higher affinity vs. other segments)

### 4. Strategic Recommendations

- Target Segments: Focus on Mainstream Young Singles/Couples (high spenders) and Budget Older Families (high volume).
- Product Strategy: Promote mid-sized packs (150–200g) and premium brands (Kettle, Doritos) to Mainstream shoppers.
- Promotions: Offer bundles or loyalty discounts for Budget families to increase basket size.
