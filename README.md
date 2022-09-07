# Exploring-Intl-Debt-Using-PostgreSQL

![Debt Bomb](https://user-images.githubusercontent.com/112103910/188953901-e369b678-dae6-4406-bf30-aa57388aefd8.jpg)

## Leveraging aggregate functions and aliasing in PostgreSQL to investigate international debt. 

Load and inspect data for topics that were hot worldwide (WW) and in the United States (US) at the moment of query — snapshot of JSON response from the call to Twitter's GET trends/place API. Convert pesky JSON data into usable data frames for easier analysis. Influencers were also analyzed to identify the impact of their retweets on their follower base for spreading the trending topics.

## Methods/Functions/Packages/Skills

* json[loads(), dumps(), open()]
* pandas
* collections
* matplotlib.pyplot

## Files

Intl_Debt.ipynb - Jupyter Notebook displaying SQL queries written in Python and markdown comments.
international_debt.csv - Raw Data leveralged by SQL
international_debt.sql - SQL file
