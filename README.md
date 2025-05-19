# Hawaii Climate Analysis Project


## Project Summary

This project showcases end-to-end data analysis and web application development by analyzing historical climate data from Honolulu, Hawaii. It includes both a comprehensive data exploration process using Python and SQLAlchemy, and the creation of a Flask API to serve the analyzed data in an accessible format.

---

## Skills Demonstrated

- **Data Analysis**: Leveraging SQLAlchemy and Pandas for querying and exploring climate data
- **Data Visualization**: Plotting trends and distributions using Matplotlib
- **Database Interaction**: Reflecting and interacting with an SQLite database using SQLAlchemy ORM
- **API Development**: Building a RESTful Flask API with dynamic routing
- **Python Programming**: Combining Pandas, Flask, and SQL to build full-stack functionality

---

## Project Breakdown

### Part 1: Climate Data Analysis

Using SQLAlchemy and Pandas, this section focuses on exploring weather trends through the following steps:

- Establishing a connection to the SQLite database
- Reflecting existing database tables into Python classes
- Performing precipitation analysis:
  - Identifying the most recent date in the dataset
  - Retrieving the last 12 months of precipitation data
  - Loading the data into Pandas and generating visualizations
  - Calculating summary statistics

- Performing station analysis:
  - Counting the total number of stations
  - Identifying the most active weather stations
  - Analyzing temperature observations for the most active station
  - Creating a histogram of temperature frequency

---

### Part 2: Flask API Development

This section implements a Flask-based web API to serve climate data through multiple routes:

- `/` — Lists all available API routes
- `/api/v1.0/precipitation` — Returns precipitation data in JSON format
- `/api/v1.0/stations` — Lists weather stations as JSON
- `/api/v1.0/tobs` — Provides temperature data for the most active station
- `/api/v1.0/<start>` — Returns min, avg, and max temperature from the start date to the end of the dataset
- `/api/v1.0/<start>/<end>` — Returns min, avg, and max temperature between a given start and end date

---

## Tools & Technologies

- Python (Pandas, NumPy)
- SQLite (local climate database)
- SQLAlchemy (ORM for database reflection and querying)
- Matplotlib (visualization)
- Flask (API development)
- Jupyter Notebook (exploratory analysis)

---

## Methodology
