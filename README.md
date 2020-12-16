# nba-player-advanced-metrics

`nba-data-historical.csv` contains historical RAPTOR and other NBA data.

Note: The following columns are not included for the 2019-20 season or later: `tmRtg`, `MP%`, `P/36`, `A/36`, `R/36`,	`SB/36`, `TO/36`, `PIE%`, `AWS%`, `ORtg`, `%Pos`, `DRtg`, `2P%`,	`3P%`, and `FT%`. These values are also not included for playoffs in any year.

|  Category   |                     Description                     |
|-------------|-----------------------------------------------------|
| player_id   | Basketball-Reference.com player ID                  |
| name_common | Name of player                                      |
| year_id     | Season (i.e., 2019-20 is "2000")                    |
| type        | Regular season (RS) or playoffs (PO)                |
| age         | Age on Feb. 1 of season                             |
| team_id     | Team played for                                     |
| pos         | Primary position                                    |
| tmRtg       | Team efficiency margin                              |
| franch_id   | Franchise played for                                |
| G           | Games played                                        |
| Min         | Minutes played                                      |
| MP%         | Share of team minutes played                        |
| MPG         | Minutes per game                                    |
| P/36        | Pace-adjusted points per 36 minutes                 |
| TS%         | True Shooting Percentage                            |
| A/36        | Pace-adjusted assists per 36 minutes                |
| R/36        | Pace-adjusted rebounds per 36 minutes               |
| SB/36       | Pace-adjusted steals plus blocks per 36 minutes     |
| TO/36       | Pace-adjusted turnovers per 36 minutes              |
| Raptor O    | Offensive RAPTOR rating                             |
| Raptor D    | Defensive RAPTOR rating                             |
| Raptor+/-   | Total RAPTOR rating                                 |
| Raptor WAR  | Total RAPTOR wins above replacement                 |
| PIE%        | Player Impact Estimate                              |
| AWS%        | PIE% using Alternate Win Score                      |
| USG%        | Usage Rate                                          |
| AST%        | Assist Rate                                         |
| TOV%        | Turnover Rate                                       |
| ORB%        | Offensive Rebound Rate                              |
| DRB%        | Defensive Rebound Rate                              |
| TRB%        | Total Rebound Rate                                  |
| STL%        | Steal Rate                                          |
| BLK%        | Block Rate                                          |
| ORtg        | Offensive Rating (points produced per 100 poss.)    |
| %Pos        | Share of team possessions used                      |
| DRtg        | Defensive Rating (points allowed per 100 poss.)     |
| 2P%         | 2-point field goal percentage                       |
| 3P%         | 3-point field goal percentage                       |
| FT%         | Free throw percentage                               |
| 3PAr        | Share of field goal attempts that were 3-pointers   |
| FTAr        | Ratio of free throw attempts to field goal attempts |
| Pace +/-    | Player's effect on team pace                        |

