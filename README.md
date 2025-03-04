# Insight into the WNBA
WNBA is an organization that has been undervalued for a large part of its history. Its sharp increase in mainstream popularity in recent years introduces a question of if the momentum towards the sport will continue to grow or if this is their “15 min of fame” due to specific factors.
# Table of Contents
- [Motivation](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#motivation)
- [Data Questions](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#data-questions)
- [Technologies](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#technologies)
- [Data Process](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#data-process)
- [Data Sources](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#data-sources)
- [Conclusion](https://github.com/tasleem-m/Insight-into-the-WNBA/edit/main/README.md#conclusion)
# Motivation
<details>
<summary>
Here is why I have chosen this project
</summary>

I am an avid sports fan, with football being my primary sport of choice—American football, that is. As a young woman, I never paid much attention to women’s sports. However, that began to change around 2023. Names like A’ja Wilson, Caitlin Clark, Angel Reese, and others started to appear more frequently in the media. A’ja Wilson signed one of the richest deals ever for a women’s basketball player with Nike. Caitlin Clark was breaking records not only in women’s college basketball but also in men’s college basketball. Angel Reese was named Most Outstanding Player in the NCAA championship, helping LSU win their first-ever national title.

While there have always been popular WNBA players, such as Sue Bird and Lisa Leslie, whom I had heard of, something felt different this time. I began to question why this shift was happening. Although I was familiar with the WNBA (as the sister league to the NBA), my own interest—and the interest of many others, according to social media—began to rise with these significant milestones. So, when it came time to select a topic for my Capstone project, the WNBA was at the top of my list. I wanted to explore the various factors contributing to this surge in popularity.
</details>

# Data Questions
- What is contributing to the current rise in popularity of the WNBA?
  - Has the game become more competitive?
  - Is it the players?
  - Is it TikTok?
- Are certain game metrics correlated with playoff success?
- What teams are the fans going to see?
# Technologies
- Python
- Power BI
- PowerPoint
# Data Process
<details>
<summary>
Gather
</summary>

Game statistics from 1997 to 2024 were gathered from Basketball-reference.com on a per-year basis due to the website's structure. CSV files were downloaded and renamed for each respective year. Once all files were collected, Python was used to concatenate them via a for-loop, and a new 'Year' column was added by referencing the base file name.
</details>

<details>
<summary>
Clean
</summary>
Specific statistical percentage columns, originally in decimal format, were converted to percentage values for analysis. The 'Year' column was cleaned to extract only the year from the full file name and then converted into an integer format. The data was subsequently exported as CSV files and uploaded to Power BI for dashboard visualization.
</details>

# Data Sources
1.	https://www.acrossthetimeline.com/wnba/attendance.html#
    * The attendance data source does not include figures for 2020 due to the impact of COVID-19 and omits home attendance data for the Indiana Fever in 2021.
2.	https://www.basketball-reference.com/wnba/
3.	https://www.wnba.com/news/wnba-delivers-record-setting-2024-season
# Conclusion
In recent years, the WNBA has experienced historic growth within the sport. So, what factors are contributing to its success, and what can we expect moving forward?

An analysis of game statistics and attendance reveals that player popularity plays a significant role in fan engagement. While competitive teams certainly encourage fan investment, it is the presence of popular players that drives a higher level of involvement.

Fostering and leveraging the appeal of these popular players will be crucial to the WNBA’s continued success.
