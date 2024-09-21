# AkasaAir Data Engineering & Analytics Task

## Description
This project is a data engineering and analytics task based on aviation data. The task focuses on cleaning, normalizing, and analyzing flight data to derive insights regarding delays, airlines, and other relevant trends. 

## Objective
- The objective of this task is to:
- Clean and normalize flight data.
- Analyze delays and trends in the dataset.
- Provide recommendations to improve airline punctuality based on the findings.

## Setup
To run this project locally, follow these steps:

# Prerequisites
Python 3.x installed.

# Required Python libraries:
pandas
numpy
matplotlib
seaborn
sqlite3

# Installation
1. Clone the repository:
      git clone https://github.com/yourusername/akasa-air-data-task.git
      cd akasa-air-data-task
2. Install the necessary libraries:
      pip install -r requirements.txt
3. Place the dataset (aviation_data.csv) in the project directory.

## Data Cleaning
The cleaning process addresses the following:
- Inconsistent date and time formats.
- Missing values in the DelayMinutes column, which are filled with the mean value.
- Duplicate entries removed.
- Invalid time entries corrected.

## Data Analysis
After cleaning, the analysis focuses on:
- Delay distributions: Understanding which flights are delayed the most and when.
- Airline performance: Calculating average delay per airline.
- Delay trends: Investigating if certain departure times are more prone to delays.

## Optional: Database Storage
The cleaned and normalized data can be stored in an SQLite database for further querying.

## Testing the Pipeline
The pipeline is tested at each stage to ensure correctness:
- Data loaded successfully.
- Cleaning steps (missing values, format changes) are correctly applied.
- Normalization and calculations (flight duration) are validated.
- Data written to the database is correct.

## Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## Contact
For any questions or feedback, please reach out to:
  Name: Dnyaneshwari Pramod Nemade
  Email: dnyaneshwarinemade02@gmail.com
