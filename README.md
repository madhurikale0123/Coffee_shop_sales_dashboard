# Coffee_shop_sales_dashboard

Project Overview - This project focuses on analyzing retail transaction data to discover trends, optimize inventory, and evaluate store performance. The dataset tracks individual sales transactions, product details, pricing, and time-based metrics across multiple retail locations.This project outlines the data structure, schema definitions, and analytical frameworks for a multi-location retail transaction dataset. The data captures granular, point-of-sale (POS) information alongside enriched time-based attributes. The primary objective of compiling this data is to evaluate store operational efficiency, perform advanced customer purchase behavior analysis, and optimize inventory supply chains.

Key Performance Indicators (KPIs) Matrix -
Total Revenue - Sum of Total Bill aggregated by store, category, or time window.
Average Transaction Value (ATV) -  Total Revenue divided by the distinct count of transaction_id.
Peak Foot Traffic Hours -  Identified by tracking distinct transaction volume frequencies across the Hour and Day Name matrix.
Product Popularity Rank - Volumetric sum of transaction_qty grouped by product_category and filtered down to product_detail.

Insights from this data
Prep-Work Planning - Analyzing Day Name against transaction_qty shows whether your customers change behaviors on weekends versus weekdays. Weekdays might see fast, single-item commuter orders, while weekends might bring slower, larger multi-item family orders that require more kitchen prep.

Hyper-Local Menu Tuning -  Cross-referencing store_location with product_category reveals what sells best where. A store near a university might sell massive volumes of cheap iced coffees, while a financial district location might dominate in high-margin premium espressos.

The Upsell Gap -  Calculating the average transaction_qty per transaction shows how often customers bundle items. If your average quantity is close to 1.0, it means people are buying a drink but skipping food—indicating a massive opportunity to introduce coffee-and-pastry combo discounts.
