🧠 AI-Powered Zip-Code Expansion Strategy — PPEC of Palm Beach
🌍 Overview

This project builds an AI-driven geographic expansion model for Prescribed Pediatric Extended Care (PPEC) of Palm Beach, which had reached capacity.
Using public-health and socioeconomic data, I designed a zip-code-level clustering framework to identify underserved families, forecast demand, and guide resource allocation for ethical, data-backed growth.

📘 View Heatmap + Case Study on GitHub →

🧩 Problem Statement

PPEC centers faced the challenge of expanding without compromising care quality.
Leadership needed a scalable, data-backed approach to answer three core questions:

Where are the highest-need pediatric populations?

Which areas should be prioritized for outreach and facility expansion?

How can resources (staff, transport, funding) be allocated most effectively?

🔍 Approach
 1> Data Collection + Integration

Gathered multi-source public data at the zip-code level, including:

Child population density

Household income levels

Medicaid % and insurance coverage

Distance to existing PPEC centers

2> AI Clustering & Modeling

Applied K-Means clustering to segment Florida zip codes by opportunity.

Categorized zones into 🟢 High, 🟠 Moderate, and 🔴 Low potential.

Used statistical weighting to combine socioeconomic and access variables.

3> Visualization & Mapping

Built an interactive Folium heatmap to display geographic clusters.

Integrated color-coded opportunity overlays for executive review.

Automated data refresh through AWS Lambda + S3 pipelines.

4> Insights & Recommendations

>>> Generated five actionable insights:

>Zip codes 33413, 33415 & 33417 = high potential, low service.

>“White space” zones have high Medicaid coverage but no centers.

>AI clustering supports franchise targeting, not just new builds.

>Zip-level precision enables hyperlocal marketing ROI.

>Resource load can be optimized by zone priority.

5> Strategy Framework

Developed two implementation tracks:

Resource Allocation Plan: Grouped zip codes into High/Moderate/Low priority for staffing & outreach.

White Space Zone Playbook: Identified untapped regions ideal for mobile PPEC units and school partnerships.


⚙️ Tech Stack

AWS Services:

Amazon S3

AWS Lambda

Amazon SageMaker

Amazon QuickSight

AWS Glue

Amazon EC2

⚙️ Technical Tools:

Python

Folium

Scikit-Learn

US Census Data + Florida AHCA APIs

⚙️ Skills Applied:

AI Clustering & Predictive Modeling

Geo-Spatial Data Visualization

Public Health Analytics

Strategic Growth Planning

📊 Results
Metric	Before	After (AI Model)
Community Coverage	Limited to 3 Centers	Identified 15 new high-impact zones
Outreach Efficiency	Manual Targeting	+40 % target precision
Resource Utilization	Generalized Allocation	Data-driven prioritization
ROI on Expansion	Unknown	Projected 2.3× return on pilot phase
🧠 Business Impact

The project enabled PPEC of Palm Beach to:

Expand strategically into underserved communities
Use AI evidence to justify grant & licensing decisions
Plan outreach and staffing with maximum social impact
Establish a repeatable data model for future PPEC locations
