# MapleRank : An Exploratory Analysis on the Popularity of Jobs in Global MapleStory

## Table of Contents
* [Introduction](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#introduction)
* [Findings](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#findings)
    * [World Data](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#world-data)
    * [Level Data](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#level-data)
    * [Class Data](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#class-data)
* [In Depth Analysis](https://github.com/kaishuun/MapleRank#in-depth-analysis)
* [Data Set](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis#data-set)

## Introduction
Maplestory has been a popular MMORPG in the early-mid 2000s. Despite its dwindling popularity, it's one of the games I always return to every semester break. One of the big questions that a lot of people have and one that I ask quite frequently to my friends is "What job should I play?"; this question, combined with me recently learning web scraping has led me to find the data myself to look at player behaviour on choosing jobs and worlds. 

In this Exploratory Analysis, we will answer the questions of:
- What jobs are popular?
- How do players differ in each world?
- What levels do most players end up?

In this Analysis, we strictly look at players over level 205.

## Findings

### World Data

![](https://res.cloudinary.com/kevinhe/image/upload/v1594505679/World_Distribution_pg1bhz.png)

Here we see the distribution of players in each world. A common issue in MapleStory is players trying to find an empty map to either train or meso farm, for those who want more of a solo play styler a less populated world such as Elysium would be a perfect fit, while in Bera trying to find a guild or party quest would be much easier. This also shows the popularity and success of Reboot, being a special server where you can't trade with other players and where game enhancements could be purchased through mesos instead of money.

### Level Data
![](https://res.cloudinary.com/kevinhe/image/upload/v1594505666/Level_Distribution_per_world_mmz3b7.png)

Next, we take a look at what levels most players are. Player levels for each world are similarly distributed with a peak around level 210 followed by an exponential decrease. This shows that despite reboot being different from the normal worlds, players tend to stop playing around level 210.

### Class Data
![](https://res.cloudinary.com/kevinhe/image/upload/v1594505654/popular_classes_for_each_world_y8cphe.png)

Finally, we take a closer look at what jobs players tend to play more. Kannas tend to be the most popular class in each of the worlds, primarily due to the popularity of meso farming and Kanna's Kishin skill, which boosts up spawn rate of monsters. Following along, explorers top other job types, which makes sense since each explorer category covers 2-3 different jobs (eg. Mages cover Ice/Lightning, Fire/Poison, and Bishop jobs). Looking at least played jobs, these jobs most often are in dire need of skill revamps due to their ageing play style or their damage output.

![](https://res.cloudinary.com/kevinhe/image/upload/v1594505641/Max_Level_per_world_rrsxd1.png)

For hardcore players hoping to be the first to hit cap level in their world, many jobs still don't have a level 275 in their world! Reboot has most characters up to the level cap, in the normal worlds, rankings are still up for grabs for multiple different jobs.
   
## In Depth Analysis
For a more in-depth analysis of player data and more graphs showing the spread of jobs and worlds check out my notebook [here](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis/blob/master/Maplestory%20Analysis.ipynb) . In there you'll find my code and more in-depth commentary of my findings.

## Data Set
Feel free to use my collected data [here](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis/blob/master/Maplestory%20Rank%20Data.csv) . I gathered the data using a web scraper that took down the rankings of players on the official MapleStory site. Character data up to level 203 were collected, but only level 205 and above characters were present for this analysis. This data was last updated on June 14. For summary statistics of different Jobs in each world click [here](https://github.com/kaishuun/Maplestory-Rankings-Exploratory-Analysis/blob/master/Summary%20Statistics.csv).
