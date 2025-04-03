# Project: Ultimate Frisbee Data Analysis

## Codebook

This codebook describes the variables used in the analysis. Each variable corresponds to columns in the dataset labeled "ultimate_college_championship.csv" found in the `data/` folder. The descriptions of the variables include data types, possible values, and descriptions.

### Variables

| Variable Name         | Data Type   | Description                                                                 | Possible Values        |
|-----------------------|-------------|-----------------------------------------------------------------------------|------------------------|
| **player**            | `Character` | The name of the player.                                                    | Any text                 |
| **level**             | `Character` | The level of the player.                                                    | "Division 1", "Division 3"       |
| **gender**            | `Character` | The gender of the player.                                                    | "Women", "Men"      |
| **division**          | `Character` | The division in which the player plays, specified by gender.                       | "Division 1 Women", "Division 3 Women", "Division 1 Men", "Division 3 Men"            |
| **team_name**            | `Character` | The full name of the team the player is on.                                                    | The variable team_name can have many possible values, such as "Brown Brownian Motion", "Colorado Quandary", and more.      |
| **Turns**         | `Numeric`      | The number of turnovers the player threw.                                           | Continuous numeric values      |
| **Ds**         | `Numeric`      | The number of defensive blocks the player made.                                           | Continuous numeric values      |
| **Assists**         | `Numeric`      | The number of assists the player threw.                                           | Continuous numeric values      |
| **Points**         | `Numeric`      | The number of points the player scored.                                           | Continuous numeric values      |
| **plus_minus** | `Numeric`   | The player's +/- score, which represents the difference between the points scored and the points allowed while the player is on the court. | Continuous numeric values |
| **team_games**               | `Numeric`   | The number of games played.                                                  | Continuous numeric values |
| **turns_per_game**       | `Numeric` | The average turnovers per game.                                                          | Continuous numeric values |
| **ds_per_game**       | `Numeric` | The average defensive blocks per game.                                                          | Continuous numeric values |
| **ast_per_game**       | `Numeric` | The average assists per game.                                                          | Continuous numeric values |
| **pts_per_game**       | `Numeric` | The average points per game.                                                          | Continuous numeric values |
| **pls_mns_per_game**       | `Numeric` | The average +/- per game.                                                          | Continuous numeric values |

### Variables Created During the Project

| Variable Name         | Data Type   | Description                                                                 | Possible Values        |
|-----------------------|-------------|-----------------------------------------------------------------------------|------------------------|
| **school**       | `Character` | A new variable created to categorize players by school.                   | The variable school can have many possible values, such as "Brown", "Colorado", and more. |

## Data Source

The data is collected from kaggle.com at this link (https://www.kaggle.com/datasets/mexwell/2024-college-ultimate-championship-statistics). The dataset covers statistics from the 2024 Division 1 and 3 Men's and Women's Championships.

## How to Use the Codebook

This codebook is provided to help users understand the dataset and its structure. It should be referenced when performing data analysis and interpretation.

---

If you have any questions about the data or the variables, please feel free to contact Julia Vitale / jvitale@vassar.edu, Mia Zottoli / mzottoli@vassar.edu, Vishnu Lakshman / vlakshman@vassar.edu
