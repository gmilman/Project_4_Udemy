## Clean data
- removed one record with mostly null values
- data otherwise seems very clean
- clean up data to year only
- include encoding for the levels
## Data Exploration

categorise price and course length

- 19 - heatmap of all variables except course title, course id, subject and url) -gm

simple stuff:
  - yunke
  - DONE 22 - boxplot of price - to determine categories: free (0), low-price (20-44), mid-price (45-95), high-price (>95) 
  - 7 bar - histograms of content duration (mplt) 
  - 8 bar- histogram year published (sns)
  - 15 bar - course level - sum of all subscribers
  - 16 bar - course level - average price (matplotlib - stem)
  - 17 - step chart (matplot lib) n. subscribers per year
  - Gemma
  - 9 boxplot - duration,
  - 10 violin- n_lectures
  - 11 pie- levels 
  - 20 - number of courses published per year (line)
  - 21 - avg price of course per year - box plot type thing
  
 multiple series charts... 
    - 13 bar - year vs price category (categorise the prices)(grouped) - gm
    - 14 bar - level vs price categories (stacked) - yunke

Regression analysis on (scatter)
- gm
  - 1 price vs number of subsribers -
  - 2 price vs number of subsribers vs duration since published (3D charts)

-yunke
  - 3 rating vs course duration / number of lecturs
  - 4 rating vs num subscribers
  
  gm
  - 5 multi var - number of sub, number of lectures and content duration (3D or radar)
  - 6 linear - number of coursers per year
  
  yunke
  - 12 radar - price, n-subscribers, n-rating, duration, number_lecturs
  - 18 facetgrid - price category vs rating
 
   
  
   
  - if time... analyse course names, via string and count and then do bubble plot to show frequency, - or bar chart for simplification
