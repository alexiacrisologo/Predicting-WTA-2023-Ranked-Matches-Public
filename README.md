**Data dictionary:**

| Variable | Description | Type |
|------------------------|------------------------------|------------------|
| `minutes` | Duration of the match in minutes (response variable) | Numeric |
| `surface` | Type of court surface (Clay, Hard, Grass, etc.) | Categorical |
| `winner_hand / loser_hand` | Handedness of the winner/loser (R, L, or U for unknown) | Categorical |
| `winner_age / loser_age` | Age of the winner/loser (in years) | Numeric |
| `winner_ht / loser_ht` | Height of the winner/loser (in centimeters) | Numeric |
| `winner_rank / loser_rank` | World ranking of the winner/loser at the time of the match | Numeric |
| `winner_rank_points / loser_rank_points` | Ranking points of the winner/loser | Numeric |
| `tourney_name` | Name of the tournament | Categorical |
| `tourney_level` | Tournament level (e.g., ITF, WTA 125, WTA 250) | Categorical |
| `tourney_date` | Starting date of the tournament | Date |
| `winner_seed / loser_seed` | Tournament seeding for the players (if applicable) | Numeric |
| `score` | Final match score (set-by-set) | Character |
| `round` | Stage of the tournament (Qualifying, stage of bracket format) | Numeric |

**Source**

Our data is from the Women's Tennis Association data set from Awesomedata's GitHub repository (https://github.com/JeffSackmann/tennis_wta/blob/master/wta_matches_qual_itf_2023.csv). The data was created in 2023 and was collected from the International Tennis Federation. The data contains 34,323 observations and 49 variables. Our variables of interest in our research include surface, winner and loser height, winner and loser age, and winner and loser hand. 