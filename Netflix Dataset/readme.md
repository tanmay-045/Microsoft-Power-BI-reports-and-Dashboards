## Netflix - EDA and Dashboard

##### Overview

This project involves exploratory data analysis (EDA) and dashboard creation using the Netflix dataset. The dataset includes the following columns:
- `show_id`
- `type`
- `title`
- `cast`
- `director`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

#### Data Cleaning and Preparation

During the EDA phase, I addressed various data quality issues, including:
- Handling missing and null values using mode imputation and other techniques.
- Managing outliers.
- Performing column segregation and generating conditional columns.
- Creating an additional table, `category_mapping`, to accurately count each category.

#### Dashboard Insights

The dashboard provides the following insights:
1. There are a total of 8,802 titles distributed across 42 genres.
2. The genre 'International Movies' has the highest count with 2,752 titles, followed by 'Dramas' and 'Comedies'.
3. The country with the most titles is the United States.
4. The year 2018 has the highest number of titles, including 767 movies and 380 TV shows.
5. The second dashboard in the report presents individual profiles for TV shows and movies.
