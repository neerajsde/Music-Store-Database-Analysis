# Music Store Data Analysis Project

## Overview

This project involves the analysis of a music store dataset using Python and MySQL. The dataset contains information about albums, artists, customers, employees, genres, invoices, invoice lines, media types, playlists, playlist tracks, and tracks.

The project is structured as follows:
1. Importing necessary libraries and modules.
2. Extracting, transforming, and loading (ETL) data from CSV files into a MySQL database.
3. Database connection and exploration of tables.
4. Data exploration, including pair plots, dataset information, and descriptive statistics.
5. Analysis and visualization of various aspects of the music store dataset.

## Requirements

- Python 3.x
- MySQL database
- Required Python libraries: pandas, matplotlib, seaborn, mysql-connector, and any other dependencies mentioned in the code.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/neerajsde/Music-Store-Database-Analysis.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn mysql-connector
   ```

3. Setup MySQL database and create a database named 'Music_database'. Update the database connection details in the code.

4. Run the Jupyter notebook or Python script to execute the project.

## Project Structure

- `database.py`: Module for database operations (creation, insertion, reading).
- `Mymodule.py`: Custom module for text formatting and visualization.
- `MusicStoreAnalysis.ipynb`: Jupyter notebook containing the project code.

## Data Exploration

Explore various tables in the music store database, analyze customer spending, identify popular genres, and visualize relationships between different entities.

## Analysis and Visualization

Answer specific questions related to the dataset, such as identifying the senior-most employee, countries with the most invoices, best customer, and more.