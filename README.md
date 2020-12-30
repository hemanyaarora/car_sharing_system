# car_sharing_system
This java project simulates a car sharing system in which car commuters pick up and drop-off passengers at designated stations. 
Assuming there are 'n' stations, one at every-mile along a route. At each station, except the last station, 
there are randomly generated number of passengers, each of them have a desired target station. 
There are cars at each station except the last station. Each car has a target destination station. 
The car drive along the stations until it arrives at its destination station. For example, if a car is 
initially located at station 1 and has destination station 4, then it will drive along
station 2 and 3 and finishes at station 4. Each driver picks up a maximum of three passengers 
(whose destination is either the same as car’s destination or on the way to the car’s destination), 
and drops them off where requested, and picks up more if possible. A driver gets paid per passenger per mile.
