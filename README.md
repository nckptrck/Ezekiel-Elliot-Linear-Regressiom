This project attempts to predict Ezekiel Elliots yards per carry based on his total amount of career touches (rushing attempts and receptions) from 2016-2022. A linear regression model was created predicting yards per carry based on the total amount of career touches Elliot had up to that point.

It is important to note that this was predicted on each game, rather than each individual attempt/touch.

All data was scraped from pro-football-refrence.com, combined and cleaned by myself. Regular season data is labeled 'Zeke-RS.csv', and playoff data is labeled 'Zeke-Playoffs.csv'

R packages used include tidyverse (cleaning/ visualizing data), readxl and here (reading csv files in), knitr, broom, and kableExtra (creating tables).


