# Airbnb-bookings-analysis-Python

# **About Airbnb**

Airbnb is a platform that allows people to rent out their homes or spare rooms to travelers as a form of accommodation. Founded in 2008, Airbnb has grown rapidly and is now available in over 220 countries and regions around the world. The company aims to provide a unique and personalized travel experience for its users by offering a variety of lodging options, from shared rooms to entire homes and apartments. Airbnb has disrupted the traditional hospitality industry by providing an alternative form of accommodation that often offers more affordable and authentic options for travelers. The analysis of data on millions of listings available on Airbnb is an essential aspect for the company.

# **Dataset Link**
https://www.kaggle.com/code/upadorprofzs/understand-your-data-airbnb-reservations/input?select=AB_NYC_2019.csv

# **Project Summary -**

The Airbnb NYC 2019 dataset consists of information on 48,895 Airbnb listings in New York City, and the main objective of this project was to conduct an EDA of the dataset to obtain valuable insights into the Airbnb market in the city. To accomplish this goal, the EDA was divided into two primary phases: data cleaning and preprocessing, and exploratory analysis.

The first stage involved identifying and addressing missing or inconsistent data, eliminating irrelevant variables and outliers, and ensuring that the data was appropriate for analysis. Following the data cleaning and preprocessing, the exploratory analysis was carried out, which involved examining the variables' distribution, identifying patterns and relationships between variables, and using visualizations to obtain insights into the Airbnb market in New York City. This process revealed some interesting findings, such as the most popular neighborhoods, the most common room types, the average price of listings in different neighbourhoods etc.

The report presented the EDA insights and recommendations for both Airbnb hosts and the company. The recommendations for hosts in high-demand neighborhoods suggested they offer discounts to gain a competitive edge, while those in less popular areas should consider lowering their prices or providing more significant discounts to attract more guests.

This project demonstrated the importance of data analysis in comprehending and enhancing business performance. Through analyzing the Airbnb NYC 2019 dataset, valuable insights were acquired, which could be used by Airbnb hosts and the company to make correct decisions. The project emphasizes the potential of data analysis to improve business performance and highlights the significance of making data-driven decisions.

# **Problem Statement**

**Airbnb dataset is used to understand the factors that impact booking rates and customer satisfaction, in order to identify areas for improvement and optimize revenue.**

# **Business Objective**

Business objective for performing an exploratory data analysis (EDA) on the Airbnb dataset is to identify opportunities to improve the user experience and drive revenue growth. By analyzing patterns and trends in the data, the company can gain insights into customer preferences and behaviors, as well as identify potential areas for improvement in terms of pricing and availability. This information can inform strategic decisions around marketing, product development, and service enhancements to ultimately increase bookings, customer satisfaction, and profitability.

# **Conclusion**



1.  The properties with the names Hillside Hotel, Home away from home, and New york Multi-unit building are the top 3 most listed properties according to property name.
2.   The top 5 host who have maximum listings are Michael, David, Sonder, John, and Alex.
3.   The most number of properties listed are present in Manhattan and Brooklyn followed by Queens, Bronx, and Staten Island.
4.   No. of properties in Manhatten(highest) are 5702% higher than staten island(least).
5.   The neighbourhood with most properties listed are Williamsburg and Bedford-Stuyvesant followed by Harlem, Bushwich, and Upper West Side.
6.   Manhattan has the highest density of properties.
7.   Entire home/apt is most preferred type of room by customers followed by Private room, and Shared room.
8.   Entire home apt(highest) has 2095% higher properties than shared rooms(least).
9.   Most number of properties fall in the category of medium price property, followed by few properties in low price category and very few properties are in high price category.
10.   Few properties have recieved large number of reviews whereas a lot of properties have recieved very few reviews as low as 1.
11.   There are many properties which have not been reviewed from 2011 to 2017. Most of the properties have been reviewed in year 2019.
12. Only 72% of the total properties have recieved any review in the last year i.e 2019.
13.   Sonder is the best host corresponding to neighbourhood_group Manhattan according to number of properties handeled.
14.   Sonder is the best host corresponding to room type Entire home/apt. Followed by David for Private room and Sergii for shared room. If a customer requires Entire home/apt in Manhatten, Solder should be recommended to customer.
15.   Michael is the best host corresponding to room type Medium. Followed by Kazuya for Low and Henry for High. Michael is also the best host in Brooklyn. So, if a customer want properties in Brooklyn in the medium price category then Michael should be recommended.
16.   Michael is the best host in terms of the total number of reviews recieved by him followed by David, and John.This makes sense because Michael is also the best host in Brooklyn based on the number of properties handeled by him. Since he handeles a lot of properties so he can have highest total number of reviews.
17.   Dona is the best host in terms of the average number of reviews followed by Asa, and Dennis & Naoka.Dona is the best host in terms of effectively handling a property.
18.   Manhattan has highest number of properties listed as room type Entire home/apt followed by Brooklyn for room type Private room. The shared room is least in number for all the neighbourhood groups.
19.   When comparing the number of properties for low price category with respect to total number of properties for a respective neighbourhood group, Manhatten has least number of properties for low price category. Also it has the highest number of high price category in all neighbourhood groups. This shows that Manhatten is the costliest neighbourhood group to live in NYC.
20.   In Private room type Bedford-Stuyvesant	has highest number of properties as 2033, for Entire home/apt room type Williamsburg has highest number of properties as 1889, and for Shared room type	Hell's Kitchen has highest number of properties as 99. 		
21.   In Medium	price category Williamsburg	has highest number of properties as 3740, for Low	price category category Bedford-Stuyvesant	has highest number of properties as 661, and for High	price category Upper West Side	has highest number of properties as 18.
22.   Based on average price Fort Wadsworth is the most costliest neighbourhood in all of the neighbourhood followed by Woodrow, Tribeca, Sea Gate, and Riverdale.
23.   Based on average price Bull's Head is the least costliest neighbourhood in all of the neighbourhood followed by Hunts Point, Tremont, Soundview, and New Drop.
24.   Neighbourhood Fort Wadsworth(Highest) has 1590% higher average price than Bull's Head(least).
25.   Based on average number of reviews Silver Lake is the most reviewed neighbourhood in all of the neighbourhood followed by East Elmhurst, Richmondtown, Elitingville, and Mount Eden.
26.   The heatmap and pairplot indicate that there is no significant correlation between the numerical columns of the dataset. The values in the numerical columns appear to be independent of each other and not strongly related to the values in the other columns.
27.   Overall, the Airbnb NYC 2019 dataset provides valuable insights into the short-term rental market in New York City. The dataset can be used by hosts to better understand their competition and adjust their pricing strategy, improve occupancy rate, and enhance customer experience.


