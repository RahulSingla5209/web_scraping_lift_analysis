# Unstructured Analysis of Edmonds.com

Scrape data from Edmonds.com and come up with insights for car reatiler on how they should position different car brands.

![image](https://user-images.githubusercontent.com/12545194/143522455-25bac7d0-eb96-4baa-af2a-9ffbe9ac1e46.png)

* [Scrapper](https://github.com/RahulSingla5209/web_scraping_lift_analysis/blob/main/web_scapper.ipynb)- Major steps done:
  * Used Selenium for scrapping Edmonds.com  
* [Lift Calculations](https://github.com/RahulSingla5209/web_scraping_lift_analysis/blob/main/lift_calculations.ipynb)- Major steps done:
  * Data Cleanup
  * Car model frequency calculation
  * Co-mentions frequnecy of car models in a post
  * Calculated lift for understanding similarity. Lift calculation = P(A, B) / P(A) * P(B)
  * Similarity graph using MDS (converted similarity scores to dissimmiarity scores)
  * Insights - Japanese brands have closer association compared to German Brands (Check nb for more details)
  * Attributes and their co-mentions with car brands

## MDS Graph
<img width="316" alt="image" src="https://user-images.githubusercontent.com/12545194/143520984-0a8dfdeb-4fab-4664-83a6-9d51bf935b4c.png">

## Most Aspirational brand - Lift with words like Aspiration
<img width="312" alt="image" src="https://user-images.githubusercontent.com/12545194/143521048-bb324f04-0694-4f18-94e2-61e18e84a3a5.png">
