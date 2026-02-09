# Retail Sales Performance Analysis – Power BI

## Project Overview
This project analyzes retail transaction data to evaluate sales performance, identify profitable and low-margin product categories, and support business decisions. An interactive Power BI dashboard was created to transform raw sales data into actionable insights.

---

## Problem Statement
A retail business wants to:
- Understand overall sales performance
- Identify profitable and non-profitable product categories
- Compare performance across regions
- Support decisions for promotions and inventory planning

The objective is to build a single Power BI dashboard that cleans, analyzes, and visualizes the data for decision-making.

---

## Project Objectives
- Clean and validate raw sales data
- Perform univariate analysis on Sales and Profit
- Analyze category-wise and regional performance
- Build a star schema data model
- Create DAX measures for key metrics
- Design an interactive dashboard
- Provide business recommendations

---

## Dataset Description
The dataset contains **1,000 retail transactions** with the following fields:

### Sales Table (Fact Table)
- Transaction ID
- Date
- Month
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount (Sales)
- Profit (calculated)
- Region (generated for analysis)

---

## Data Preparation
The following steps were performed:

- Checked for missing values
- Removed duplicate transactions
- Verified data types
- Created a Profit column
- Generated a Region column
- Created bins for Sales and Profit distribution analysis

---

## Data Model
A **Star Schema** was implemented:

