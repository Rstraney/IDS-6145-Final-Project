# IDS6145(SimTech 2018) - DISNEYWORLD "MAGIC KINGDOM" GUESTS ENTRANCE SYSTEM

# MouseHeadz
![**Mickey.png**](images/Mickey.png)

> * ADAM HARDNEY
> * BLAKE NGUYEN
> * MICHAEL STERKEL
> * RACHEL STRANEY
> * Project Title: MAGIC KINGDOM GUESTS ENTRANCE SYSTEM

# Abstract
Magic Kingdom, at Walt Disney World theme parks in Orlando Florida, has lived up to its tagline as being "The most Magical Place on Earth" by becoming one of the most visited theme parks in the world. According to the Themed Entertainment Association Global Attractions Attendance Report in 2015, Walt Disney's Magic Kingdom hosted over 20 million visitors. (http://www.teaconnect.org/images/files/TEA_160_611852_160525.pdf). For anyone who has the visited the Magic Kingdom theme park, the size of the crowds can affect guests' overall experience and impose safety issues. Compounding this issue is the bottleneck created by the Transportation and Ticket Center (TTC) where guests must travel by ferry boat, monorail, bus, and Minnie van to get to the official main street entrance (park entrance) to Magic Kingdom. The goal of our system is to model the time it would take guests to arrive at Magic Kingdom based on which mode of transportation taken from the TTC. We believe the two types of transportation that utilize efficiency and safety are Disney's buses and Minnie vans.



![**MKE.png**](images/MKE.png)



## General Introduction


Walt Disney theme parks are one of the most well-known theme parks in the world. Specifically, Magic Kingdom, which is located in Orlando, Florida is popularly known as the most happiest place on earth. The popular title is due to the innovation of Walt Disney himself. Walt Disney built his first theme park in Anaheim, California, known as Disneyland. Unfortunately, when he first built the Disneyland theme park, he ran out of property to build on. Therefore, he sought out more property in Orlando, Florida. He then began to build Disney World theme park in Orlando, Florida. While building Magic Kingdom park, Walt Disney and his team discovered a problem. The area directly in front of Magic Kingdom was a swamp and would not be suitable area to build a parking lot. They resolved this problem by building the guests parking lot a mile and a half away from Magic Kingdom. The former swamp was rehabilitated into the Seven Seas Lagoon as part of the the parking lot issue. However, Walt Disney faced another issue after combating the swamp problem. As a result of having to build the parking lot a mile and half away from Magic Kingdom, the need for transportation was discovered.

Walt Disney developed the Transportation and Ticket Center (TTC), where guests can buy their admission and secure transportation into Magic Kingdom's park entrance. In the original concept of the TTC, guests would travel to and from Magic Kingdom by ferry boats across the Seven Seas Lagoon or monorail "highway-in-the-sky". Later, Walt Disney built non-monorail hotels on Disney property, which required the use of bus transportation. As Walt Disney continued to build more hotels around the theme park, there became an overload at the TTC. The monorail and ferry boats could not keep up with the demand and high volume of guests coming in and out of Magic Kingdom. To help this, they developed an elaborate bus stop at Magic Kingdom. Currently, the TTC offers four modes of transportation to and from Magic Kingdom (bus, monorail, ferry boat, and Minnie van).

From our initial research, we found that Disney's Magic Kingdom averages about 53,000 guests per day. Of this, there are roughly 12,000 at most that can enter the park through the Magic Kingdom Parking Lot as this is the number of parking spots available. We can hypothesize that the high volume of guests that visit the Magic Kingdom park experience extensive wait times to travel to and from the TTC. Extensive wait times is a problem that is both interesting and relevant to Disney's Magic Kingdom park visitors, as it may affect the quality of guests experience while also imposing potential safety concerns. We propose the following system: Magic Kingdom Guests Entrance System as an attempt to resolve the problem of extensive wait times for the offered modes of transportation. We are interested in investigating and identifying answers to the following questions: which mode of transportation is the fastest method to get to and from the TTC to the park entrance of Magic Kingdom, does the design of the TTC create bottlenecking during high and low volume times, and does it lead to unnecessary wait times that can lead to negative visitor experiences.

We found limited to no research on Disney's mode of transportation in terms of which option is the fastest or how extensive wait times can affect visitors experience. We also found limited research on whether or not the TTC creates bottlenecking during different volumes of time and whether or not that it leads to extensive wait times. We believe our project makes the following contributions to answering research questions that have yet to be identified or answered. The first contribution, we believe would benefit Disney's Magic Kingdom park visitors. As our research will investigate the fastest type(s) of transportation offered, if bottlenecking occurs and during what time of day does it occurs. Our project's contributions will help Disney's employees as well as their guests in terms of how to approach extensive wait times. Our project will also contribute to the overall limited research in this particular area. We hope that our project's contributions become the starting point for future research as well.




