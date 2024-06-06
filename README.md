# Project on high_diamond_ranked_10min dataset
Description and preliminary statistical analysis of high_diamond_ranked_10min dataset. <br>
<br>

*Table of contents:*
1. About the dataset.
2. Attribute information.
3. Key statistics.
<br>

### About the dataset
The dataset contains the various data about the first 10 minutes of matches of players classified as "Diamond" in the multiplayer online battle arena genre game "League of Legends". It can be used to predict the features, that let players have a better performance during matches. 

This detailed dataset, that contains almost 10 000 observations, can be found on kaggle: https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min.

The **main idea of the game** is for one team to take over the opponent's base. To achieve this, teammates must first destroy the opposing team's towers. The game includes various enrichments, such as dragons, heralds, and minions.  Players can collect gold and heighten their level (by gaining experience) by killing minions or opponents. They might use this gold to purchase items that provide improvements. Each match is consisted of two teams: red and blue, five players each, who must work together using strategy, skill, and teamwork to capture victory. <br>
<br>

### Attribute information
*gameId* - the unique ID of a player <br>
*blueWins* - information, wheather blue team won ('0' - no, '1' - yes) <br>
*blueWardsPlaced* - the number of wards that has been placed by blue team <br>
*blueWardsDestroyed* - the number of wards that has been destroyed by blue team <br>
*blueFirstBlood* - information, wheather someone from blue team killed as first in match ('0' - no, '1' - yes) <br>
*blueKills* - total number of red players, which were killed by blue ones <br>
*blueDeaths* - total number of blue players, which were killed <br>
*blueAssists* - total number of assists of kills that blue teammates had <br>
*blueEliteMonsters* - the number of elite monsters killed by blue team (blueDragons + blueHeralds) <br>
*blueDragons* - the number of dragons killed by blue team <br>
*blueHeralds* - the number of heralds killed by blue team <br>
*blueTowersDestroyed* - the number of towers destroyed by blue team <br>
*blueTotalGold* - total amount of gold won by the blue team <br>
*blueAvgLevel* - the average blue players level <br>
*blueTotalExperience* - total amount of experience gained by blue team <br>
*blueTotalMinionsKilled* - total amount of minions killed by blue team <br>
*blueTotalJungleMinionsKilled* - total amount of jungle minions killed by blue team <br>
*blueGoldDiff* - the difference in gold between blue and red team (blueTotalGold - redTotalGold) <br>
*blueExperienceDiff* - the difference in experience between blue and red team (blueTotalExperience - redTotalExperience) <br>
*blueCSPerMin* - the average number of minions killed in one minute by blue players <br>
*blueGoldPerMin* - the average amount of gold collected in one minute by blue players <br>
*redWardsPlaced* - the number of wards that has been placed by red team <br>
*redWardsDestroyed* - the number of wards that has been destroyed by red team <br>
*redFirstBlood* - information, wheather someone from red team killed as first in match ('0' - no, '1' - yes) <br>
*redKills* - total number of blue players, which were killed by red ones <br>
*redDeaths* - total number of red players, which were killed <br>
*redAssists* - total number of assists of kills that red teammates had <br>
*redEliteMonsters* - the number of elite monsters killed by red team (redDragons + redHeralds) <br>
*redDragons* - the number of dragons killed by red team <br>
*redHeralds* - the number of heralds killed by red team <br>
*redTowersDestroyed* - the number of towers destroyed by red team <br>
*redTotalGold* - total amount of gold won by the red team <br>
*redAvgLevel* - the average red players level <br>
*redTotalExperience* - total amount of experience gained by red team <br>
*redTotalMinionsKilled* - total amount of minions killed by the red team <br>
*redTotalJungleMinionsKilled* - total amount of jungle minions killed by red team <br>
*redGoldDiff* - the difference in gold between red and blue team (redTotalGold - blueTotalGold) <br>
*redExperienceDif* - the difference in experience between red and blue team (redTotalExperience - blueTotalExperience) <br>
*redCSPerMin* - the average number of minions killed in one minute by red players <br>
*redGoldPerMin* - the average amount of gold collected in one minute by red players <br>
<br>

### Key statistics

'''py
print("Hello")
'''
