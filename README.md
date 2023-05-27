# Capstone-Project-1--AirBnb-Booking-Analysis
Project Type - EDA
Contribution - Individual
Team Member 1 - Syed Junaid Ali

**Introduction**
Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia. Airbnb is a shortened version of its original name, AirBedandBreakfast.com. The company is credited with revolutionizing the tourism industry, while also having been the subject of intense criticism by residents of tourism hotspot cities like Barcelona and Venice for enabling an unaffordable increase in home rents, and for a lack of regulation.

**Problem Statement**
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more. This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.
Explore and analyze the data to discover key understandings.

![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/c0d2289f-0b86-42b9-a2f5-d72f0b277b5d)

**Business Objective and their solutions**
1) **Which are the most expensive and cheepest locations to live in NYC ?**

   Manhattan is the most costliest place to live in, having price more than 140 USD followed by Brooklyn with around 80 USD on an average for the listings.
   Queens, Staten Island are on the same page with price on listings.
   We can see that Manhattan has the highest(the costliest) average of price ranging to ~150dollars/day followed by Brooklyn Queens and Staten Island have same    average price/day, while Bronx comes out to be the cheapest neighbourhood group in NYC.
   From my point of view It is more profitable to add hosts who have more properties in Manhattan, however manhattan is the most expensive location with higher    property tax as well but people likes to stay in mahattan as it is the economical and cultural hub.
   
2) **What are the top most areas in NYC in terms of average price of Airbnb listings ?**

   Among the top neighbourhoods in each neighbourhood groups,Fort Wadsworth from Staten Island is on the top followed by Sea Gate origins from Brooklyn,          Riverdale from Bronx , Tribeca from Manhattan and Neponsit from Queens.
   I think AirBnb should have to reduce the price of Fort Wadsworth in Stalen Island.It could be good for business point if view.
   
3) **What are the price range of room types in different neighbourhood_group ?**

   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/eefad8a8-73e4-4a09-b4b2-efc20f838887)
   Looks like a property with Entire home/apt as room_type having the highest price range at NYC followed by private rooms.

   Manhattan has the highest price for room types with Entire home/apt ranging to nearly 240 USD/night, followed by Private room with 110 USD/night. And it's      being the most expensive place to live in!

4) **What are the average of nights in which people likes to stay in each room type ?**

   Looking at these it clearly indicates that people mostly prefer living in an entire home/apt on an average of more than 8 nights followed by guests who        stayed in shared room where average stay is 6-7 nights.

   In this criteria we found private rooms is on least where average stay is 5-6 nights.
   
5) **List top 10 reviewed listings in NYC ? How monthly reviews varies with room types in each neighbourhood groups?**

   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/15e76b5a-b586-43de-ad02-e30b2e08891f)


   So, these are the listings which are having highest number of reviews, the highest being: 'Enjoy great views City in our Deluxe Room!' with 58 reviews/month    followed by 'Great Room heart of Times Square!' with a total of 27 reviews/month. Top 2 are from Manhattan so we can decide the best suited place for a        comfortable stay but the prices are high to afford.
   We can see that Private room recieved the most no of reviews/month where Manhattan had the highest reviews received for Private rooms with more than 50        reviews/month, followed by Queens in the chase.

   Manhattan & Queens got the most no of reviews for Entire home/apt room type.

   There were less reviews recieved from shared rooms as compared to other room types and it was from Staten Island followed by Bronx.
   
6) **Find the top most reviewed hosts on the basis of number of reviews and reviews/month?**

   Nalicia is the host who got more than 1000 number of reviews which is highest in NYC followed by Danielle , Brent , Lakshmee and Louman.
   Louman is the most reviewed host with more than 20 reviews/month on an average.
   
7) **Who is the most valuable host of NYC listed on AirBnb?**

   So, Sonder(NYC) leads the most valuable host in NYC with around 327 properties listed followed by Blueground and Michael.

   Also, all 3 of them has their listings on Manhattan.
   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/fd8771e0-0d59-4818-8d21-8babd82828e1)
   Sonder (NYC), Michael, Kazuya, Vie and and Amarjit are the hosts with most no of listings in each neighbourhood groups in entire NYC!
   
8) **Who is the most expensinve host in NYC ?**

   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/887379c4-2711-4ac3-a05e-fa5fcbc409e2)

   Erin in Brooklyn , Jelena in Manhattan and Kathrine in Queens are the host who has the same most expensive average price of 10000 USD/night in NYC before      removing outliers followed by Alissa in Stalen Island and Kathy in Bronx.
   
   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/b29f8241-1435-4f6b-9264-4a0bc532d0ad)
   
   Cullen in Brooklyn and Mel in Manhattan are the host who have the most expensive average price of 333 USD/night in NYC after removing outliers.
   
9) **Distribution of AirBnb listings accross neighbourhood groups in NYC.**

   ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/60106ac2-a7d9-408d-ba35-17e29775048c)

10) **Distribution of rooms types accross NYC.**

    ![image](https://github.com/Alisyed098/Capstone-Project-1--AirBnb-Booking-Analysis/assets/134094832/1b48cfc1-d76c-4be9-b3a2-e538811e05c8)
    
    95% of the listings on Airbnb are either Private room or Entire/home apt. Very few guests had opted for shared rooms on Airbnb.
    Also, guests mostly prefer this room types when they are looking for a rent on Airbnb as we found out previously in our analysis.
    
 **Conclusion**
 From all the analysis we have done above to the dataset gives us a fantastic understanding of AirBnb's business in New York city. Manhattan is the most        demanding and expensinve location in NYC followed by Brooklyn, Queens,Bronx and Stalen Island. Loauan is the most reviewed host in entire NYC. Sonder(NYC) is the most valuable host who owns the maximum number of listings in NYC. Manhattan is the most reviewed listing per month.

Concluding with the statement which i observed that The Manhattan is the most valuable location in all formats for AirBnb.
 
