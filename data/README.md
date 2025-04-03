# Project: Ultimate Frisbee Data Analysis

## Codebook

This codebook describes the variables used in the analysis. Each variable corresponds to columns in the dataset(s) found in the `data/` folder. The descriptions of the variables include data types, possible values, and explanations.

### Variables

| Variable Name         | Data Type   | Description                                                                 | Possible Values        |
|-----------------------|-------------|-----------------------------------------------------------------------------|------------------------|
| **player**            | `Character` | The name of the player.                                                    | Any text                 |
| **level**             | `Character` | The level of the player.                                                    | "Division 1", "Division 3"       |
| **gender**            | `Character` | The gender of the player.                                                    | "Women", "Men"      |
| **division**          | `Character` | The division in which the player plays, specified by gender.                       | "Division 1 Women", "Division 3 Women", "Division 1 Men", "Division 3 Men"            |
| **team_name**            | `Character` | The full name of the team the player is on.                                                    | The variable team_name can have many possible values, such as "Brown Brownian Motion", "Colorado Quandary", and more.      |
| **Turns**         | `Numeric`      | The number of turnovers the player threw.                                           | Continuous numeric values      |
| **player_plus_minus** | `Numeric`   | The player's +/- score, which represents the difference between the points scored and the points allowed while the player is on the court. | Continuous numeric values (e.g., -5, 10, 3) |
| **age**               | `Numeric`   | Age of the player in years.                                                  | Continuous numeric values (e.g., 18, 22, 30) |
| **player_name**       | `Character` | Name of the player.                                                          | Any text               |

### Variables Created During the Project

| Variable Name         | Data Type   | Description                                                                 | Possible Values        |
|-----------------------|-------------|-----------------------------------------------------------------------------|------------------------|
| **age_category**       | `Character` | A new variable created to categorize players based on age.                   | "Under 20", "20-30", "Over 30" |

## Data Source

The data is collected from [source name], with the dataset being updated regularly. The dataset covers player performance across various seasons.

## How to Use the Codebook

This codebook is provided to help users understand the dataset and its structure. It should be referenced when performing data analysis and interpretation.

---

If you have any questions about the data or the variables, please feel free to contact [your name/email].
