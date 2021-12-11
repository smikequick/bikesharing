# NYC Citibike Bikesharing

![Pictures of bikes](https://miro.medium.com/max/4096/1*GJ45uUnc49T-D5LdYn7CfQ.jpeg)

## **Overview of Analysis**

### ***Purpose***
A key stakeholder in Des Moines is interested in investing in the bikeshare business based on data models from New York City. This analysis serves as a proposal to bring the bikeshare business to Iowa and to reflect on what is successful in NYC and what could be improved in Des Moines.


## **Results**

The first visualization generated illustrates the checkout time for users. This indicates that most users are riding a bike for approximately 5-10 minutes. Based on this data, the assumption could be made that bikes are used for relatively short trips.

![Checkout Times for Users](https://user-images.githubusercontent.com/87885677/145687463-a14e3f9d-2b6f-48e0-a758-28641b1f0900.png)

<br>

Next, a pie chart was created to indicate who typically uses the bikeshare system to ride within New York City. The data indicates it is primarily male dominated.

![Gender Breakdown](https://user-images.githubusercontent.com/87885677/145687470-55278e07-6a69-48f9-835e-96d031e6c0ee.png)

<br>

Third, using the gender data above, further information was gathered regarding checkout times. There is no surprise here that checkout times overlapped with gender indicated that each group tends to checkout bikes for the same approximate amount of time (5-10 minutes) across all bands.

<br>

![Checkout Times by Gender](https://user-images.githubusercontent.com/87885677/145687503-e9ca2d59-6777-4791-a6f9-87ae8daf515f.png)

<br>

Additionally, it's intriguing to leverage a heat map to better understand when bikes tend to be checked out. The below heat map indicates many bikes are checked out in what could be identified as the morning and evening commute times (i.e. ~6:00am to ~9:00am and ~5:00pm to ~7:00pm, respectively).

<br>

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/87885677/145687509-b7141442-6a84-4c62-b9c7-262c735e8fdf.png)

<br>

From here, it naturally make sense to see if the same pattern exists across gender. The heat map below indicates that it does.

<br>

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/87885677/145687512-2021db9c-db1d-49ba-ba1a-d37f733f427d.png)

<br>

Changing gears a bit, a pie graph indicates who tends to ride with Citibike. The data indicates more than 75% of riders are subscribers, with repeated rides while less than 25% are non-subscribers, or customers.

<br>

![Customers](https://user-images.githubusercontent.com/87885677/145687515-06891b03-ccfe-499c-ac9a-112aa33ec03c.png)

<br>

Additionally, breaking down that data by gender and weekday further illustrates an interesting pattern. Subscribers appear to be further identified by gender, presumably because of the process of signing up to be a part of Citibike. Further, it seems that subscribers ride almost every day of the week, but more so are commuters to work whereas customers appear to ride slightly more on the weekends indicating likely tourism.
<br>

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/87885677/145687517-42e317de-1852-43ee-99fe-de17c122734c.png)

<br>

## **Summary**

Based on the analysis of Citibike bikeshare data, it appears that subscribers who are male tend to ride the most in New York City, particularly during morning and evening commute times. There are two additional recommendations for further analysis. 

First, upon a deeper review of age and gender, it makes sense to better understand why riders that are born in the early '90s are much more active in using the bikeshare system. Further questions arise regarding why other age groups do not ride nearly as much as this one.

![Rider Count by Birth Year and Gender](https://user-images.githubusercontent.com/87885677/145687519-1c24d3b1-3f20-4d2a-be52-fd63d4a674b2.png)

<br>

Second, what marketing techniques can be used to convert customers to subscribers? Additionally, what analysis can be conducted to further understand which customers are visiting NYC and which customers live in NYC and therefore can be converted to a subscriber?

![Number of Rides by Customer Type](https://user-images.githubusercontent.com/87885677/145687527-f88c5a10-c70e-41ec-a96a-9e824d174bc3.png)

Tableau Workbook located here: https://public.tableau.com/views/NYC_Citibike_Challenge_16392494994830/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link 
