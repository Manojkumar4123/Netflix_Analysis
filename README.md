Netflix Data Analysis Using Power BI
Project Overview
This project analyzes Netflix content and customer viewing behavior to
generate meaningful business insights. The analysis focuses on content
popularity, customer engagement, subscription preferences, ratings,
genre trends, and country-wise viewing patterns.

The goal is to turn the Netflix datasets into clear, interactive visual
insights that can support content and subscription strategy decisions.
Project Objectives
- Identify popular movies and TV shows using customer watch time and
  ratings.
- Understand customer demographics and audience preferences.
- Compare engagement across Basic, Standard, and Premium subscription
  plans.
- Explore content ratings and their relationship with viewer behavior.
- Analyze genre popularity across countries.
- Study content additions and release-period trends.
- Derive insights that can help improve Netflix's content strategy.
Tools and Technologies
- Microsoft Excel -- Data checking, cleaning, and preprocessing.
- Microsoft Power BI -- Data transformation, analysis,
  visualizations, and interactive dashboard creation.
- CSV -- Source data format.
Datasets
The project brief describes two CSV datasets:
1. Netflix Shows Dataset
Contains information about movies and TV shows.

  Column           Description
  show_id        Unique identifier for each movie or TV show
type           Content type: Movie or TV Show
title          Title of the content
director       Director name, where available
cast           Main cast members
country        Country where the content was produced
date_added     Date the content was added to Netflix
release_year   Original release year
rating         Content age-rating category
duration       Movie duration or number of seasons
genre          Genre or content category
2. Netflix Customer Ratings Dataset
Contains customer details and viewing/rating activity.
  Column                              Description
  customer_id                       Unique customer identifier

  show_id                           Identifier linking the customer
record to Netflix content

  customer_name                     Customer name

  age                               Customer age

  gender                            Customer gender

  country                           Customer's country

  subscription_type                 Basic, Standard, or Premium

  watch_time_minutes                Total viewing time in minutes
rating                            Customer rating on a 1--5 scale
The show_id field is the linking field between the two datasets.
Project Workflow
1. Data inspection -- Review the source CSV files, columns, data
   types, and data consistency.
2. Data cleaning -- Check missing values in fields such as
   director, cast, and country; standardize date_added; and validate
   rating categories.
3. Data transformation -- Prepare fields and categories needed for
   analysis.
4. Data analysis -- Explore content performance, customer
   demographics, subscriptions, ratings, genres, and country-level
   patterns.
5. Dashboard development -- Build interactive Power BI visuals and
   slicers.
6. Insights and recommendations -- Summarize findings and identify
   possible business actions.
Analysis Areas
The project brief identifies the following analysis areas:
- Top 10 most-watched movies and TV shows.
- Movie versus TV Show watch-time comparison.
- Genre popularity by country.
- Customer rating distribution and average ratings by genre and
  country.
- Recently added content versus older content.
- Subscription-plan market share and engagement.
- Customer retention and repeat-viewing patterns.
- High-rated versus low-rated genres and content types.
- Director and cast influence on ratings.
- Country-level content localization opportunities.
- Monthly content additions and rating patterns.
- Customer engagement dashboard with country, age-group, and
  subscription slicers.
- Competitor benchmarking simulation.
Expected Deliverables
- Interactive Power BI dashboard.
- Cleaned Excel datasets, if required.
- Presentation containing key insights and recommendations.
- Business report summarizing the findings.
Notes and Limitations
- This README is based on the supplied project brief.
- The project brief describes the dataset structure and intended
  analysis; actual findings, KPI values, and dashboard results should
  be added only after validating the data and completed Power BI
  report.
- The brief mentions watch time and customer ratings as analysis
  measures. Use the fields available in the supplied datasets and
  avoid presenting unsupported metrics as actual Netflix company-wide
  figures.
Project Domain
Entertainment, Media, and OTT Analytics
Author
E.manoj kumar
