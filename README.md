- Hi, I’m Chris Mullens, @chmullens here and most other professional sites I'm on
- I’m interested in data! Analysis, statistics, visualization, and other tools.
- I’m currently focusing on Python, SQL, R and applying machine learning techniques in Python and R.  
- You can reach me at chmullens@gmail.com, or chmullens on LinkedIn
 
Current public repositories:
1. Names: Repository for the project "Hey, I know that name!", my capstone for Data Incubator Winter 2021. It focuses on common names in the United States, from 1880 to the current day. The first part of the project is a tool to visualize names that are characteristic to a given year and age range; the second estimates future name popularity. This project uses US birth name and actuarial data, and involves data scraping, interpolation, feature engineering, data visualization in Matplotlib and Plotly, web APIs, affinity propagation clustering, and (currently) linear regression modeling for future name popularity estimations. 
2. Dice: This is a d20 dice tester to visualize whether dice are biased. It primarily uses Monte Carlo methods to estimate the likelihood that a given set of rolls comes from an unbiased dice, with an interactive dice visualization and face likelihood visualization. 
3. Covid tracking retrospective: This is a visualization of state-by-state data from the volunteer COVID Tracking Project, which provided the most comprehensive early-pandemic data available for the US and continued until May 2021. I used the data as a testbed for seeing what matplotlib can do, and as such there's a lot more info in the visualization than I would typically include. The final video file is included in the repository. 


Other things I'm working on: 
1. Multidimensional Kalman filtering for asset prices. A Kalman filter is one of the cleanest examples of a dynamic Bayesian network. You have a state, then you get new data, both of which have noise. Adding them together gives you a better state estimate, then you project forward (adding uncertainty) and update with a new measure (reduce uncertainty) repeatedly across time. Kalman filters are the optimal way to  predict the current state of a system under some assumptions. I'm working on implementing a multidimensional Kalman filter to track Steam market data for items that are closely related. It's a great test dataset for irregular sales data, and extending the filter to multiple dimensions needs governing equations to relate the variables, which I've been working on the logic for. 
2. Panel data regression for name tracking, great for modeling time series data with many variables. 
3. Recurrent neural networks (RNN), and long short-term memory (LSTM), additional great tools for tracking and predicting how data changes over time, for both names and market data.

<!---
chmullens/chmullens is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
