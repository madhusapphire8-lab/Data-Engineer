🚀 End-to-End Customer 360 View Ecommerce Project using Microsoft Fabric, OneLake & Power BI

📉 The Business Problem
The e-commerce company operated across multiple digital touchpoints:
• Website
• Mobile App
• Order Management System
• Payment Gateway
• Customer Support Platform
• Web Analytics Tools

🔺 Each system produced valuable data, but the information existed in isolated silos.
This created several business challenges:
• Leadership could not easily identify high-value customers
• Marketing teams struggled to segment customers for personalization
• Support agents lacked full customer history when responding to issues
• It was difficult to measure customer churn or loyalty
• Business teams could not see the complete lifecycle from browsing to purchase to support interaction

What the organization needed was a single, reliable Customer 360 view.

🎯 Project Objective
The goal of the project was to build a unified Customer 360 analytics platform using Microsoft Fabric.
The platform needed to:
✔ Integrate data from multiple operational systems
✔ Clean and standardize messy datasets
✔ Provide a single source of truth for customer analytics
✔ Enable leadership to monitor key customer KPIs
✔ Deliver interactive insights through Power BI dashboards

🔥 Microsoft Fabric made this possible by bringing data engineering, data storage, and analytics into one unified environment. 🔥 

🧩 Data Sources Integrated
The solution brought together multiple data sources:
Customer Profiles
Orders
Payments
Support Tickets 
Web & App Activity 

🏗 Architecture: Unified Data Platform with Microsoft Fabric
The platform was built using Microsoft Fabric Lakehouse architecture with the Medallion data model.

Bronze Layer – Raw Data
Data from multiple CSV sources was ingested using Fabric Data Pipelines and stored in the Lakehouse as raw Delta tables.

Silver Layer – Data Cleaning & Transformation
Using PySpark notebooks in Fabric, the data was cleaned and standardized.

Gold Layer – Analytics Model
The final layer created a business-friendly analytical model using a Star Schema.

📊Key KPIs included:
• Active Customers – customers with at least one transaction
• Average Order Value – average spend per order
• Repeat Customer % – customers with two or more purchases
• Open Support Tickets – unresolved complaints
• Churn Risk Customers – customers with past complaints and no recent orders
• Payment Mode Distribution – credit card vs UPI vs wallet usage
• Device Preference – web vs mobile engagement trends

💡 Business Impact
By implementing this unified data platform, the organization unlocked several business benefits.
Personalized Marketing
Improved Customer Support
Better Strategic Decisions
Full Customer Lifecycle Visibility
Customer Signup → Browsing Behavior → Purchase → Payment → Support Interaction 
