## Clean data
- removed one record with mostly null values
- data otherwise seems very clean
- clean up data to year only
- include encoding for the levels
## Data Exploration

categorise price and course length

- 19 - heatmap of all variables except course title, course id, subject and url)

simple stuff:
  - 7 bar - histograms of content duration,
  - 8 bar- histogram year published
  - 15 bar - course level - sum of all subscribers
  - 16 bar - course level - average price (matplotlib - stem)
  - 17 - step chart (matplot lib) n. subscribers per year
  - 9 boxplot - duration,
  - 10 violin- n_lectures
  - 11 pie- levels 
  - 20 - number of courses published per year (line)
  - 21 - avg price of course per year - box plot type thing
  
  - multiple series charts... 
    - 13 bar - year vs price category (categorise the prices)(grouped)
    - 14 bar - level vs price categories (stacked)

Regression analysis on (scatter)
  - 1 price vs number of subsribers 
  - 2 price vs number of subsribers vs duration since published (3D charts)
  - 3 rating vs course duration / number of lecturs
  - 4 rating vs num subscribers
  - 5 multi var - number of sub, number of lectures and content duration
  - 6 linear - number of coursers per year
  - 12 radar - price, n-subscribers, n-rating, duration, number_lecturs
  - 18 facetgrid - price category vs rating
 
   
  
   
  - if time... analyse course names, via string and count and then do bubble plot to show frequency, - or bar chart for simplification
