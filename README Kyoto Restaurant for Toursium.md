<h1>Group 5 Project - Kyoto Restaurant for Tourism</h1>
Our project is analysis Kyoto Top rate Restaurant to recommend for Tourism. The analysis will provide lunch and dinner price, rating, Category and review number.<br>
The group project have 4 peoples work together, group member name: Diana, Zahra, Gavin and Victor.<br>
We designed to make Clean dataset together and we separate 3 different analysis for our group member to work.<br> 
File location under Clean Kyoto Data Frame/clean.ipynb<br><br>

**Job list for Group member duty:**
<ul>
  <li>Diana - rating vs review number chart, convert Yen to US dollar and compare average and Review by category.</li>
  <li>Gavin - map for rating and review number location, create Price range question for Tourism setup dinner and lunch price range.</li>
  <li>Zahra - create counting Restaurant chart, Average for category chart, Collect group member idea and write Analysis and Conclusion</li>
 
</ul>
We will provide a slide show presentation for our Tourism to understand our project and analysis.<br>
<br>
<h1>Kyoto Restaurant Analysis and Conclusion</h1><br>

**Introduction**

For data analytics and visualization, our group chose to look at a dataset from restaurants in Kyoto. This dataset had included price range, customer ratings, review numbers, exact location by coordinates, and the cuisine type for each restaurant. We thought it would be interesting to assess all of these different parameters to find out which restaurants in Kyoto were the most popular and explore the reason for this. We also wanted to compare the price range with ratings and review numbers to see how this had an impact on customer choice.

**Analysis**

In order to reach our goals and assess the data in a more tangible way we used a variety of coding and visualization techniques. When we were looking at the first and second categories, we noticed that there was too much variety in terms of restaurant type and cuisine style. In order to analyze this section of the data, we decided to limit categories to three regions. We decided to name these bigger categories Asian, European, and American stye cuisine. We used a search index in pandas to look for key words which would classify each restaurant into one of three categories.
Another issue we had was that many restaurants in the data set did not include a price range for their lunch. We took this to mean that these restaurants do not offer lunch. This is not ideal to include in a dataset that should be manipulated for customers. As a result, we excluded any restaurants that did not include the lunch price. 
The original dataset had given us the price range in Japanese Yen, which made it hard for us to get a sense of food pricing in Kyoto. To resolve this issue, first we split the cells into lowest price and highest price, then we converted the Yen to United States Dollar (USD). 
Our next step was to compare customer ratings and review numbers to categories. First we counted and calculated the percentage of each restaurant region to see what was most popular. Then, we used the ‘groupby’ function to calculate the count, some, mean, minimum, and maximum of review numbers for each category. We used the same function for comparing the regions to average customer rating. 
Another thing we wanted to know was how competitive the restaurants were in terms of their prices. To determine this, we used the ‘groupby’ function again and we looked at the count of restaurants that had the same prices for dinner and/or lunch. Moreover, we ordered from lowest price to highest price. This can help business owners when they are assessing their profit margins and if it is worth it for them to continue keeping their prices as the status quo. It also helps customers when they want to decide whether or not Kyoto is a suitable place to travel to and eat out comfortably. 
