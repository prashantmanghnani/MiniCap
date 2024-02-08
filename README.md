# Mini Capstone Project: Crime Data Analysis with MySQL and Python

## Introduction

This project involves the use of Python, specifically the PyMySQL library, to interact with a MySQL database for analyzing and gaining insights from crime data. The dataset encompasses a range of information including DR NO, Date Reported, Date Occurred, Area Name, Crime Code, Crime Code Description, Victim Age, Victim Sex, Premises Description, Status, Location, Latitude, and Longitude.

## Objectives

1. **Database Setup and Import**:
   - Create a MySQL database.
   - Load the provided crime dataset into the MySQL database.

2. **Database Connection**:
   - Use PyMySQL to establish a connection to the database in PyCharm or VS Code.
   - Verify the successful import of data.

3. **Data Exploration**:
   - Retrieve basic statistics on the dataset.
   - Identify the distinct crime codes and their descriptions.

4. **Temporal Analysis**:
   - Analyze the temporal aspects of the data.
   - Determine trends in crime occurrence over time.

5. **Spatial Analysis**:
   - Perform spatial analysis using geographical information (Latitude and Longitude).
   - Visualize crime hotspots on a map.

6. **Victim Demographics**:
   - Investigate the distribution of victim ages and genders.
   - Identify common premises descriptions where crimes occur.

7. **Status Analysis**:
   - Examine the status of reported crimes.
   - Classify crimes based on their current status.

## Questions for Analysis

- **Spatial Analysis**: Where are the geographical hotspots for reported crimes?
- **Victim Demographics**: 
  - What is the distribution of victim ages in reported crimes?
  - Is there a significant difference in crime rates between male and female victims?
- **Location Analysis**: Where do most crimes occur based on the "Location" column?
- **Crime Code Analysis**: What is the distribution of reported crimes based on Crime Code?

## Tools and Libraries

- Use PyCharm or Visual Studio Code for Python development.
- PyMySQL for interacting with the MySQL database.
- Matplotlib and Seaborn for data visualization.

## Deliverables

- Python scripts for database setup, data import, and data analysis.
- Visualizations and insights derived from the analysis.

## Setup Instructions

Ensure you have a running MySQL server for this project. Install the necessary libraries using:

```bash
pip install pymysql matplotlib seaborn
