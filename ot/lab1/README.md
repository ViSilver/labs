# Laboratory work nr. 1

### DeadLines (DLs)
Group 1: March 8th, 01:00 GTM+2

Group 2: March 22nd, 01:00 GTM+2

### Grading system
- 1 subproblem  - 6
- 2 subproblems - 8
- 3 subproblems - 10


## Problem description
Aunt Marry is an old lady from Chișinău. She lives in the area near the Circus and everyday she needs to take the trolleybus in order to get to the city center. From there she can go further to the *Piața Centrală*, where she doesn't buy anything, rather she spends her time hearing the latest news in the city. 

Unfortunately, Aunt Marry is upset by the way the municipal transport is optimized especially when she returns back home. For example, from station **Ștefan cel Mare** to station **Circul** there go trolleybuses nr: 7, 10, 24, 25 (I will skip 11 and 14 as they are routed comparably few times per day). Thus, she doesn't care so much what is the number of the trolleybus she takes in order to reach the destination station. One thing she noticed is that often the trolleybuses arrive as a train (all at once) to the station, but there appear gaps of around 10 or even 15 minutes when there no trolleybuses arrive. What Aunt Marry wants, neglecting the car traffic in our city, is an evenly distributed timetable when she can wait for the minimum amount of time the transportation that will take her to the destination. 

[Here](https://github.com/ViSilver/labs/blob/master/ot/lab1/stations/station_graph.txt) is represented the mini graph of Chisinau's public transportation. 


### Subproblem 1
Given the [timetables](https://github.com/ViSilver/labs/tree/master/ot/lab1/stations) of trolleybus arrival, find an algorithm to optimize the traffic from station **Ștefan cel Mare** to station **Circul**. Visualize the data output of your solution.


### Subproblem 2 
Given the [timetables](https://github.com/ViSilver/labs/tree/master/ot/lab1/stations) of trolleybus arrival, find an algorithm to optimize the traffic among all given stations.


### Subproblem 3 
Given the [passenger traffic load](https://github.com/ViSilver/labs/blob/master/ot/lab1/stations/station_graph.txt) between two stations (written in the parentheses), find an algorithm to determine the number of trolleybuses of each type needed to satisfy the law obedient citizens' needs that use the public transportation. For example, how many trolleybuses of number 3 are needed to completely consume the load? If there isn't sufficient data, what would you need more to take into consideration? 

PS: Consider that there can be max 70 people in a trolleybus. 



