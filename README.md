# Predicting Riksy Landings using GLM models

**Project Link**:
https://rpubs.com/akshaykher/Predicting-Risky-Landings-using-GLM-models

#### Motivation: 
To reduce the risk of landing overrun.

#### Goal: 
Use various GLM (generalized linear models) to study what factors and how they would impact the landing distance of a commercial flight.

#### Data:
Landing data (landing distance and other parameters) from 950 commercial flights.

#### Variable Dictionary:

1. **Aircraft**: The make of an aircraft (Boeing or Airbus).
2. **Duration (in minutes)**: Flight duration between taking off and landing. The duration of a normal flight should always be greater than 40min.
3. **No_pasg**: The number of passengers in a flight.
4. **Speed_ground (in miles per hour)**: The ground speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.
5. **Speed_air (in miles per hour)**: The air speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.
6. **Height (in meters)**: The height of an aircraft when it is passing over the threshold of the runway. The landing aircraft is required to be at least 6 meters high at the threshold of the runway.
7. **Pitch (in degrees)**: Pitch angle of an aircraft when it is passing over the threshold of the runway.
8. **Distance (in feet)**: The landing distance of an aircraft. More specifically, it refers to the distance between the threshold of the runway and the point where the aircraft can be fully stopped. The length of the airport runway is typically less than 6000 feet.