## **Solution to Business Objective**

Based on the insights gained from the EDA of the Airbnb NYC 2019 dataset, here are some potential solutions to the business objectives:

1. Optimize Listings in High-Demand Locations
Focus on Manhattan and Brooklyn: These areas have the highest density of properties and demand. Promote listings in neighborhoods like Williamsburg, Bedford-Stuyvesant, and Harlem, which already attract significant interest.

Highlight Unique Selling Points: For Manhattan properties, emphasize luxury and exclusivity since it is the costliest neighborhood. For Brooklyn, focus on affordability and vibrant culture.

2. Prioritize Entire Home/Apt Listings
Since "Entire home/apt" is the most preferred room type (2095% higher than shared rooms), prioritize marketing and maintaining these listings. Ensure these properties are well-furnished and provide privacy to meet guest expectations.

3. Dynamic Pricing Strategies
Adjust Prices Based on Demand: Use dynamic pricing tools to optimize nightly rates based on local demand trends, seasonality, and competitor pricing.

Leverage Medium Price Category: Most properties fall into the medium price range, which aligns with guest preferences. Keep competitive pricing while offering added value to stand out.

4. Improve Guest Experience
Enhance Amenities: Add sought-after features like pools, hot tubs, or outdoor kitchens for premium listings. For budget-friendly options, include thoughtful touches like high-quality linens or welcome baskets.

Offer Unique Experiences: Collaborate with local businesses to offer curated experiences such as guided tours, cooking classes, or cultural activities. This can justify higher rates and attract more bookings.

5. Increase Occupancy Rates
Fill Unoccupied Nights: Promote listings through social media, Google ads, and cross-promotion with local businesses to attract more guests.

Target Underutilized Properties: Focus on properties that have received few or no reviews (e.g., those inactive from 2011–2017). Offer discounts or promotions to encourage bookings and generate reviews.

6. Leverage Top Hosts’ Expertise
Promote hosts like Michael (Brooklyn) and Sonder (Manhattan) who manage a large number of properties successfully. Highlight their expertise in managing entire homes/apartments or medium-priced listings to build trust with potential guests.

7. Encourage Reviews
Since 28% of properties lacked reviews in 2019, incentivize guests to leave reviews by offering perks like early check-ins or small gifts. Positive reviews will boost visibility and credibility.

8. Diversify Property Offerings
Expand listings in underserved categories like shared rooms or low-price properties in neighborhoods where demand exists (e.g., Bedford-Stuyvesant for low-price private rooms). This can capture budget-conscious travelers.

9. Promote Costly Neighborhoods Strategically
For high-end neighborhoods like Fort Wadsworth, emphasize exclusivity and luxury experiences to attract affluent travelers willing to pay premium prices.

10. Partner with Local Businesses
Collaborate with restaurants, tour operators, or event organizers to create bundled packages (e.g., discounted meals or guided city tours). This enhances guest experience while generating additional revenue streams.

By implementing these strategies tailored to the insights provided, Airbnb hosts can maximize occupancy rates, enhance guest satisfaction, and significantly increase revenue potential.
