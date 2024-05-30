# Olympic History Data Visualization

This repository contains a data visualization project that delves into 120 years of Olympic history, examining a wide array of variables such as athlete details, event information, game specifics, medals, biometrics, and nationality. The primary goal is to visualize and analyze trends in medal distribution, athlete biometrics, sport popularity, and participation dynamics using various graphing methods.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Details](#project-details)
3. [Technologies Used](#technologies-used)
4. [Data Sources](#data-sources)
5. [Results](#results)
6. [Future Work](#future-work)

## Introduction

Understanding the history and trends of the Olympic Games can offer significant insights into the evolution of sports, athlete performance, and global participation. This project utilizes visual data analysis to explore:

- The distribution of medals across various nations.
- Trends in the age, weight, and height of athletes in different sports.
- Correlations between athlete biometrics and performance.
- Changes in sport popularity and participation over time.
- Profiles of the most successful Olympians.
- The evolving sex ratio in sports.
- The influence of host cities on participation and success.

## Project Details

### Medal Distribution Visualizations

**Packed Bubble Chart**  
The packed bubble chart represents countries with bubbles sized according to the total number of medals won. This visualization helps in identifying clusters of countries with similar medal counts and uncovering trends and exceptions.

![Packed Bubble Chart](https://github.com/disanza-franck/Olympic-Games/assets/146677173/05b3e620-473e-4f5c-8ada-802fdfd6cc3d)


**Tree Map**  
The tree map offers a hierarchical view, breaking down medals by sport categories or types. Color-coding adds a layer of information, showing the distribution of medals among countries and providing a comprehensive view of competition dynamics.

![Tree Map](https://github.com/disanza-franck/Olympic-Games/assets/146677173/37c89e37-b822-4df3-bd5e-a38fe6e28fce)


### Athlete Biometric Trends

**Age and BMI Evolution Graphs**  
These graphs use a combination of shape graphs and average lines to show the spread of age and BMI for each Olympic edition. The color-coding indicates athlete performance, represented by medal counts. This visualization allows analysis of individual games as well as trends over time.

![Age Evolution Graph](https://github.com/disanza-franck/Olympic-Games/assets/146677173/7886da6a-de64-450d-bc44-b73b99675314)

![BMI Evolution Graph](https://github.com/disanza-franck/Olympic-Games/assets/146677173/4d41b5a4-f71e-4a82-9d1a-3c3820625eaa)


### Popularity and Participation Trends

**Line Graphs and Bar Graphs**  
Line graphs effectively illustrate changes in sport popularity over the years, with smooth lines highlighting patterns and abrupt changes. Bar graphs, on the other hand, are used to show medal counts and participation rates per host country, providing clear comparisons and insights.

![Line Graph](https://github.com/disanza-franck/Olympic-Games/assets/146677173/fef927ad-bfc5-4d26-8ef6-88c554467c4a)

![Bar Graph](https://github.com/disanza-franck/Olympic-Games/assets/146677173/004da263-cd3e-4f3a-9de1-3ba8f08aca51)


## Technologies Used

- **Python**: For data analysis and preprocessing.
- **Tableau**: For creating interactive and detailed visualizations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For additional graphing capabilities.

## Data Sources

- **Olympic Dataset**: The dataset includes 120 years of Olympic data and is obtained from [kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).

## Results

The visualizations generated in this project provide valuable insights into the historical trends and patterns of the Olympic Games. They help in understanding regional differences in performance, changes in athlete characteristics, and shifts in the popularity of various sports. These insights are crucial for researchers, sports enthusiasts, and policymakers.

## Future Work

While Tableau has been effective for visualizations, it has limitations in handling complex calculations. Future work could involve integrating Python for more advanced data analysis, enabling deeper insights and more dynamic visualizations. This integration could enhance the responsiveness and interactivity of the visualizations, making the data exploration process more engaging and informative.
