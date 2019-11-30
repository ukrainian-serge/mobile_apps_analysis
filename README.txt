# Profitable App Analysis

`./profitableApps.ipynb` : NO pandas. All old school data wrangling using python to build functions for work.
`./profitableAppsVisualization.ipynb` : Using pandas, matplotlib, etc, to visualize.

---

A brief dive into the profiles of apps offered at Apple App Store and Google Play Market to ascertain profitablilty potential of apps based on chosen descriptor columns(examples: Genre, Category, user_ratings, Installs, etc.,). 
Primary Focus will be on free/ad-revenue apps. Python3+ with csv module will be used in this analysis. A step by step notation will precede code used to manipulate these data sets.



#### Data sources:
- Android Kaggle data-set of approximately ten thousand Android Google Play apps - August 2018.
- iOS Kaggle data-set of approximately seven thousand Apple Store apps - July 2017.

#### Data questions/answers:
- Cleaning incompatible and wrong data
- Removing duplicate entries
- Removing Non-English Apps
- Isolating Free and English Apps
- Most Common Apps by Genre
- Most Popular Apps by Genre on the App Store