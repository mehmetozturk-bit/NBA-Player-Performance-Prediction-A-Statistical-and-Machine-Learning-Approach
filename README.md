# NBA-Player-Performance-Prediction-A-Statistical-and-Machine-Learning-Approach
2. Motivation
Basketball is a data-rich sport where almost every action on the court is recorded.
Understanding what factors affect a player’s scoring performance (Points Per Game, or PPG) can provide valuable insights into the game and players’ development.
This project aims to analyze NBA player statistics from recent seasons to discover which variables — such as age, position, playing time, and shooting accuracy — have the strongest relationship with scoring performance.
Rather than building a complex machine learning model, the project will focus on data exploration, visualization, and simple statistical analysis to identify meaningful patterns and trends.
3. Research Question
What player and team characteristics are most related to scoring performance (PPG)?
How do age, playing time, and position affect scoring?
Are there noticeable trends across different seasons?
4. Data Sources
This project will use publicly available basketball data from the following sources:
Basketball-Reference.com – season-level player statistics (Points, Assists, Rebounds, FG%, 3P%, FT%, etc.)
NBA Stats – team-level information such as win percentage and offensive/defensive ratings
Data enrichment plan:
In addition to individual player stats, team-level performance indicators (for example, win percentage or pace) will be merged to provide more context.
5. Methodology (Planned Steps)
a. Data Collection and Cleaning
Download player statistics for several recent seasons (e.g., 2020–2024).
Keep consistent player names and team abbreviations.
Remove missing or incomplete records.
Focus on players who have played at least a minimum number of games (to ensure fair comparison).
b. Exploratory Data Analysis (EDA)
Use descriptive statistics to summarize the data (mean, median, range).
Visualize relationships using scatter plots, histograms, and correlation heatmaps.
Compare PPG averages by player position (e.g., Guard, Forward, Center).
Explore how scoring changes with age or minutes played.
c. Statistical Analysis
Compute correlation between PPG and key numeric features (Minutes, FG%, Age).
Perform simple linear regression to understand how PPG changes with these variables.
Conduct small hypothesis tests, e.g.:
“Do Guards score significantly more points than Centers?”
6. Expected Findings
Playing time (Minutes per Game) and shooting accuracy (FG%) will likely be the strongest predictors of PPG.
Younger players might have lower averages but show faster improvement trends.
Guards are expected to have higher PPG on average compared to Centers.
Team success (Win%) may have a mild positive relationship with player performance.
7. Limitations and Future Work
Data does not account for injuries, player roles, or team strategy.
Only focuses on scoring (PPG), not defensive performance or efficiency.
Future work could include time-series modeling or machine learning prediction for “next season” PPG.
8. Tools & Libraries
Python: pandas, numpy, matplotlib, seaborn
Jupyter Notebook: for data exploration and visualization
GitHub: for version control and documentation
9. Project Timeline
Date	Milestone	Description
31 Oct	Proposal Submission	GitHub repo + README.md (this file)
28 Nov	Data Collection & EDA	Gather data and perform descriptive & visual analysis
02 Jan	Statistical Analysis	Apply correlation and regression analysis
09 Jan	Final Submission	Final report, visualizations, and conclusions
