# Portfolio: Vincent Balalian

Welcome to my Github! I'm Vincent, a junior data engineer based in Los Angeles. I'm passionate about learning and professional growth. My goal is to effectively utilize the tools in the modern data stack to apply data theory concepts and best practices through the various stages of ELT/ETL.

## Overview

These repositories are a collection of my data projects showcasing my skills in data cleaning, processing, visualization, orchestration, and more, using various tools and technologies such as Python, SQL, and more.

### Projects

#### [roman_coins_data_pipeline](https://github.com/vbalalian/roman_coins_data_pipeline)

End-to-end data pipeline project with a simple, learning-based scope, focused on the Extraction, Loading, and Transformation of data on coins minted by the ancient Roman Empire. The project currently consists of a [web scraper](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/web_scraping/web_scraper.py) that scrapes and parses data from wildwinds.com, then loads the data into a PostGreSQL server; an [API](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/api/main.py) that serves the dataset; a [custom Airbyte connector](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/custom-airbyte-connector/source_roman_coin_api/source.py), and [configuration script](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/airbyte-api-minio-connection/airbyte_connection_config.py) that sets up an Airbyte connection between the API and a [configured](https://github.com/vbalalian/roman_coins_data_pipeline/blob/c78bec8854deae898e19177d0f8e019241ee4b15/compose.yaml#L53) [MinIO](https://github.com/vbalalian/roman_coins_data_pipeline/blob/c78bec8854deae898e19177d0f8e019241ee4b15/compose.yaml#L42) bucket, with scheduled syncs orchestrated by [Dagster](https://github.com/vbalalian/roman_coins_data_pipeline/blob/master/orchestration/orchestration/__init__.py).

#### [Cyclistic_case_study](https://github.com/vbalalian/Cyclistic_case_study)

An R-based case study analyzing ride-sharing data using R's impressive suite of data processing and visualization tools to uncover insights and trends in bike-sharing service usage, in order to help the marketing team develop a new strategy to target casual riders for conversion to annual members. 

#### [Cointoss](https://github.com/vbalalian/cointoss)

A simple cointoss game using the tkinter python module for a graphical UI, demonstrating simple object-oriented programming concepts.

## Connect with Me

* LinkedIn: [Vincent Balalian](https://www.linkedin.com/in/vincent-balalian/)
* Email: vbalalian@gmail.com
