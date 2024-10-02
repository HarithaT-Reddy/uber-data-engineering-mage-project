# Uber Data Analytics | Modern Data Engineering GCP Project

 ## Introduction
This project leverages Google Cloud Platform (GCP) to extract valuable insights from Uber data. We utilize Mage.ai to build a robust data pipeline that ingests data from Cloud Storage, transforms it in BigQuery, and prepares it for analysis. Finally, Looker Studio empowers us to visualize the transformed data, revealing hidden patterns and trends. This modern data engineering approach enables us to gain a deeper understanding of Uber's operations and make data-driven decisions.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. Programming Language -Python
2. Scripting Language-SQL
3. Google Cloud Platform
   - Bigquery
   - Cloud Storage
   - Looker Studio
   - Compute Instance
4. Mage.Ai(modern data pipeline tool)

**Modern Data Pipeline Tool:** https://www.mage.ai/
**Contribute to this project here:** https://github.com/mage-ai/mage-ai

## Dataset Used
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset used in the video - https://github.com/darshilparmar/uber-data-engineering-mage-project/blob/main/data/uber_data.csv

## More Info About Dataset
1. Original Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Data Model Image](data_model.jpeg)

## Scripts for project
1. [Extract Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Transform Python File](mage-files/transform.py)

## Complete Video Tutorial
Video Link - https://www.youtube.com/watch?v=WpQECq5Hx9g

