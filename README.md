# **nba-prediction**
### 2022 AI final project
### Introduction
Basketball is a well-known sport, and NBA, known as
the most prestigious basketball league, attracts the topnotch basketball players around the globe.In the final
project, we want to use the skills and techniques learned
from the course to predict the winner of NBA games.
We want to use different machine learning algorithm and
datasets. With the comparison of these results, finding the
one that has the best accuracy of prediction. If we can predict more accurately, we can actually apply the knowledge
learned in this course and get a sense of accomplishment.
### Prerequisites
- pip install nba_api
### data description
AWAY_STL,AWAY_BLK,AWAY_PF,AWAY_PTS,AWAY_PLUS_MINUS,HOME_TEAM_ABBREVIATION,HOME_STL,HOME_BLK,HOME_PF,HOME_PTS,HOME_PLUS_MINUS,HOME_OFF_RATING,HOME_DEF_RATING,HOME_AST_TOV,HOME_AST_RATIO,HOME_OREB_PCT,HOME_DREB_PCT,HOME_REB_PCT,HOME_TM_TOV_PCT,HOME_TS_PCT,HOME_PACE,HOME_PIE,AWAY_OFF_RATING,AWAY_DEF_RATING,AWAY_AST_TOV,AWAY_AST_RATIO,AWAY_OREB_PCT,AWAY_DREB_PCT,AWAY_REB_PCT,AWAY_TM_TOV_PCT,AWAY_TS_PCT,AWAY_E_PACE,AWAY_PACE,AWAY_PIE,HomeWin

|     Column Name    |                              Description                                   |
|:------------------:|:--------------------------------------------------------------------------:|
|      AWAY_STL      |                            Away team's steal                               |
|      AWAY_BLK      |                            Away team's block                               |
|       AWAY_PF      |                            Away team's foul                                |
|       HOME_STL     |                            Home team's steal                               |
|       HOME_BLK     |                            Home team's block                               |
|       HOME_PF      |                             Home team's foul                               |
|    AWAY_OFF_RATING |                        Away team's Offensive Rating                        |
|    AWAY_DEF_RATING |                        Away team's  Defensive Rating                       |
|    AWAY_AST_TOV    |                       Away team's Assist to Turnover Ratio                 |
|   AWAY_AST_RATIO   |                            Away team's Assist Ratio                        |
|    AWAY_OREB_PCT   |                      Away team's Offensive Rebound Percentage              |
|    AWAY_DREB_PCT   |                      Away team's Defensive Rebound Percentage              |
|    AWAY_REB_PCT    |                       Away team's Assist to Turnover Ratio                 |
|    AWAY_TM_TOV_PCT |                        Away team's Turnover Percentage                     |
|     AWAY_TS_PCT    |                       Away team's True Shooting Percentage                 |
|      AWAY_PACE     |                             Away team's Pace                               |
|      AWAY_PIE      |                       Away team's Player Impact Estimate                   |
|    HOME_OFF_RATING |                        Home team's Offensive Rating                        | 
|    HOME_DEF_RATING |                        Home team's  Defensive Rating                       |
|    HOME_AST_TOV    |                      Home team's Assist to Turnover Ratio                  |
|   HOME_AST_RATIO   |                          Home team's Assist Ratio                          |
|    HOME_OREB_PCT   |                     Home team's Offensive Rebound Percentage               |
|    HOME_DREB_PCT   |                     Home team's Defensive Rebound Percentage               |
|    HOME_REB_PCT    |                      Home team's Assist to Turnover Ratio                  |
|    HOME_TM_TOV_PCT |                      Home team's Turnover Percentage                       |
|     HOME_TS_PCT    |                     Home team's True Shooting Percentage                   |
|      HOME_PACE     |                             Home team's Pace                               |
|      HOME_PIE      |                     Home team's Player Impact Estimate                     |
|       HomeWin      |           If,data is 1,home team wins,else if data is 0,away team wins     |
|  H_Team_Elo_Before |                   Home team's elo rating before this game                  |
|  A_Team_Elo_Before |                   Away team's elo rating before this game                  |
