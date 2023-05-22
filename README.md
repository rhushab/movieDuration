# Netflix Movie Analysis

This IPython Notebook provides an analysis of Netflix movie data using Python libraries such as pandas and matplotlib. The notebook explores movie durations over the years, subsets the data for movies only, and visualizes various aspects of the dataset.

## Prerequisites

Before running the notebook, ensure that you have the following dependencies installed:

- Python 3.x
- pandas (`pip install pandas`)
- matplotlib (`pip install matplotlib`)

Additionally, make sure you have the dataset file `netflix_data.csv` available in the appropriate location.

## Usage

1. Open the IPython Notebook file (`netflix_movie_analysis.ipynb`) in Jupyter Notebook or JupyterLab.
2. Run each cell in the notebook sequentially to execute the code and see the results.
3. The notebook will output visualizations and analysis based on the provided Netflix movie data.

## Contents

The notebook consists of the following sections:

1. **Introduction**: Creation of lists and dictionaries to store movie years and durations.
2. **Creating a DataFrame**: Conversion of the dictionary into a pandas DataFrame and printing it.
3. **Visualizing Movie Durations**: Plotting a line graph to visualize movie durations over the years.
4. **Exploring Netflix Movie Data**: Reading the Netflix movie data from a CSV file and printing the first five rows of the DataFrame.
5. **Filtering Movies**: Subsetting the DataFrame to consider only movies and selecting specific columns.
6. **Movie Duration Analysis**: Creating a scatter plot to examine movie duration trends by year of release.
7. **Short Movies**: Filtering for movies with durations shorter than 60 minutes and printing the first 20 rows.
8. **Genre-based Scatter Plot**: Generating a scatter plot of movie duration by release year, color-coded by genre.
9. **Movie Duration Trend**: Analyzing whether movies are getting shorter based on the available data.

## Note

- The analysis provided in this notebook is based on the provided Netflix movie dataset. Results and conclusions may vary depending on the dataset and its characteristics.
- This notebook serves as a demonstration of data analysis techniques using Python libraries and should be used as a reference or starting point for further analysis.

Enjoy exploring the Netflix movie data and conducting your analysis!
