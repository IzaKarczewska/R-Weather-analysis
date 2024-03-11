# Statistics - college project
This is the Analysis of weather data for Białystok, Wrocław and Kraków in R language. All done in RMarkdown.

### Data used
[Link - Open Meteo](https://archive-api.open-meteo.com/v1/archive?latitude=53.13&longitude=23.17&start_date=1950-01-01&end_date=2022-12-31&daily=temperature_2m_max,temperature_2m_min,temperature_2m_mean,precipitation_sum,precipitation_hours,winddirection_10m_dominant&timezone=Europe%2FWarsaw)

## What has been implemented in project
* extracting data for Białystok
* Chi squared test - checking the truth about Polish proverb using our data
* extracing data for Wrocław and Kraków
* Kolmogorov–Smirnov test - changes in weaather conditions between these cities
* Data visualization of precipitation, wind conditions and temperature

### Drawning conclusions after Kolomogorov-Smirnov test
1. Kraków and Wrocław have different distribution
2. These cities have different climatic characteristics in July
