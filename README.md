# Note
I have published this notebook in Kaggle. Please view the detail codes from <a href="https://www.kaggle.com/together/visualization-flight-delays?scriptVersionId=29191037">Visualization-Flight-Delay</a>.

# Flight Delay Analysis
The topic comes from a Kaggle Dataset named <a href="https://www.kaggle.com/usdot/flight-delays#flights.csv">2015 Flight Delays and Cancellations</a>.
<br>
The dataset comes from Department of Transportation (US). 


## Objective
In this project, I used several packages (including <a href="https://plot.ly">plot.ly</a>) in Python to visualize this big dataset. 

## Data Overview
### Raw Variables (Column Names)
**YEAR**: Year of the Flight Trip  
**MONTH**: Month of the Flight Trip  
**DAY**: Day of the Flight Trip  
**DAY_OF_WEEK**: Day of week of the Flight Trip  
**AIRLINE**: Airline Identifier  
**FLIGHT_NUMBER**: Flight Identifier  
**TAIL_NUMBER**: Aircraft Identifier  
**ORIGIN_AIRPORT**: Starting Airport  
**DESTINATION_AIRPORT**: Destination Airport  
**SCHEDULED_DEPARTURE**: Planned Departure Time  
**DEPARTURE_TIME**: WHEEL_OFF - TAXI_OUT  
**DEPARTURE_DELAY**: Total Delay on Departure  
**TAXI_OUT**: The time duration elapsed between departure from the origin airport gate and wheels off  
**WHEELS_OFF**: The time point that the aircraft's wheels leave the ground  
**SCHEDULED_TIME**: Planned time amount needed for the flight trip  
**ELAPSED_TIME**: AIR_TIME + TAXI_IN + TAXI_OUT  
**AIR_TIME**: The time duration between wheels_off and wheels_on time  
**DISTANCE**: Distance between two airports  
**WHEELS_ON**: The time point that the aircraft's wheels touch on the ground  
**TAXI_IN**: The time duration elapsed between wheels-on and gate arrival at the destination airport  
**SCHEDULED_ARRIVAL**: Planned arrival time  
**ARRIVAL_TIME**: WHEELS_ON + TAXI_IN  
**ARRIVAL_DELAY**: ARRIVAL_TIME - SCHEDULED_ARRIVAL  
**DIVERTED**: Aircraft landed on airport that out of schedule  
**CANCELLED**: Flight Cancelled (1 = cancelled)  
**CANCELLATION_REASON**: Reason for Cancellation of flight: A - Airline/Carrier; B - Weather; C - National Air System; D - Security  
**AIR_SYSTEM_DELAY**: Delay caused by air system  
**SECURITY_DELAY**: Delay caused by security  
**AIRLINE_DELAY**: Delay caused by the airline  
**LATE_AIRCRAFT_DELAY**: Delay caused by aircraft  
**WEATHER_DELAY**: Delay caused by weather  
