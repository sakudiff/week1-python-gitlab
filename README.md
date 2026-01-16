# Analysis of Titanic Fares by Class

**Dataset chosen:** Titanic Data (https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv)

# How to run
python3 -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python analyze.py

# What it does
This script performs an automated analysis of the Titanic passenger list:
* **Summarizes Data Structure:** It prints the dataset dimensions (rows/cols), lists available columns, and previews the first 5 records to the terminal.
* **Calculates Grouped Averages:** It groups the data by passenger "class" to compute and display the average fare paid for each category.
* **Visualizes Results:** It generates a bar graph comparing fares across classes and saves the image as `output/chart.png`.

# Reflection
The most challenging part of this lab was getting comfortable with the terminal commands, specifically remembering to activate the virtual environment before installing packages. Regarding Git, I learned that using "git add" (staging) is a crucial safety step to review files before committing them. I also realized that writing meaningful commit messages makes it much easier to look back at the project history compared to generic updates.


