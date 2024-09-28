## Overview

These repositories are a collection of my data projects showcasing my skills in data analytics and engineering.

### Projects

#### [roman_coins_data_pipeline](https://github.com/vbalalian/roman_coins_data_pipeline)

ELT pipeline that extracts, loads, and transforms data on coins minted by the ancient Roman Empire.
- [web scraper](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/web_scraping/web_scraper.py) scrapes and parses data from wildwinds.com, then loads the data into a PostGreSQL server
- [API](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/api/main.py) serves the dataset
- [custom Airbyte connector](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/extract-load-transform/custom-airbyte-connector/source_roman_coin_api/source.py), and [configuration script](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/extract-load-transform/airbyte-api-minio-connection/airbyte_connection_config.py) set up an Airbyte connection between the API and a [configured](https://github.com/vbalalian/roman_coins_data_pipeline/blob/c78bec8854deae898e19177d0f8e019241ee4b15/compose.yaml#L53) [MinIO](https://github.com/vbalalian/roman_coins_data_pipeline/blob/c78bec8854deae898e19177d0f8e019241ee4b15/compose.yaml#L42) bucket
- [Dagster](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/extract-load-transform/orchestration/orchestration/__init__.py) orchestrates data sync, loading into DuckDB, and dbt modeling.

#### [Cyclistic_case_study](https://github.com/vbalalian/Cyclistic_case_study)

An R-based case study analyzing ride-sharing data using R's impressive suite of data processing and visualization tools to uncover insights and trends in bike-sharing service usage, in order to help the marketing team develop a new strategy to target casual riders for conversion to annual members. 

## Connect with Me

* LinkedIn: [Vincent Balalian](https://www.linkedin.com/in/vincent-balalian/)
* Email: vbalalian@gmail.com
