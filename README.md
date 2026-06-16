🧹 Data Cleaning & Preparation | DecodeLabs Internship

📊 Project Overview

Cleaned a raw e-commerce dataset (1,200 orders) by handling missing
values, removing duplicates, and standardizing formats — achieving
a 100% data quality score.

📁 Files in This Repository

FileDescription

Dataset_Cleaned_Project1.csv ---> Final cleaned dataset
CHANGE_LOG.txt ---> Documentation of every change made
PProject1Workspace.ipynb ---> Full Python/Pandas notebook

🎯 Goal

Clean a raw dataset by handling missing values, duplicates, and
incorrect data formats.

🔧 What Was Done

1️⃣ Phase 1: Strategic Imputation
Identified 309 missing CouponCode values
Filled with "NO_COUPON" (explicit, no data loss)


2️⃣Phase 2: Integrity Audit
Verified 100% unique OrderIDs
Removed any full-row duplicates
Result: 0 duplicate records


3️⃣Phase 3: Standardization
Converted all dates to ISO 8601 format (YYYY-MM-DD)
Applied Title Case + trimmed whitespace on text fields
Standardized prices to 2 decimal places
Recalculated 107 rows where TotalPrice ≠ Quantity × UnitPrice


🛑 Quality Verification Results

CheckResultDuplicate OrderIDs 0% ✅
Invalid Date Formats 0% ✅
Missing Values 0% ✅
Price Calculation Errors 0% ✅

🛠️ Tools Used
Python, Pandas, NumPy, Google Colab, Git

📚 Key Learnings
Strategic imputation vs. naive deletion
Importance of standardized formats for analysis
Professional documentation through Change Logs


