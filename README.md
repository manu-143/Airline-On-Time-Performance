# Airline delay cause dataset
## by Mansi Kamthane


## Dataset

>The dataset used in this analysis is based on airline delay causes and spans a period of 20 years from 2003 to 2023. It includes information related to flight arrivals, delays, cancellations, and the contributing factors for the delays. The dataset consists of the following columns:

1. `year`: Represents the year of the flight data.
2. `month`: Represents the month of the flight data.
3. `carrier`: Represents the code or identifier for the airline carrier.
4. `carrier_name`: Represents the name of the airline carrier.
5. `airport`: Represents the code or identifier for the airport.
6. `airport_name`: Represents the name of the airport.
7. `arr_flights`: Represents the total number of flights that arrived.
8. `arr_del15`: Represents the number of flights that arrived delayed by 15 minutes or more.
9. `carrier_ct`: Represents the number of delayed flights attributed to the airline carrier.
10. `weather_ct`: Represents the number of delayed flights attributed to weather conditions.
11. `nas_ct`: Represents the number of delayed flights attributed to the National Aviation System (NAS), which includes air traffic control and other factors.
12. `security_ct`: Represents the number of delayed flights attributed to security-related reasons.
13. `late_aircraft_ct`: Represents the number of delayed flights attributed to the late arrival of the aircraft.
14. `arr_cancelled`: Represents the number of flights that were canceled.
15. `arr_diverted`: Represents the number of flights that were diverted to a different airport.
16. `arr_delay`: Represents the total time delay (in minutes) of all flights that arrived.
17. `carrier_delay`: Represents the total time delay (in minutes) attributed to the airline carrier.
18. `weather_delay`: Represents the total time delay (in minutes) attributed to weather conditions.
19. `nas_delay`: Represents the total time delay (in minutes) attributed to the National Aviation System.
20. `security_delay`: Represents the total time delay (in minutes) attributed to security-related reasons.
21. `late_aircraft_delay`: Represents the total time delay (in minutes) attributed to the late arrival of the aircraft.

The dataset contains 339,106 rows and 21 columns. It provides a comprehensive view of flight delays, their causes, and other relevant metrics for analyzing and understanding the factors influencing airline operations and performance.


## Summary of Findings

> During the exploration of the airline delay causes dataset, several findings were observed:

1. Arrival Delays: The distribution of arrival delays showed a skewness towards higher delay values, with the presence of extreme outliers. Applying logarithmic transformations helped normalize the data and reduce the impact of extreme values.

2. Carrier Delays: The number of delayed flights varied among carriers, with carrier "OO" having the highest number of delays. This information can be useful for identifying carriers that may require additional attention in terms of improving their operational efficiency and reducing delays.

3. Causes of Delays: The major causes of delays were related to late aircraft arrivals, followed by NAS delays and carrier delays. Understanding the contributing factors to delays can help airlines and relevant stakeholders in implementing targeted strategies to mitigate delays and improve overall performance.

4. Flight Counts: The number of flights varied across different months and years. In 2019, there was a peak in the number of flights, while other years exhibited relatively lower flight volumes. Analyzing the trends in flight counts can assist in understanding the overall demand and patterns in air travel.

5. Flight Cancellations: Flight cancellations were relatively rare compared to the total number of flights. The majority of flights were not canceled, with a higher frequency of zero to two cancellations. This finding emphasizes that flight cancellations are infrequent events but can still impact travel plans and require attention from airlines.

6. Flight Diversions: Flight diversions were also relatively uncommon compared to the total number of flights. The majority of flights were not diverted, with a higher frequency of zero to one diversions. Understanding the frequency and reasons for flight diversions can help identify areas for improving operational efficiency and passenger experience.

7. Relationships Between Variables: Several relationships were observed between variables during the exploration. For example, there was a positive correlation between the total number of flights and the number of delayed flights, indicating that higher flight volumes can contribute to increased delays. Additionally, the heatmap analysis revealed relationships between carriers, months/years, and average delays, providing insights into carriers with consistently higher delays and potential seasonality in delays.

These findings highlight the complexity of airline operations and the various factors that contribute to delays and disruptions. Understanding these patterns and relationships can assist airlines and industry stakeholders in making data-driven decisions to improve efficiency, minimize delays, and enhance the overall passenger experience.


## Key Insights for Presentation

> Thread 1: Analysis of Arrival Delays

One of the main threads from the exploration is the analysis of arrival delays. This analysis focuses on understanding the distribution of arrival delays, identifying the major causes of delays, and exploring how arrival delays vary across different months and carriers. The goal is to provide insights into the factors contributing to delays and identify patterns or trends that can inform decision-making for improving operational efficiency and customer satisfaction.

> Thread 2: Relationship Between Flights and Delays

The second main thread focuses on the relationship between the total number of flights and the number of delayed flights. This analysis aims to explore if higher flight volumes result in increased delays and to identify any correlations or patterns between flight counts and delay counts. Understanding this relationship is crucial for airlines to manage their operations effectively, allocate resources efficiently, and improve overall on-time performance.

> Thread 3: Impact of Cancellations and Diverted Flights

The third main thread revolves around understanding the impact of flight cancellations and diverted flights. This analysis aims to explore the distribution of cancellations and diversions, identify any relationships between these two variables, and investigate factors such as carrier-related delays and weather delays that may contribute to cancellations. Understanding the frequency and causes of cancellations and diversions is crucial for airlines to improve operational planning, minimize disruptions, and enhance customer satisfaction.