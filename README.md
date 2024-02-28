![image](https://github.com/AshwinPavanKadha/Hospitality_Insights_for_AtliQ/assets/131484545/4bd9943a-7ced-45c2-8d37-3c4321207acf)


# Hospitality_Insights_for_AtliQ
# PowerBi-Hospitality-Analytics
A detailed project to find Revenue Insights from scratch for ehancing performance of Atliq Chain of Hotels using Power Bi and empower stake holders to have clear understanding about critical issues and possible opportunites to resolve them. To create targets for Monthly, weekly through market analysis and stratagize their assets accordingly.

Live Dashboard Link :- http://surl.li/qzmau

Power point Link :- http://surl.li/qzmcj

Video Presentaion :- http://surl.li/qzyfm



## Problem Statement!
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury and business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.


- **Project objective:** 

    **1.** Create a _[Hospitality performance Dashboard for detailed veiw of Revenue, DSRN,RevPar, Occupancy, Realisation through Week over week (Wow)]((https://app.powerbi.com/view?r=eyJrIjoiODkzZDFhZTEtZGQ0Ni00Mjg0LWFkOTItNDE2ODZiNThmYTYyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9))_ 

    **2.** Conduct a comprehensive revenue comparison between _[Room Class and category of hotel and genrate insights ]((https://app.powerbi.com/view?r=eyJrIjoiODkzZDFhZTEtZGQ0Ni00Mjg0LWFkOTItNDE2ODZiNThmYTYyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9))_

- **Purpose of sales analytics:** Empower businesses to monitor and evaluate their pricing stratagy against their competitors.

- **Importance of analyzing Hospitality data:** Conducst Root cause analysis (RCA) and idetify Least performing Hotels, ⬇️ avg. ratings and possible reasons by tracking key performance indicators (KPIs).

- **Role of Dashboard:** To effectively Visualize live performance of various KPIs like Occupancy, Avg. rating, DSRN determine efective ways to improve costomers' satisfaction, and identify potential business expansion opportunities in promising cities.

**Data collection , cleaning and Modelling**

General Practices in Hospitality industry:
- Weekends: Fridays and Saturdays
- On Weekends, There will be a high demand for Leisure and vacations category Hotles 
- Weekdays: Sunday to Thursday
- On Weekdays, There will be a high demand for Business and Meetings Halls.

**Data cleaning**:

- Loading the given files i.e dimensional tables like date, hotels, rooms,  and fact tables aggregated bookings , bookings into Power query . 
- Identify the duplicated values from different columns and delete them
- Identify any mistakes in data throughout columns and rectify the errors in data like spelling mistakes
- Identify errors in numerical like booking date, amount in fact tables and modified them accordingly


**Data Modelling**:
- Identify primary keys, foreign keys from dim tables and map them with fact tables through one-to-many relationship and adjusted them into Star schema
- Add week numbers (wn) column in dim_date table for moderation and understanding of data.

**Level 1 Analysis:**  
It enables us to deep dive into the Key Performance indicators of the business. It summarizes KPIs according to various factors like WoW changes etc.
Using DAX queries I have comprehensively Built views for most important metrics in Hospitality domain like Revenue, RevPar, ADR, DSRN , Occupancy (%), Realisation (%), Average Ratings

- Revenue--> To get the total revenue realised
  
- Average Rating--> Get the average ratings given by the customers
  
- Occupancy (%)--> Occupancy means total successful bookings happened to the total rooms available

- Booking % by Room class--> To show the percentage contribution of each room class over total rooms booked. We have room classes like Standard, Elite, Premium, Presidential.

- Booking % by Platform--> To show the percentage contribution of each booking platform for bookings in hotels. We have booking platforms like makeyourtrip, logtrip, tripster etc)

- Cancellation % --> Total cancelled bookings to Total bookings
  
- No Show rate % --> Total No show bookings to total bookings

- Realisation %--> calculate the realisation percentage. It is nothing but the successful "checked out" percentage over all bookings happened.

- RevPAR--> Calculate the RevPAR (Revenue Per Available Room)It represents the revenue generated per available room, whether or not they are occupied and helps hotels measure their revenue generating performance to accurately price rooms. It  can also help hotels to measure against brands.

- DBRN --> Calculate (Daily Booked Room Nights)This metrics tells on average how many rooms are booked for a day considering a time period

- DSRN--> calculate DSRN (Daily Sellable Room Nights)This metrics tells on average how many rooms are ready to sell for a day considering a time period

- DURN --> calculate (Daily Utilized Room Nights)This metric tells on average how many rooms are successfully utilized by customers for a day considering a time period

- ADR--> Calculate the ADR (Average Daily rate)It is the ratio of revenue to the total rooms booked/sold. And It measures the average paid for rooms sold in a given time


**Level  2 Analysis:**

By level 1 , we can have clear understanding that specific hotel has a least Occupancy of 44.3 %. Conversely, that same hotel has lesser avg rating of  2.37

This hotel need to focus on rating first, and the possible reasons could be : 

➢ They are not focusing at online reviews and improving themselves in service on specific topics mentioned in reviews

➢ Basically they are facing challenges with their overall service


An efficinet way for addressing :

➢ Online content on multiple channel websites should be fair and up to date

➢ Customers satisfaction plays key role in cancellation, Hotel should meet expectations of customers and maintain amenities according to promise while booking

The above approach could be applicable for other properties as well. Since, they follow same trends

On Observing RevPAR, ADR, Occupancy. It is evident that Revenue and occupancy has a jump in weekends and a drop in weekdays. However, ADR is a flat line throughout all months

➢ This shows that, They are following flat pricing strategy and selling rooms at constant Price on weekdays and weekends

➢ They can also work on Dynamic pricing strategy based on peak days and Occupancy(%), Competitor Pricing etc.

![image](https://github.com/AshwinPavanKadha/Hospitality_Insights_for_AtliQ/assets/131484545/30e7138e-e2dd-461a-8ecd-ff393af25fae)




## Technical & Soft Skills:
- [x]	Mastering the Basics like cell formats, conditinal formatting to building appealing dashboards
- [x]	Proficiency in ETL methodology (Extract, Transform, Load) from various sources.
- [x]	Mastered the Skills to generate a date table, clean data and transform data using Power Query.
- [x]	Slicing & summarizing the data using Pivot table based on stake holder goal
- [x]	Ability to derive fiscal months and quarters as needed.
- [x]	Establishing data model relationships with Power Pivot ⚡ and Data Modelling , Relations.
- [x]	Utilizing DAX to create calculated columns and measures like SUM,SUMX, CALCULATE.
- [x]	Created appealing visuals 📊 using the features of diverse charts and formatted them to make presentable.
- [x]	Derived insights 🔎 focused on stake holder goals which significantly helps in decision making 📉 for Revenue teams at AtliQ Hotels 

## Soft Skills:
- [x]	Refined understanding of practices in Hospitality domain importance of data informed decision making
- [x]	Gained the knowledge about the factors involved in decision making 
- [x]	Designing user-centric reports with empathy in mind.
- [x]	Optimization of report generation through meticulous fine-tuning.
- [x]	Developing a systematic approach to devising a report building plan.
