# nfl_all_pro
An analysis into the distribution of age and years of experience across different positions for all players that made an All-Pro team from 2000-2024

## Background Questions
- For each position, what is the age range for players making the All-pro team?
- If a team handed out market-setting contracts to one if its players, given that player's position, are they likely to continue playing at an All-Pro level? For example, how often do Edge rushers in the age range of T.J Watt and Myles Garret make All-pro?

## Data
I scraped All-pro data (1st and 2nd team) from football reference for years 2000-2024. I combined smaller unqiue position groups into the main ones typically talked about for comparison in the NFL. The Age variable is the age of the player as of Dec 31 that year. For example, last year's 2024 team, Lamar Jackson was 27 at Dec 31, 2024. This obviously has some limitationw and in an ideal world, the age variable would be rounded to a decimal place or two, but it does help for visualization purposes

## Main Takeaways
Position Analysis notebook contains visualizations on Age distributions for each position
#### Running backs are young
- Nothing ground breaking with this analysis
- Lowest IQR, middle 50% of All-pro RBs are between 24-27 years old
#### CBs peak youngest
- 28% 25 or younger, higest % of any major position group
#### With LB as a slight exception, very few defensive All-pros 31 and above
- Are Myles Garret and T.J. Watt good enough to be considered outliers?
#### Centers age slightly better than Guards and Tackles
