# End To End Cricket Data Analytics Project Using Web Scraping, Python, Pandas and Power BI 🏏

👋 Hi there! Welcome to the End To End Cricket Data Analytics Project Using Web Scraping, Python, Pandas and Power BI. This project aims to provide a comprehensive and interactive analysis of cricket matches using data collected from web scraping and transformed using Python and Power BI. 

## Data Source 🌐

The data is scraped from [Cricinfo](https://www.espncricinfo.com/), a sports website that provides live coverage and statistics of cricket matches. The data contains information about the match results, batting summaries, bowling summaries, and ball-by-ball details for each match. The data is collected as JSON format and is converted to a dataframe using Python.

## Data Transformation 🐍

We use Pandas and JSON libraries in Python to transform the JSON files into CSV files. We perform various operations such as renaming columns, appending dataframes, dropping columns, replacing values, creating dictionaries, and adding columns. We export the CSV files to our local directory.

## Data Loading 🔌

We use Power BI Desktop to load the CSV files into our data model. We use Power Query Editor to perform some additional transformations such as duplicating columns, splitting columns, sorting data, and adding columns. We also create relationships between the tables in our data model.

## Data Analysis 📈

We use Power BI Desktop to create measures and calculated columns using DAX language. We use these measures and columns to create various charts and tables to visualize the data. We also use slicers and filters to make our report interactive and dynamic.

Some of the measures and calculated columns we create are:

- Total Runs: The sum of runs scored by a batsman or a team.
- Total Innings Batted: The count of innings played by a batsman or a team.
- Batting Average: The ratio of total runs to total innings batted.
- Boundary %: The percentage of runs scored from boundaries (fours and sixes) by a batsman or a team.
- Avg. balls Faced: The average number of balls faced by a batsman or a team per innings.
- Wickets: The count of wickets taken by a bowler or a team.
- Balls Bowled: The count of balls delivered by a bowler or a team.
- Bowling Strike Rate: The ratio of balls bowled to wickets taken by a bowler or a team.
- Bowling Average: The ratio of runs conceded to wickets taken by a bowler or a team.
- Boundary runs: The sum of runs scored from boundaries (fours and sixes) by a batsman or a team.
- Boundary runs bowling: The sum of runs conceded from boundaries (fours and sixes) by a bowler or a team.
- Custom Batting Order: A calculated column that assigns a custom batting order based on the position of the batsman in the innings.

## How to Run the Project 💻

To run this project, you will need the following:

- Python 3.x
- Pandas
- JSON
- Power BI Desktop

You can follow these steps:

1. Clone this repository or download the zip file.
2. Open the `data_transformation.py` file in your preferred IDE or editor and run it. This will generate the CSV files in your local directory.
3. Open the `cricket_data_analysis.pbix` file in Power BI Desktop and refresh the data source. This will load the CSV files into your data model.
4. Explore the report and interact with the visuals.

Then, follow the instructions in the notebook and enjoy the analysis!
If you have any questions, suggestions, or feedback, feel free to contact me at nainil30maladkar@gmail.com 💬

Happy reading and analysing! 🎉
