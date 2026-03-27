Consumer Behavior and Revenue Analytics
End-to-End Data Pipeline: From Raw Transactions to Executive Insights

Business Impact
This project transformed 3,900 raw retail transactions into a strategic growth roadmap. The analysis identified a 73% subscription gap and established a data-backed framework to drive a projected 12-18% increase in annual revenue.

Tech Stack
Data Engineering: Python (Pandas, SQLAlchemy) for automated ETL and database synchronization.

Database: MS SQL Server for relational data storage and complex querying.

Analytics: Advanced SQL for demographic segmentation and revenue distribution.

Business Intelligence: Power BI for interactive executive-level dashboards.

Key Insights Uncovered
Revenue Dominance: Male customers account for 67% of total revenue ($157,890).

High-Value Demographic: The 'Young Adult' segment (ages 18-30) is the most profitable, contributing $62,143.

Conversion Opportunity: 73% of the customer base are currently non-subscribers, representing the largest area for growth.

Operational Quality: Identified specific product categories with ratings below 3.5 that require immediate vendor quality audits.

Project Structure
Plaintext
├── Scripts/
│   └── data_pipeline.py       # Clean ETL logic (No comments)
├── SQL/
│   └── revenue_analysis.sql   # Mission-critical business queries
├── Dashboard/
│   └── retail_analytics.pbix  # Interactive Power BI file
├── Docs/
│   ├── Presentation.pdf       # Executive summary presentation
│   └── Report_Final.pdf       # Full analytical documentation
├── requirements.txt           # Environment dependencies
└── README.md
Setup and Installation
Clone the Repository:
git clone https://github.com/arfaazpathan/customer-behaviour-analysis.git

Install Dependencies:
pip install -r requirements.txt

Execute Pipeline:
Run data_pipeline.py to process raw CSV data and sync with the local SQL Server instance.

Author
Arfaaz Pathan
Data Analyst | Python and SQL Specialist
[LinkedIn Profile] | [Portfolio Link]

Professional Note
Code Standard: All scripts follow clean code principles with self-documenting variables and zero unnecessary comments.

Security: Database credentials have been externalized; ensure local environment variables are configured before execution.
