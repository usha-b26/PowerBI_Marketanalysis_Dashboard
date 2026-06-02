📊 Project Overview
This project provides a data-driven analysis of global marketing efforts, evaluating the performance of various campaign types (Influencer Marketing, Social Media, TV, etc.) across multiple regions and industries. The goal is to identify high-performing channels and provide actionable insights to improve the current Average ROI.

🛠️ Tools Used
Power BI: Data visualization, DAX measures, and interactive dashboarding.

Excel/CSV: Data cleaning and structured dataset management.

<img width="2345" height="1345" alt="Dashboard" src="https://github.com/user-attachments/assets/f841f5e8-00ca-4dd7-bf79-c41008446a65" />

# Market Analysis & Campaign Performance Dashboard

A SQL-based data analytics project designed to track, aggregate, and evaluate multi-channel marketing campaigns across various global regions and industry verticals.

## Project Overview

This repository contains the database schema and analytical queries required to measure marketing efficiency. The dataset tracks core digital marketing metrics—including ad spend, impressions, clicks, conversions, and revenue—to calculate key performance indicators (KPIs) like Click-Through Rate (CTR), Conversion Rate (CR), and Return on Investment (ROI).

## Database Setup

The project uses a MySQL database named `market_analysis`. Follow the instructions below to create the schema and import your dataset.

### Prerequisites
* MySQL Server (v8.0+ recommended) installed and running locally or remotely.
* Command Line Interface (CLI), Command Prompt, or Git Bash.

### Setup Instructions

1. **Log into your MySQL server:**
```bash
   mysql -u root -p
2.Create the target database:
Run the following commands inside the MySQL shell to initialize the database:
```bash
   CREATE DATABASE market_analysis;
   EXIT;
Import the schema and data:
Navigate to the directory where your .sql backup file is saved and execute the import command:
```bash
       mysql -u root -p market_analysis < market_analysis.sql
