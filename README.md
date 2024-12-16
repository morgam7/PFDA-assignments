# Weekly Assignments

![Panda Eating Computer](panda_eating_laptop.png)

This is the repository containing all the weekly assignments for the Programming for Data Analytics module of the [Higher Diploma in Science in Data Analytics given by ATU Galway-Mayo](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics). My lecturer is [Andrew Beatty](https://github.com/andrewbeattycourseware?tab=overview&from=2022-12-01&to=2022-12-31). He set us four assignments to explore different aspects of data analysis using Python, pandas, and matplotlib. My code is far from perfect, but I hope it gets the job done. Below is an overview of what each task involves and some highlights of what I learned along the way.

To create this repository, I installed Python using [Anaconda](https://www.anaconda.com/download), and I used [Visual Studio Code](https://code.visualstudio.com/) as a text editor and terminal. The image of the panda eating a computer was generated using OpenAI's DALL·E.

## Task Overview

### Task 2: Plotting Weather Data
In this assignment, I worked with a CSV file containing weather data to create a line graph plotting temperature over time. I used pandas for data manipulation and matplotlib for visualisation. One challenge I faced was dealing with a header row that wasn’t properly aligned, which required troubleshooting to fix. The final graph came out nice and clean, showing clear trends in the data.

### Task 3: Email Domains Pie Chart
This task involved parsing email addresses from a dataset and plotting a pie chart of email domains. The challenge was extracting the domain names from email addresses, which I achieved using pandas string operations. I then created a pie chart to display the proportions of each domain. I even added a slight “explosion” effect to highlight the most common domain.

### Task 5: Risk Simulation
Here, I simulated 1,000 individual battles from the board game Risk, following the game’s rules for attackers and defenders. I created a function to simulate dice rolls and track troop losses for both sides. The assignment also included an optional “extra marks” section to simulate full battles between armies of arbitrary sizes. I completed this by iterating through rounds until one side was wiped out. Visualising the results was both fun and rewarding!

### Task 6: Knock Airport Weather Analysis
For this final task, I analysed weather data from Knock Airport. I plotted temperature, daily mean temperature, and monthly mean temperature. In the more advanced part of the task, I worked on windspeed data, cleaning missing values and plotting rolling averages, daily maximums, and monthly means of daily maximums. Handling missing data and grouping for analysis were key skills in this task.

## Highlights and Challenges
- **Data Cleaning**: I had to deal with messy datasets, including missing values, misaligned headers, and non-numeric data.
- **Visualisation**: Learned how to create clear and readable graphs, including line plots, pie charts, and smoothed rolling averages.
- **Simulations**: Writing functions to simulate dice rolls and battles in Task 5 was a fun way to apply Python for something interactive.

## Resources
I relied on Python libraries like pandas and matplotlib throughout these assignments. Additional references include:
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- I also used Chat GPT when I found myself stumped. It was useful at explaining very specific problems I was having quickly, but it also got a few things wrong! 

- Other links to resources:  
    https://www.geeksforgeeks.org/how-to-plot-value-counts-in-pandas/  
    https://www.boardinfinity.com/blog/learn-about-reset-index-pandas/  
    https://stackoverflow.com/questions/31328861/replacing-header-with-top-row/  
    https://www.statology.org/pandas-set-first-row-as-header/  
    https://www.datacamp.com/tutorial/pandas-read-csv/  
    https://stackoverflow.com/questions/72468073/pandas-index-column-name-issue-when-reading-csv/  
    https://www.geeksforgeeks.org/how-to-fill-nan-values-with-mean-in-pandas/  
    https://www.w3resource.com/python-exercises/pandas_numpy/pandas_numpy-exercise-15.php/  
    https://pandas.pydata.org/docs/reference/api/pandas.to_numeric.html/  
    https://www.geeksforgeeks.org/convert-a-dataframe-column-to-integer-in-pandas/  
    https://stackoverflow.com/questions/43445125/pandas-groupby-datetime-function-does-not-preserve-dtype/  
    https://stackoverflow.com/questions/13361326/preserving-datetime-index-in-groupby-operation/  
    https://realpython.com/pandas-groupby/  
    https://www.geeksforgeeks.org/how-to-make-a-time-series-plot-with-rolling-average-in-python/  
    https://learnpython.com/blog/average-in-matplotlib/  
    https://towardsdatascience.com/time-travel-made-easy-a-comprehensive-guide-to-python-datetime-326dd1c57391/  
    https://www.statology.org/pandas-group-by-month/  
    https://stackoverflow.com/questions/41642126/matplotlib-customize-pie-chart-labels-and-dropshadow/  





