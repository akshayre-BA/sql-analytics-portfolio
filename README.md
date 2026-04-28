# SQL Business Analysis Project

## Overview
This project demonstrates the use of SQL to analyse customer complaint data and generate actionable business insights.

## Key Analysis
- Complaint trends by category
- Average resolution time
- Identification of open issues

## Sample Queries
```sql
SELECT complaint_type, COUNT(*) 
FROM customer_data
GROUP BY complaint_type;
