# NYC Taxi Data Engineering Project

This project aims to design and implement a scalable data pipeline for processing and analyzing the New York Taxi Trip data. It includes automated data extraction, transformation, loading into a database, and performing data analysis to derive insights.
## Environment Setup

### Prerequisites

Before starting, ensure you have the following installed:
- Python 3.x
- AWS CLI (optional, for AWS setup)
- AWS SDKs (boto3 for Python, if using AWS services)
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kannada5/nyc-data-pipeline.git
   cd nyc-data-pipeline

   
#### Data Analysis

-- Example SQL queries for analysis
SELECT strftime('%H', tpep_pickup_datetime) AS pickup_hour, COUNT(*) AS trip_count
FROM nyc_taxi_trips
GROUP BY pickup_hour
ORDER BY trip_count DESC;


### Querying Data

- Use Amazon Athena to run SQL queries on data stored in S3 buckets.
- Example query to find peak hours for taxi usage.

### Visualizing Data

- Use Python libraries (Matplotlib, Seaborn) to create visualizations.
- Example: Plotting trip counts by hour using Matplotlib.
## Final Notes

- For questions or issues, contact gowthamacchuacharya@gmail.com
