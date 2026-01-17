# Analysis of Titanic Fares by Class


name = "week1-python-gitlab"

version = "0.1.0"

description = "Exploratory data analysis and visualization pipeline for the Titanic dataset."

readme = "README.md"

requires-python = "3.11"

dependencies = [
    "matplotli 3.10.0",
    "pandas 2.2.0",
    "plotly 6.0.0",
    "seaborn 0.13.0",
]


dataset = ("https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv")

# How to run
# Initialize and synchronize the environment using uv
uv python pin 3.11.11
uv sync

# Activate the virtual environment
source .venv/bin/activate

# Execute the analysis script
uv run analyze.py

# What it does
Loads the data and fetches the Titanic dataset directly from the URL.

Summarizes the data by printing the total number of rows/columns, a list of all the column names, and the first 5 rows to the console.

It then cleans and processes the data by selecting the class and fare columns respectively, removing missing values to ensure the data is numeric.

It then calculates the averages and groups the data class calculates the average fare for each and prints the results sorted from highest to lowest.

To visualize the data it creates a bar chart of the average fares and it finally generates the visualization  in an image format in /output/chart.png 



# Reflection
The most challenging part of this lab was transitioning from traditional environment managers to the uv workflow, specifically managing the terminal commands required to sync dependencies correctly. 

We learned that Git staging is a vital step for reviewing changes and ensuring that environment files like .venv are not accidentally tracked in the repository. 

In addition, we realized that using atomic commits with descriptive messages makes it much simpler to track the evolution of the project compared to using single, large updates.


