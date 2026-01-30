# ⚽ Football Pulse: Player, Team & Match Analytics Dashboard ⚽

**Advanced Soccer Performance Insights**  
**Built with Tableau** | ~1,000 Matches Analyzed | Real-World Football Data

![](https://img.olympics.com/images/image/private/t_s_pog_staticContent_hero_lg/f_auto/primary/dwo3ptv9guiqrkj1hfmc)

Interactive Power BI dashboards visualizing player contributions, team performance, match outcomes, and tactical insights from football matches.

## Project Overview

**Project Name:** Football Pulse – Player & Match Intelligence Dashboard

**Domain:** Sports Analytics / Football (Soccer) Business Intelligence

**Tools Used:** Tableau, DAX, Excel (data prep)

**Dataset Summary**  
- ~1,000 matches (spanning ~2023–2024)  
- Key entities: Players (Ronaldo, Salah, Haaland, Bellingham, De Bruyne, etc.), Teams (A–F), Positions (Forward, Midfielder, Defender, Goalkeeper)  
- Metrics: Goals, Assists, Minutes Played, Fouls, Match Results (Win/Draw/Loss), Shots, etc.

**Objectives**  
Transform raw football match data into actionable insights for:  
- Scouts & analysts → identify top performers  
- Coaches & teams → understand positional trends & match patterns  
- Fans & media → explore star players, goal contributions & game dynamics

## Dashboard 1: Player & Team Performance Overview

![](https://github.com/Shital9090/Sports_Football_Player_Performance/blob/main/Player%20%26%20Team%20Performance%20Overview.png)

**Key Metrics**  
- Total Matches: 1,000  
- Total Goals: 2,055  
- Total Assists: 1,481  
- Average Minutes Played per Appearance: ~60 min

**Main Visuals**  
- **Top Goal Scorers** (Bar Chart): Ronaldo, Salah, Haaland, Griezmann, De Bruyne leading  
- **Assists vs Goals** (Scatter Plot): Player comparison with shot volume bubbles  
- **Team-wise Goals Contribution** (Stacked Bar): Breakdown by position (Forward dominant in most teams)  
- Filters: Team (A–F), Position, Player Parameter (top N goals threshold)

**Core Insights**  
- Forwards contribute most goals across teams  
- Elite players (Ronaldo, Salah, Haaland) dominate scoring with high shot volume  
- Strong correlation between goals & assists for creative midfielders/forwards

## Dashboard 2: Match Results & Game Insights

![](https://github.com/Shital9090/Sports_Football_Player_Performance/blob/main/Match%20Results%20%26%20Game%20Insights.png)

**Key Visuals**  
- **Minutes Played vs Goals** (Stacked Bar): Player-level contribution over time  
- **Fouls by Position** (Bar Chart): Defenders commit most fouls (577), followed by Forwards (656? wait – check data), Midfielders (629)  
- **Matches Over Time** (Line Chart): Monthly match count trends (peaks mid-season)  
- **Match Result Distribution** (Pie Chart): Roughly balanced Wins (~33.6%), Draws (~32.8%), Losses (~33.6%)  
- Filters: Match Result (Win/Draw/Loss), Position

**Core Insights**  
- High foul count from Defenders & Forwards → physical/tactical style indicator  
- Consistent match volume with seasonal peaks  
- Near-even win/draw/loss split → competitive dataset  
- Top players maintain high minutes + goal output across periods

## Features & Interactivity
- Slicers for Team, Position, Player, Match Result, Date Range  
- Cross-filtering between visuals  
- Tooltips with detailed player/match stats

## Skills Demonstrated
- Data modeling & relationships (Players ↔ Matches ↔ Teams)  
- Advanced DAX (rankings, time intelligence, conditional measures)  
- Dashboard design (layout, themes, conditional formatting)  
- Sports data storytelling

## How to Use / Explore
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers to filter teams/players/positions  
4. Hover for details & drill through if implemented

## Future Enhancements
- Add xG/xA metrics (if data available)  
- Player radar/pizza charts  
- Team form streaks & head-to-head  
- Win probability modeling  
- Export to Power BI Service for sharing

Feel free to ⭐ the repo, fork, or contribute!

Made with passion for football analytics ⚽📊
