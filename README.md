<!DOCTYPE html>
<html>
<head>
    <h1>NBA Fantasy Player Salary Analysis</h1>
</head>
<body>

<h1>Introduction</h1>
<p>This project aims to analyze the salary distribution and team investment in the <b>top 150 NBA Fantasy players</b>. By leveraging data from various sources such as <a href="www.rotowire.com">www.rotowire.com</a>, <a href="https://basketball.realgm.com">https://basketball.realgm.com</a>, and <a href="https://hoopshype.com">https://hoopshype.com</a>, we will explore various aspects of player salaries, including total salary investment per team, salary distribution by position, and the number of top players in each conference.</p>

<h2>Project Scope</h2>
<p>The scope of this project includes the following:</p>
<ul>
    <li>Collecting data on the top 150 NBA Fantasy players, their salaries, teams, and positions.</li>
    <li>Analyzing the total salary investment in these top players per team.</li>
    <li>Comparing the salary distribution for each position to the overall salary distribution among these top players.</li>
    <li>Investigating whether there is a significant difference in the number of top players between the two conferences.</li>
</ul>
<p>Through this analysis, we aim to gain insights into player valuation, team strategies, and market dynamics in the NBA.</p>

<h2>Data Extraction</h2>
<p>To gather the necessary data for this project, we will use web scraping techniques in Python to extract information from the aforementioned websites. Here’s what we plan to extract:</p>
<ul>
    <li>From <a href="www.rotowire.com">www.rotowire.com</a>: Player rankings, names, positions, and teams.</li>
    <li>From <a href="https://basketball.realgm.com">https://basketball.realgm.com</a>: Additional player information such as age, height, weight, college attended, and years in the league.</li>
    <li>From <a href="https://hoopshype.com">https://hoopshype.com</a>: Player salary information for the 2023-2024 season.</li>
</ul>
<p>By combining data from these sources, we can create a comprehensive dataset for our analysis. Please note that all data extraction will be done in compliance with the terms of service of these websites.</p>

<h2>Data Analysis</h2>
<p>Once we have collected and cleaned our data, we can use various statistical methods and visualization techniques to answer our research questions.</p>

<h3>Q1: Total Salary Investment per Team</h3>
<img src="https://github.com/NelsonLi81/Python_Project_2/blob/main/24.08.2023_15.11.15_REC.png"></img>
<p>Observations from the Result:</p>
<ul>
    <li>Investment Range: The length of each bar shows the total salary investment for each team. Teams with longer bars have invested more in their players’ salaries.</li>
    <li>Investment Distribution: By comparing the bars, we can see how salary investments are distributed across different teams.</li>
    <li>Color Gradient: The color gradient provides a visual representation of the total salary investment. Teams with darker bars have higher total salary investments.</li>
</ul>
<p>This chart provides a visual comparison of the total salary investments made by different basketball teams.</p>

<h3>Q2: Salary Distribution by Position</h3>

<img src="https://github.com/NelsonLi81/Python_Project_2/blob/main/24.08.2023_15.15.19_REC.png"></img>

<p>Observations from the Result:</p>
<ul>
    <li>Range of salaries: The vertical length of each box shows the interquartile range (IQR) of salaries for each position.</li>
    <li>Median salary: The line inside each box represents the median salary for each position.</li>
    <li>Outliers: Any dots above or below the boxes represent outliers or salaries that fall outside of the majority of data.</li>
    <li>Salary distribution: By comparing the boxes, we can see how salaries are distributed across different positions.</li>
</ul>
<p>This chart provides a visual comparison of salary distributions across different positions in NBA Fantasy.</p>

<h3>Q3: Number of Players in Each Conference</h3>
<p>Observations from the Result:</p>
<ul>
    <li>Total Salary Investment: The length of each bar shows the total salary investment for each conference.</li>
    <li>Number of Players: The number of players in each conference is annotated on each bar.</li>
    <li>Investment Comparison: By comparing the bars, we can see how salary investments differ between the Eastern and Western conferences.</li>
</ul>
<p>This chart provides a visual comparison of the total salary investments made by different basketball conferences.</p>

<h2>Project Conclusion</h2>
<p>In conclusion, this project will provide valuable insights into player salaries and team strategies in the NBA. By understanding how teams invest in their players and how player salaries are distributed across different positions and conferences, we can gain a deeper understanding of the economics of professional basketball. This could potentially inform future decisions made by teams, players, and league officials.</p>

</body>
</html>
