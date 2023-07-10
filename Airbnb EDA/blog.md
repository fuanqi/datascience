As someone who works remotely, I've always wanted to work from Seattle for an extended period of time. But deciding where and when to go is always a tricky question for me. 
* How are Airbnb supplies in each neighbourhood?
* What are the different vibes for different neighbourhoods? 
* How the airbnb listings are priced? 
* What affects the price?

Here we are taking the public data for Seattle Airbnb in 2016 to get an idea. 

# Airbnb Supply 
![picture 1](../images/f979a101d1b976d941fc4d9f3a82a18536f5f78ae7bb463b677468f86905cfb2.png)  

When it comes to Airbnb homes, Broadway has the most options. There are ~400 listings available at the market in 2016. Roxhill, on the other hand, has the least options. 

![picture 3](../images/f8b9d4489cf9559c3ff0e3ccb9fb9440c04a10cccb1557039db9d36f884e6919.png)  
If considering South Lake Union neighbourhood or Dunlap, you need to book fast, as most of the Airbnbs are booked out early. 

# Vibes of different neighbourhood
![picture 8](../images/6c89ff010f82424035051af0cfca10081ac3dd59e115df7f082922a7e6fc9123.png)  
Each neighbourhood has its own vibes. This is a word cloud plotted based on neighbourhood descriptions on Airbnb. 
For example, visit Ballard for farmers market. Go to Capitol Hill, University District, Central Area for restaurants and coffee shops. 

# Prices
![picture 5](../images/7330be4001b23127e9f841f503e60a4b0b619f1b48b3ce6e91070eb540b88e79.png)  

Price diffs quite a lot in different neighbourhoods. The most expensive neighbourhood is Southeast Magnolia, with average price of $231, almost 4 times the price of the cheapest neighbourhood.

![picture 4](../images/b844d33450062e1998d507d1a17d08c4b46ae75992e4892d9e3949317acf79f1.png)  

There's definitely seasonality in prices. July is the most expensive time to visit the city. In fact, prices in the second half of year is in general higher than the first half. 

![picture 6](../images/f6d31cf60f37d2697b4a35d42fed433e8ecdf394bbc8e1f2e45560f10e1258e3.png)  
The seasonality in prices is observed in all neighbourhoods, and some neighbourhoods are more sensitive than others, such as Downtown. In summer times, downtown prices are almost 50% more expensive than its low seasons. 

![picture 7](../images/7023a5f28bde795a00514ad0624ed3b20896be5728408f33001fcacb497190a9.png)  
Weekends are usually more expensive than weekdays. No surprise!

# Price Model
In order to better understand the factors impacting prices, I built a simple linear model. 

![picture 11](../images/263eb21d654968e8b4335b6009ba9c0bd682e9b64653805a6681ff8eb6ac2f0c.png)  
These are the top features impacting Airbnb price. 
* Property type: Being an Airbnb on boat has great positive impact to the price. On the other hand, if Airbnb is a Dorm, the prices are lower.
* Neighbourhood: Plays a big role in prices. Neighbourhoods like Pioneer Square, Industrial District has a positive impact on the prices. There are also neighbourhoods like South Park, that impacts the prices in the negative way.
* Room type: Shared room and private room prices are lower. 
* Bedrooms: More bedrooms, higher the price

# In conclusion:
Seattle is a great city to visit. 
* Summer season is the busiest time of the city, Airbnb prices peaks.
* Each neighbourhood has its own vibes.
* Some tips on saving money on Airbnb:
  * Avoid summer season and weekends.
  * Stay at shared or private rooms
  * Boats are expensive

