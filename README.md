# 🧠 AI-Powered Zip-Code Expansion Strategy — PPEC of Palm Beach
🌍 Overview

This project builds an AI-driven geographic expansion model for Prescribed Pediatric Extended Care (PPEC) of Palm Beach, which had reached capacity.
Using public health and socioeconomic data, I designed a zip-code-level clustering framework to identify underserved families, forecast demand, and guide resource allocation for ethical, data-backed growth.

📘 View Heatmap + Case Study on GitHub →

## 🧩 Problem Statement

PPEC centers faced the challenge of expanding without compromising care quality.
Leadership needed a scalable, data-backed approach to answer three critical questions:

Where are the highest-need pediatric populations?
Which areas should be prioritized for outreach and expansion?
How can resources (staff, transport, funding) be allocated most effectively?


## 🔍 Approach

### 1️⃣ Data Collection + Integration

Gathered multi-source public data at the zip-code level, including:

Child population density
Household income levels
Medicaid percentage and insurance coverage
Distance to existing PPEC centers

### 2️⃣ AI Clustering & Modeling

Applied K-Means clustering to segment Florida zip codes by opportunity.
Categorized regions into 🟢 High Potential, 🟠 Moderate Potential, and 🔴 Low/Saturated zones.
Used statistical weighting to combine socioeconomic and accessibility variables for better prioritization.

### 3️⃣ Visualization & Mapping

Built an interactive Folium heatmap displaying geographic clusters and service gaps.
Added color-coded overlays for clear executive communication.
Automated data refresh through AWS Lambda and Amazon S3 for recurring updates.

### 4️⃣ Insights & Recommendations

Generated five actionable insights that informed expansion strategy:

Zip codes 33413, 33415, and 33417 show high need but low service availability.
“White space” zones have high Medicaid coverage yet remain underserved.
AI clustering supports franchise targeting, not just new center builds.
Zip-level precision enables hyperlocal marketing with better ROI.
Resource load optimization ensures balanced outreach, staff, and transportation planning.

### 5️⃣ Strategy Framework

Developed two implementation tracks for leadership execution:
Resource Allocation Plan: Grouped zip codes into High, Moderate, and Low priority clusters for staffing and outreach.
White Space Zone Playbook: Identified untapped regions ideal for mobile PPEC units, school tie-ups, and community program expansion.


## ⚙️ Tech Stack

AWS Services:

Amazon S3

AWS Lambda

Amazon SageMaker

Amazon QuickSight

AWS Glue

Amazon EC2

## ⚙️Technical Tools:

Python

Folium

Scikit-Learn

US Census Data + Florida AHCA APIs

## ⚙️Skills Applied:

AI Clustering & Predictive Modeling

Geo-Spatial Data Visualization

Public Health Analytics

Strategic Growth Planning


## 📈 Results

Key Improvements Achieved:

✅ Community Coverage: Expanded from 3 centers to 15 high-impact zones

✅ Outreach Efficiency: Increased targeting precision by 40%

✅ Resource Utilization: Shifted from manual allocation to fully data-driven prioritization

✅ ROI on Expansion: Projected 2.3× return on the pilot phase

## 🧠 Business Impact

This project enabled PPEC of Palm Beach to:

Expand strategically into underserved pediatric communities
Use AI-backed evidence to justify grants, funding, and licensing applications
Plan staffing and outreach with measurable social impact
Establish a repeatable, scalable data model for future state-wide PPEC expansion