This project makes the following contributions towards:
-	Identifying problems within Walt Disney's TTC.
-	Identifying whether or not extensive wait times affect visitors overall satisfactory experience.
-	Identifying the fastest type(s) of transportation offered at the TTC.
-	Identifying the slow type(s) of transportation offered at the TTC.
-	Investigating whether or not extensive wait times affect efficiency and safety.
-	Limitations of our research as well as propose future research directions in this area of research.





## The Model

(Provide structural and behavior diagrams of the system you wish to study.) (Why is your model a good abstraction of the problem you want to study?) (Are you capturing all the relevant aspects of the problem?) (Use the model to tell us what is going on.)

(explicitly list your requirements of what the model will have and simulate for the proposal)

## Fundamental Questions
The described system, entering Magic Kingdom, is being designed for simulation to answer fundamental questions that will ultimately lead to the answers the system was built to find.  For this system, which involves transportation methods to and from Magic Kingdom, the following questions apply.

The overarching fundamental questions are:

- Which transportation method (Monorail, ferry boat, bus or Minnie van) is the fastest method to get from the Transportation and Ticket Center to the park entrance of Magic Kingdom?
	
- Does the design of the Transportation and Ticket Center (TTC) create a bottleneck during high volume times that could lead to safety issues for the visitors?
	
- Does the design of the Transportation and Ticket Center (TTC) lead to unnecessary wait times that can lead to a negative visitor experience?
		
The sub questions that flow from the 3 fundamental questions are:
		
- What is the time, in minutes, that it takes to get to the Magic Kingdom Entrance from the TTC via the Ferry boat, via the Monorail, via the Buses and via the Minnie Vans?
- What is the capacity of the Ferry boat, Monorail, Bus and Minnie Van, respectively?
- How often do each of the four methods run?
- Are any of the transportation methods on a set schedule?
- Does travel time of the four methods vary depending on the time of day?
- What is the travel time at different times of the day?
- What are the hours of operation of the four transportation methods?
- Is there a cost associated with each of the transportation methods?
- If there was an emergency could park visitors exit the park in a safe and efficient manner?
 


## Expected Results

The fundamental questions are to be answered by the simulation created to represent the system.  However, before the simulation is built there are notions of what answers to some of the questions will be and the simulation will be used to determine if these pre stated answers are correct.

Disney buses and Minnie vans are expected to have the shortest travel times, the monorail as the second shortest travel time and the ferry boats as the slowest travel time. Using google maps distance measuring tool the distance of the bus route (and the Minnie van route) is approximately 1.12 miles, the distance of the Monorail route is approximately 1.56 miles and the distance of the ferry route is approximately .67 miles.

For this system, the time it takes to travel from the TTC to the Magic Kingdom park entrance, regardless of transportation method, is expected to increase during peak visiting hours during the day. This expectation is from personal experience at the parks during peak times and the perception that the time it took was statistically significantly longer.  This also applies to the direction of travel. Getting into the park during normal business hours is expected to take longer than exiting the park and conversely as the park is nearing closing time, the time to get into the park will decrease while the time to get out of the park will increase.

All modes of transportation are expected to run during the entire time the park is open except when a mode is not operating due to a mechanical issue that may arise.

The expectation, before running the simulation, is that a bottleneck is created at the TTC during peak hours due to its design.

All modes of transportation, excluding the Minnie vans, are included in the price of admission, while a ride in a Minnie van is a flat rate fee of $20 per ride.

For the presented system the data will be presented in the form of line graphs, scatter plots and histograms.

**(Mike Comment) In the directions for this section is said to hand draw some graphs, which I have given below, but it said something about not showing data but I wasn't sure, so I have graphs with Example Data and those without.  I can always remake these on the computer if you think its needed.  Please use whichever one you think would be best.

A histogram will be used to plot the average time (in minutes) it takes to get into the park by the four different modes of transportation.


![Histogram Example](images/HistogramExample2.jpg)

A scatter plot will be used to track transit times (in minutes) of individual agents.  The scatter plot will visually show where most of the transit times fall.


![Scatter Plot Example](images/ScatterPlotExample2.jpg)

A line graph will be used to show the change in transit time (in minutes) as the time of the day changes from the time the park opens until it closes.


![Line Graph Pot Example](images/LineGraphExample2.jpg)


