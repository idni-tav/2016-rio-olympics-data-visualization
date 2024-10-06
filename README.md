# 2016 Rio Olympics Data Visualization

## Overview
This project explores data from the **2016 Rio Olympic Games** using **SQL** for data extraction and **Tableau** for data visualization. This simplified analysis aims to demonstrate and practice key skills in data processing, visualization, and analysis for potential recruiters, rather than providing an exhaustive examination.

## Project Structure
The analysis focuses on three key areas:
1. **Athlete Demographics**: Trends in age, height, and weight across different sports and genders.
2. **Event Distribution**: Mapping the locations of events across Rio's neighborhoods and analyzing the distribution of events across various sports.
3. **Country Performance**: Ranking the top-performing countries by gold medals, and subsequently adjusting for factors such as population and GDP.

### Additional Considerations:
- **Counting Medals by Event**: Medals were initially counted based on the number of athletes per country. However, this skewed results in favor of countries with strong team sports, as an entire team (for example 11 football players) would be counted as multiple medals. This issue was identified but not addressed due to data limitations.
- **GDP as a Metric**: While GDP was used to compare country performance, it doesn’t account for the specific investments in sports. A more insightful analysis would consider how much of a country’s GDP is allocated to sports initiatives, which requires deeper research.
- **Demographics of Medal-Winning Athletes**: Analyzing the demographics of athletes who won medals across multiple Olympic Games could reveal trends in successful characteristics by sport. This would require expanding the dataset to cover winners from additional years.

## Key Technologies
- **SQL**: For data extraction, cleaning, and processing.
- **Tableau**: For creating interactive visualizations.
- **Kaggle Notebook**: Used for documenting the entire analysis process.

## Visualizations
The following visualizations were created and combined in a Tableau Story, which can be accessed here: [RioOlympicGames2016](https://public.tableau.com/app/profile/idni.tav/vizzes).

1. **Athlete Demographics:**
   - 3 Boxplot Charts comparing age, height, and weight across sports and genders.

2. **Event Distribution:**
   - 1 Treemap showcasing the hierarchy of events.
   - 1 Event Density Map displaying the geographical distribution of events across Rio’s neighborhoods.

3. **Country Performance:**
   - 3 Bar Charts illustrating the top-performing ranked countries based on: total number of medals, number of medals adjusted for population, and number of medals adjusted for GDP.
   - 1 Sunburst Plot + Map displaying the top-performing on multiple ranks.

## Dataset
The dataset is sourced from [2016 Olympics in Rio de Janeiro](https://www.kaggle.com/datasets/rio2016/olympic-games) and contains data on:
- **Athletes**: Personal details such as name, nationality, and sport, along with demographic information including gender, date of birth, height, and weight
- **Countries**: Population and GDP per capita of each country
- **Events**: Details on the events, such as venues, disciplines and sports

The data has been cleaned and processed using SQL queries to standardize formats and prepare it for visualization.

## Key Findings
Some insights gathered from this analysis include:
- The neighborhood with the highest concentration of events was Barra da Tijuca.
- The sports with the most events and titles in the Olympics were aquatics and athletics.
- The countries that consistently ranked among the top in all three categories were Russia, Argentina, Australia, Germany, Denmark, and Great Britain.

## License
The dataset is publicly available under the **CC0: Public Domain** license, meaning you are free to use, modify, and distribute it.

