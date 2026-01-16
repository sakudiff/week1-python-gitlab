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
[OPTION 1: Focus on the Command Line/Git]
The most challenging part of this lab was getting comfortable with the terminal commands, specifically remembering to activate the virtual environment before installing packages. Regarding Git, I learned that using "git add" (staging) is a crucial safety step to review files before committing them. I also realized that writing meaningful commit messages makes it much easier to look back at the project history compared to generic updates.

[OPTION 2: Focus on Python/Pandas]
For me, the hardest part was understanding how to group the data in Pandas to get the specific averages I needed for the printout. Through the Git exercises, I learned that frequent, small commits are better than one large one because they create a clear checkpoint system. I also found that writing descriptive commit messages helps explain *why* a change was made, not just *what* was changed.

[OPTION 3: Focus on Workflow/Structure]
The hardest part was ensuring the folder structure was correct so that the script could save the chart into the `output` folder without errors. This assignment taught me that Git acts like a timeline for my project, where staging allows me to pick specific changes to save. I also learned that "atomic" (small) commits with clear messages make the project easier to debug if something goes wrong later.