![Mike Space Mountain](images/MikeSpaceMountain.png)

## Research Methods
(Cellular Automata, Agent-Based Model, Discrete Event Continuous Modeling...)(Python or Anylogic) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards) (Steps in the process)

### Methods used in Similar Studies
There have been numerous publications involving research to estimate visitors at theme parks and evaluate guest traffic flow. The purpose behind much of this research falls into one of two categories: 1. ) Assessment of how wait times impact park visitor experience and 2.) Analysis of emergency or disaster management realtive to congestion in the park. For example, Reza H. Ahmadi focused on the Six Flags Magic Mountain theme park to address questions of daily operations such as managing traffic flow in the park and suggesting routing tours for guests (Ahmadi, 1997). Data used in his analysis included primary data from a visitor questionnaire and direct measures provided by the park which included park attendance and queue lengths at rides. More recent research by Shih-Fen Cheng, et al. in 2013 and Liou Chu, et al. in 2014 also considered guest satisfaction . Whereas  Shih-Fen Cheng and his team developed and constructed a very large agent-based model, Liou Chu approached their work by designing a Theme Park Queuing System using discrete-event simulation (Cheng, 2013; Chu, 2014). A publication by Gurkan Solmaz and Damla Turgut, on the other hand, is a good example of how simulating theme park attendee traffic can address issues of safety. Their study focused on the foot traffic patterns of guests in theme parks to evaluate mobility in the event of a disaster. The researchers used information collected from mobile devices carried by 11 volunteers to simulate visitor movement around the park. The simulation used in the study was an agent-based model (Solmaz, 2017). 

### Proposed Methods for our Research

Although there are several approaches to simulating traffic and movement throughout a theme park, our team has elected to develop a discrete-event simulation to address our research questions. Furthermore, we plan to include an agent-based aspect to our simulation since our preliminary research has concluded that characteristics of the park guests play a significant factor in our system. For example, guests visiting in large groups or with small children may take longer to reach the entrance of the park. Therefore, the agents parking and traveling to the Magic Kindom entrance will be groups with attributes like average age and number in the group.

As described in the Model section, there are assumptions and parameters that need to be estimated to develop a meaningful simulation. Specifically, the resources mentioned above and others will assist us in identifying the following:
- Maximum daily park attendance by way of the parking lot (12,156 - https://www.wdwmagic.com/facts!.htm)
- Typical travel time required for each mode of transport into park (Ferry boat, Monorail, Bus and Minnie Van)
- Typical wait time through security at the Transportation and Ticket Center (TTC) (this will depend on whether the agents are carrying bags as there are two security lines - one for guests with bags and the other for guests without). For simplicity, if a group is carying a bag, all members of that group will go through the same bag security line. 



Taking into account our research thus far, Crowd diversion systems have been an area of focus for the theme park industry for a while. Disney's FASTPASS and Universal Studios' Express Pass have both been implemented to reduce lines and wait times once guests are inside the park. (Shih-Fen Cheng, 2013) However, these solutions do very little to remedy the time it takes guests to enter the park.

 According to Ohtani, a cited reference by the researchers, wait time before being served is one of the most significant factors to customer satisfaction.  
	- Although the authors modeled multiple rides within a theme park using Arena, this work can be generalized to our research by substituting rides with the main queuing points of the Magic Kingdom entrance, namely, the ticketing & transport center and the three modes of transport. 



## References


Ahmadi, R. H. (1997). Managing Capacity and Flow at Theme Parks. Operations Research. 
https://doi.org/10.1287/opre.45.1.1

Cheng, S., & Lin, L. (2013). An agent-based simulation approach to experience management in theme parks. In Winter Simulation Conference (pp. 1527–1538).

Gigliotti, A. R., Russell, A., & Gentry, R. J. (2016). It’s a Small World: Worldwide Declining Attendance and Disney Theme Parks. SAGE Business Cases Originals.


Richardson, S. (2014). 9 things you never knew about the Walt Disney world monorail system. https://www.themeparktourist.com/features/20141219/29760/10-things-you-never-knew-about-disney-world-monorail-system
Solmaz, G., & Turgut, D. (2017). Modeling pedestrian mobility in disaster areas. Pervasive and Mobile Computing, 40, 104–122. https://doi.org/10.1016/j.pmcj.2017.05.005

Spence, J. (2011). Transportation and ticket center - TTC. http://land.allears.net/blogs/jackspence/2011/04/transportation_and_ticket_cent.html

WDWMAGIC: An Unofficial Walt Disney World Fan Site. *Facts*. https://www.wdwmagic.com/facts!.htm 

