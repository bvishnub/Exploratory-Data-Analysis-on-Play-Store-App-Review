# Exploratory-Data-Analysis-on-Play-Store-App-Review

                                         
![google play](https://github.com/bvishnub/Exploratory-Data-Analysis-on-Play-Store-App-Review/assets/169208781/c6c3319c-bff0-4588-b8ad-0f4041c6b44e)

The Android app market is growing rapidly and becoming more competitive, with developers constantly releasing new apps. To succeed, developers need to target specific user segments based on their behavior. User ratings, which reflect satisfaction, are a key performance indicator for making decisions. The aim of the project is to analyze the play store app and user review data to come up with actionable insights which can help developers to work on and capture the android market leading to app making business a success.

## Table of Contents

- [Objectives](#objectives)
- [Data Sets](#data-sets)
- [Built With](#built-with)
- [Steps Involved For Analysis](#steps-involved-for-analysis)
- [Key Findings And Implications](key-findings-and-implications)
  


### Objectives
- To come up with the actionable insights by deep diving into data and performing analysis.
- Understanding the app download trends based on Categories , Age groups , Paid or Free, Genres , sizes and all.
- Understanding App Ratings and Reviews pattern and understanding the sentiment of the users for better quality apps development.
- To find out the appt features and attributes for app development business ensuring positive response and maximum downloads at consumer end leading to high revenue.

### Data Sets 
- There are two data set Play Store Data and User Review Data, provided by AlmaBetter Team.
- **Play Store App Dataset Variables :**
  -   **App** - Name of the application.
  -   **Category**- App category and categorical in nature.
  -   **Reviews** - Count of reviews for the app and categorical in nature and 55% unique value, needs to be converted to numerical.
  -   **Size** - stands for size of the application in MB and KB , need to be converted to numerical.
  -   **Installs** - total number of downloads of respective app, need to converted to numerical.
  -   **Type**- Free or Paid distinguish among app.
  -   **Price** - Instalation charges,needs to be converted to numerical.
  -   **Content** - which age group can download the app - categorical in nature.
  -   **Genre** - Genre of the app.
  -   **Last Updated** - Date when app was last updated needs to converted to datetime.
  -   **Current Ver** - current version of the app.
  -   **Android Ver** - Android version required to download the app.
  -   **User Review Dataset Variables :**
  -   **App** -Name of the application.
  -   **Translated_Review** - Transalation of the review given by customer about the application
  -   **Sentiment** - Sentiment of the consumer +ve , -ve or neutral.
  -   **Sentiment_Polarity** -Polarity of the review and range is [-1,1]
  -   **Sentiment_Subjectivity** - Range is [0,1].Helps in understanding whether the feedback is based on personal preferences or factual issues.


### Built With 
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab


### Steps Involved For Analysis
- Dataset Inspection.
- Removing duplicates.
- Handling Missing Values.
- Dealing with outliers.
- Exploratory Data Analysis- Analyzing basic trends , relationship in the data and generating summary statistics and visualizing the same with specific charts plots for better understanding.


### Key Findings and Implications 
### -  Top App Categories:
- **Findings**- Family, Games, Tools, Business, Communication categories are mostly downloaded , also having good rating above 4 and good count of reviews.
- **Suggestions**- These category apps are majorly downloaded and same can be considered for acquiring new consumers.

### -  Free Vs Paid:

- **Findings** - Free applications are downloaded majorly by consumers with a whole percentage of 99.9%.
- **Suggestions** - Apps should be developed under free section and for paid section prize should be kept below 10$.

### - Genre:

- **Findings**-Communication , Tools, Productivity , Social ,Photography are the most preferred and downloaded at consumer end. Under Games Category - most downloaded apps are under Genre -arcade, action ,casual, Racing ,puzzle.
- **Suggestions** - Developers should focus on developing apps under above mentioned genres.

### - Content Rating:

- **Findings** - Everyone age group have the most number of installs with 69.5%.
- **Suggestions** - Everyone age group should be considered for developing new app , increasing the audience count.

### - Size of App :

- **Findings** - Consumers tend to download small apps ,and here size group 10-19 MB was majorly installed. For paid section installs were also for 90-100mb and 20-29 mb .
- **Suggestion** : App should be light weight with good quality and size should be between 10-19 MB.

### - Android Version :

- **Findings** - 52% downloads was for Android Version - Varies with Device and 43.5% downloads for Android version 4 and above.
- **Suggestions** - Developer should consider android version which varies with the device of above 4 to develop apps.

### - Paid Apps :

- **Findings** 

  -  Most revenue generated Category is Family (46.2%) , Lifestyle (23.4%) and game (16.55%) allover.
  -  Most revenue generated Genres are Arcade Action and adventure (35.8%),Lifestyle(29.5%) and Action 15.9%.
  -  Minecraft is most revenue (47.6%) generated app in play store.
- **Suggestions** - Developers should focus in Family ,Lifestyle and Games with genres Arcade Action and Adventure , Lifestyle and Action for developing paid apps in case with everyone Age Group.

- **Findings**-

  -  Google News , Maps - Navigate & Explore , Google Street View , YouTube, Google Play Movies & TV ,Google+ ,Instagram , Facebook , Google, Google Play Books are top 10 most installed apps in play store.

  -  ColorNote Notepad Notes, Calorie Counter-Macros, Family Locator - GPS Tracker,Calorie Counter - MyNetDiary, 8fit Workouts & Meal Planner are top 5 most +ve sentiment apps.

  -  Overall Sentiment is 64% Positive , 21.3% Negative , 14.7% Neutral.

  -  Based on sentiment - Game, Health and Fitness , Family , Tools, Finance are the top 5 categories with maximum +ve sentiment received from consumer end with age group that of Everyone.

  -  Based on Ratings and Reviews - Timely Updates needs to be rolled out to improve the performance and quality of the app and to keep the consumer engaged, considering the reviews leading to improvement in Average rating.



  
