# 2024-T20-worldcup-performance-analysis-

To design a data-driven Power BI dashboard that delivers deep insights into the ICC Men’s T20 World Cup 2024,highlighting team performances, player dominance, match dynamics, and toss influence — empowering analysts, coaches, and fans to understand the story behind the tournament’s numbers.

Fact Table: ICC Mens T20 Worldcup

Dimension Table: Total Teams (Team master)

Relationships:

Total Teams[Team] → ICC Mens T20 Worldcup[1st Team] (Active)

Total Teams[Team] → ICC Mens T20 Worldcup[2nd Team] (Inactive)

DAX Pattern: USERELATIONSHIP() used to correctly count matches and wins across both columns.

Created clean model following Star Schema principles.

-- Tournament Overview (Executive Page)

KPIs: Total Matches, Total Runs, Total Teams, Toss Impact %, Tournament Winner

Charts:

Bar Chart → Matches Won by Each Team

Donut Chart → Wins by Method (Runs/Wickets)

Line Chart → Match Score Trends

Map → Matches by Venue

Smart Narrative → Auto-insight summary

-- Team Performance Dashboard

Clustered Bar Chart → Matches Played vs Won

Stacked Column Chart → Match Scoring Category (High/Average/Low)

Heatmap → Team Wins by Venue

Line Chart → Average 1st Innings Score per Team

KPI Cards → Win %, Matches Played, Highest Score

-- Player Performance Dashboard

Bar Chart → Top 10 Run Scorers

Bar Chart → Top 10 Wicket Takers

Treemap → Player of the Match Awards

Scatter Plot → Batting Dominance vs Bowling Impact

Card Visuals → Highest Run Scorer, Highest Wicket Taker, Tournament MVP

-- Match Analysis Dashboard

Table → Match-wise summary (Teams, Score, Winner, Venue, POM)

Line Chart → Winning Margin Trend

Donut Chart → Pressure Index Distribution

Scatter Chart → 1st vs 2nd Innings Comparison

KPI → Highest Scoring Match, Average Match Score, Low Scoring Match Count
