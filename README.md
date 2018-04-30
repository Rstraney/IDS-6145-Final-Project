# IDS6145(SimTech 2018) - DISNEYWORLD "MAGIC KINGDOM" GUESTS ENTRANCE SYSTEM

# MouseHeadz
<img src="./images/Mickey.png" alt="Mickey" width="180px" height="180px">

> * ADAM HARDNEY
> * BLAKE NGUYEN
> * MICHAEL STERKEL
> * RACHEL STRANEY
> * Project Title: MAGIC KINGDOM GUESTS ENTRANCE SYSTEM

## Project Roles
For our final project, we felt that it was in our best interest to assign specific roles and responsibilities to each of our team members. Based on our knowledge, skills and abilities, we wanted to demonstrate our individual and collective strengths in our final project. Rachel and Michael have been our project's avid Anylogic model builders. They have been leading the efforts in creating the model of our system as well as data analysis. Blake and Adam are responsible for the research and written report of the final project. Collectively, we have been successful at collaborating and supporting one another at various stages of our final project. We strongly believe that our team has performed well together and that our final project represents are efforts and successes.




## Abstract

Magic Kingdom, at Walt Disney World theme parks in Orlando Florida, has lived up to its tagline as being "The Most Magical Place on Earth" by becoming one of the most visited theme parks in the world. According to the Themed Entertainment Association Global Attractions Attendance report in 2015, Walt Disney's Magic Kingdom hosted over 20 million visitors. (http://www.teaconnect.org/images/files/TEA_160_611852_160525.pdf). Avid Disney goers and first time guests are well aware of the affects of population size and it's impact on the overall theme park experience. Not only does the population size affect overall experience for guests but it also imposes safety issues.
Compounding this issue is the bottlenecking created by the Transportation and Ticket Center (TTC), where guests must travel by ferry boat, monorail, bus, and Minnie van to get to the official main street entrance (park entrance) of Magic Kingdom. The goal of our system is to model the time it would take guests to arrive at the Magic Kingdom park entrance based on which mode of transportation taken from the TTC. We hypothesized that the two modes of transportation that utilize efficiency and safety are Disney's buses and Minnie Vans. From our results, our model depicts that the most efficient mode of transportation are the Disney's buses.


## General Introduction

Walt Disney theme parks are one of the most well-known theme parks in the world. Specifically, Magic Kingdom, which is located in Orlando, Florida is popularly known as the happiest place on earth. The popular title is a result of just how innovative Walt Disney is. Walt Disney built his first theme park, known as Disneyland in Anaheim, California.
Unfortunately, when he first built the Disneyland theme park, he ran out of property to continue to build on. Therefore, he sought out more property in Orlando, Florida where he then began to build the Disney World theme park.

While building the Magic Kingdom park, Walt Disney and his team of engineers discovered a problem. The area directly in front of Magic Kingdom was a swamp and would not be a suitable area to build a parking lot. They resolved this issue by building the guests' parking lot a mile and a half away from the Magic Kingdom entrance. The former swamp was rehabilitated into the Seven Seas Lagoon as part of a solution to fix the the parking lot issue. However, after rehabilitating the swamp into the Seven Seas lagoon Walt Disney needed some form of transportation from the parking lot, which is located a mile and half away from the Magic Kingdom entrance.

Walt Disney developed the Transportation and Ticket Center (TTC), where guests can buy their admission into the theme park and secure transportation into Magic Kingdom's park entrance. In the original concept of the TTC, guests would travel to and from Magic Kingdom by ferry boats across the Seven Seas Lagoon or use the "highway-in-the-sky" as known as the monorail station. Later on, Walt Disney built hotels that were not supported by the monorail transportation. Therefore, these hotels required the use of an alternative mode of transportation, and as a solution they implemented the use of bus transportation. As Walt Disney continued to build additional hotels around the theme park, the TTC became overly crowded with guests. The monorail and ferry boat transportation methods could not keep up with the demand and high volume of guests coming in and out of Magic Kingdom. Therefore, in order to alleviate the high volume of guests, they had to implement other methods of  transportation for their guest. Currently, the TTC offers four modes of transportation to and from Magic Kingdom (bus, monorail, ferry boat, and Minnie van). The image below depicts an areal view of the system we are proposing to simulate:

![**MKE.png**](images/MKE.png)

From our research, we found that Disney's Magic Kingdom theme park averages roughly 53,000 guests attendance per day. Of this, there are roughly 12,000 at most that can enter the park through the Magic Kingdom parking lot as this is the number of available parking spots. We can hypothesize that the high volume of guests that visit the Magic Kingdom park experience extensive wait times to travel to and from the TTC. Extensive wait times is a problem that is both interesting and relevant to Disney's Magic Kingdom park visitors, as it may affect the quality of  the overall experience while also imposing potential safety concerns. We propose the following system: Magic Kingdom Guests Entrance System as an attempt to improve upon the issue related to extensive wait times for the offered modes of transportation. We are interested in investigating and identifying: (1) which mode of transportation is the fastest method to get to the TTC to the park entrance of Magic Kingdom, (2) does the design of the TTC create bottlenecking, and (3) does it lead to unnecessary wait times that can lead to negative experiences for their guests.


We found very limited research on Walt Disney's modes of transportation in terms of which option is the fastest or how extensive wait times can affect visitors experience. What we did find in our research is which mode of transportation is the most used, which is the iconic monorail system. We also found limited research on whether or not the TTC creates bottlenecking during different volumes of time and whether or not that it leads to extensive wait times. We believe our project makes the following contributions to answering research questions that have yet to be identified or answered. We believe the first contribution would benefit Disney's Magic Kingdom park visitors. As our research will investigate the fastest type(s) of transportation offered, if time of day affects which method is the fastest, if bottlenecking occurs and during what time of day does it occur. We believe our project may contribute to improving upon the issue with extensive wait times. Our project will also contribute to the overall limited research in this particular area. We also hope that our project contributes as initial efforts for future research in this specific area of research.

Crowd diversion systems have been an area of focus for the theme park industry for a number of years. Disney's FASTPASS and Universal Studios' Express Pass have both been developed and implemented to reduce the amount of lines and wait times once guests are inside the park. However, these solutions do very little to remedy the time it takes guests to enter the park. As this is the first thing guests experience during their visit to the Magic Kingdom, this is a very import piece to the broader park system. Past simulation research can be generalized to our project by substituting rides with the main queuing points of the Magic Kingdom entrance. This project makes the following contributions towards:
-	Identifying problems within Walt Disney's TTC.
-	Identifying the fastest type(s) of transportation offered at the TTC.
-	Identifying the slow type(s) of transportation offered at the TTC.
-	Investigating whether or not extensive wait times affect efficiency and safety.
-	Limitations of our research as well as propose future research directions in this area of research.

![Mike Space Mountain](images/MikeSpaceMountain.png)

A member of our team enjoying Space Mountain at Walt Disney World.

## The Model

An Object Diagram shown below depicts the main objects of the Magic Kingdom Guest Entrance System. As guests arrive they are directed to park in one of the two parking lots, the Hero lot or the Villain lot. From the parking lot, guests travel by foot or by tram to the security checkpoint. Guests are randomly to go through the security lines. Security lines are divided into guests with bags and guest without bags. Finally, from the Transportation and Ticket Center (TTC), guests have a choice which mode of  transportation (bus, monorail, ferry boat, or Minnie Van) to take to get to the entrance of the park.

![**Object Diagram.png**](images/BDFP1.png)




### Modes of Transportation:
Walt Disney Monorail
![MK-Monorail.png](./images/MK-Monorail.png)

Walt Disney Ferry boats
![Mk_ferry.png](./images/Mk_ferry.png)

Walt Disney Buses
![MK_bus.png](./images/MK_bus.png)

Walt Disney Minnie Vans
![minnie_van.png](./images/minnie_van.png)








## Fundamental Questions
The Magic Kingdom Guest Entrance System is being designed for simulation to answer the following fundamental questions:

- Which transportation method (monorail, ferry boat, bus or Minnie van) is the fastest method to get from the Transportation and Ticket Center (TTC) to the park entrance of Magic Kingdom?

- Does the design of the Transportation and Ticket Center (TTC) create bottlenecking during high volume times that could lead to safety issues for the visitors?

- Does the design of the Transportation and Ticket Center (TTC) lead to unnecessary wait times that can lead to a negative visitor experience?


The sub questions that flow from the 3 fundamental questions are:

- How long does it take (in minutes) guests to travel to the Magic Kingdom entrance from the TTC via monorail, via ferry boat, via bus, and via Minnie Van?
- What is the capacity of the Ferry boat, Monorail, Bus and Minnie Van, respectively?
- How often do each of the four methods run?
- Are any of the transportation methods on a set schedule?
- Does travel time of the four methods vary depending on the time of day?
- What is the travel time at different times of the day?
- What are the hours of operation of the four transportation methods?
- Is there a cost associated with each of the transportation methods?
- If there was an emergency could park visitors exit the park in a safe and efficient manner?


## Expected Results


The fundamental questions are to be answered with the data collected from the model of our system. To some degree we have preliminary results that are supported by the notions of existing research. However, to fully address our fundamental questions a model is needed to better address the questions related to our system.


- The Disney buses and Minnie vans are expected to have the fastest travel times. The monorail is expected to have the second fastest travel time and the ferry boats are expected to have the slowest travel time.

- The time it takes to travel from the TTC to the Magic Kingdom park entrance, regardless of transportation method, is expected to increase during peak visiting hours during the day. This expectation is interfered by personal experiences of our researchers. The parks during peak times and the perception that the time it took was statistically significantly longer. For example, getting into the park during normal business hours is expected to take longer than as the park is nearing closing time.

- The expectation, before running the simulation, is that a bottleneck is created at the TTC during peak hours due to its design.




#### Visualized Data of Expected Results
For the Magic Kingdom Entrance system the data will be presented in the form of line graphs, scatter plots, and histograms.


![Line Graph Pot Example](images/LineGraphExample2.jpg)

_Line Graph_. A line graph will be used to show the change in average transit time (in minutes) as the time of the day changes from the time the park opens until it closes. This can be useful when validating our model.


![Scatter Plot Example](images/ScatterPlotExample2.jpg)

_Scatter Plot_. A scatter plot by groups will be used to track transit times (in minutes) of agents. The scatter plot will visually show where most of the transit times fall. Visualizations like scatter plots can also be used to compare the duration of time it takes to enter the park at peak and non-peak times throughout the day.


![Histogram Example](images/HistogramExample3.jpg)

_Histogram_. Histograms will be used to plot the time (in minutes) it takes to get into the park by the four different modes of transportation (monorail, ferry, bus and Minnie van).





## Research Methods

#### Methods used in Similar Studies
There is existing research related to investigating the estimate of visitor attendance at theme park and evaluations of the visitor traffic flow. The purpose behind this research falls into one of the two categories: 1) assessment of how wait times impact theme park visitor experience and 2) analysis of emergency or disaster management relative to congestion in the park. For example, Ahmadi (1997) focused on the Six Flags Magic Mountain theme park to address questions related to daily operations such as managing traffic flow in the park and suggestions for rerouting of tours offered to guests. Data used in his formal analysis included primary data collected from  visitor questionnaires and direct measures provided by the park, which included park attendance and queue lengths at ride attractions.

More recent research by Shih-Fen Cheng et al. (2013) and Liou Chu et al. (2015), considered guest satisfaction. Whereas  Shih-Fen Cheng et al. (2013) developed and constructed a very large agent-based model. Liou Chu et al. (2014) approached their work by designing a Theme Park Queuing System using discrete-event based simulation (Cheng, 2013; Chu, 2014). A publication by Gurkan Solmaz and Damla Turgut (2017), on the other hand, is a good example of how simulating theme park attendance traffic can address issues of safety. Their study focused on the foot traffic patterns of guests in theme parks to evaluate the degree of mobility in the event of a disaster. The researchers used information collected from mobile devices carried by 11 volunteers to simulate visitor movement around the park. The simulation used in the study was an agent-based model (Solmaz, 2017).


#### Proposed Methods for our Research

Although there are several approaches to simulating traffic and movement throughout a theme park, our team has elected to develop a discrete-event based simulation to address our research questions. Furthermore, we plan to include an agent-based aspect to our simulation since our preliminary research has concluded that characteristics of the park guests play a significant factor in our system. For example, guests visiting in large groups or with small children may require more time to reach the entrance of the park from the Transportation and Ticket Center (TTC). Therefore, agents in our model will be groups of individuals with attributes like average age and number in the group.

As described in the Model section of our report, there are assumptions and parameters that need to be estimated to develop a meaningful simulation. The resources mentioned will assist us in identifying these estimates. Below are a few of the preliminary estimates for the simulation as well as any relevant assumptions or limitations:
- The maximum daily park attendance (groups of guests) by way of the parking lot is 12,156 (https://www.wdwmagic.com/facts!.htm)

- The typical travel time required for each mode of transportation into the park using Google maps distance measuring tool reports that the distance of the bus route and the Minnie van routes are approximately 1.12 miles, the distance of the Monorail route is approximately 1.56 miles and the distance of the ferry route is approximately .67 miles).

- The typical wait time through the security checkpoint before arriving at the Transportation and Ticket Center (TTC) will depend on whether or not guests are carrying bags into the park. There is essential two forms of lines at the security checkpoint; guest with bags and guest with no bags. For simplicity, guests with bags, will go through the same security line.

- Although all modes of transportation may experience mechanical issues (e.g., out of service buses, engine problems, system malfunctions, etc.). We excluded this issue to obtain some control in our model. Therefore, we will be assuming that all modes of transportation are running without any mechanical issues during the duration of our model.

- All modes of transportation, excluding the Minnie vans, are complimentary and included in the price of admission with the exception of the Minnie vans. There is a flat rate fee of $20.00 per ride that is associated with the Minnie van transportation option. The cost factor associated with the Minnie vans may affect the guests' choice of which mode of transportation to take. Therefore, this particular mode of transportation will not be implemented in our model.






## Results







## Discussion
- limitations of our simulation/study
- why we didn't use the Minnie vans
- initial assumptions versus our actual results
- example of that is pedestrians only walk through the parking lot.



#### Limitations

_Anylogic_. While we had the opportunity to explore some aspects of Anylogic, we noticed that the personal learning edition (student free version) has some restrictions to the pedestrian features offered. For example, we wanted to run our simulation for longer than an hour but that required us to purchase the full version of Anylogic. Since we were unable to run our simulation for longer than an hour, we feel that our results may vary due to this single limitation. We also ran into issues related to computing power. We wanted to implement a full scale of at least 6,000 vistors per hour but our computer systems could not withstand the large scale of vistors we were trying to implement in our model. Therefore, in order to combat this issue, we had to scale the number of vistors down to ten percent. Originally, we wanted to include 6,000 vistors but unfortunately, we had to downsize to 600 people so that the model could fully function. This is a solution we came up with to remedy the limited computing power we experienced. In our results, we converted our model scale to realistic estimates by multiplying our variables by ten. For example, 600 vistors will be multipled by 10 to better represent the 6,000 vistors we originally wanted to implement in our model but couldn't simply because we had limited computing power.



_Data_. For our project and model, we found it difficult to implement real data within our model. This is due to the fact that Disney does not provide public records of data. We had to use synthtic data in our model in order to

_Model Resolution_.

_Model Fidelity_.




- tram is missing
- acknowledge that we developed the system in a way that it could not







#### Future Research
Kider's email including the paper he wanted us to look over.

If given an opportunity to work with the full version of Anylogic, we would like to further investigate whether or not running our simulation for more than an hour would alter our results. Future studies should consider working with the full version of Anylogic to further investigate this limitation in our study.




#### Model Description Mike Section Please check my numbers for what the model is set to ensure I didn't goof

The anylogic model created to cover the movement of people from the TTC to MK entrance consists of the following blocks:
  
  SelectOutputIn (x1)
  SelectOutputOut (x3)
  TimeMeasureStart(x3)
  TimeMeasureEnd(x3)
  Batch(x3)
  Unbatch(x3)
  Service(x3)
  Sink(x3)
  ResourcePool (x3)
  
  Each of the three modes of transportation (monorail, ferry and bus) were setup in a similar manner to ensure consistency in how the model was running each method.  The selectOutputIn (called SelectTransport in the model) was used to have each agent determine which mode of transportation to select.  The selection was based on probabilities with 30 percent going to the ferry, 50 percent going to the monorail and 20 percent going to the buses.  The reason for this distribution was based on personal experience of the members and their families.  The group agreed that most new visitors to the park would choose the monorail, the ferry would be the second choice and the buses are mainly used by those who have visited the park before and know about them.  
  
  To ensure the model behaved in the way the group members have experienced at Magic Kingdom, the batch block was used.  The batch block was used to allow agents to be grouped together before all the agents took the selected mode of transportation.  The batch size for the ferry was set to 600 agents, the batch size for the monorail was set to 360 and the batch size for the buses was set to 50.  When the model is running the batch size much reach capacity before it pushes the batch to the connected service block.  One limitation of the batch is that the model was not able to get the batch to push agents before the batch was full if enough time expired and would be an improvement for the next iteration of the model.  
  
  The service blocks were used to set the time ( in the form of the delay setting) it took each mode of transportation to get to the entrance to Magic Kingdom.  All times were set to a triangular distribution between 13 and 20 minutes with a mean time of 15 minutes.  THe reason for this was to equalize all transit times and determine what effect the time it takes to load each method has on the total time it takes to get to the park.  The resource pool was used in conjunction with the service to set the number of vehicles that can be used at one time to take people to the MK entrance.  The resource pool size for the ferry was set to 3, the resource pool size for the monorail was set to 10, and the resource pool size for the buses was set to 10.  These numbers were taken from the following sources: INSERT SOURCES.
  
  the unbatch block was used to have all agents leave their respective method of transportation and head to the sink which represents the entrance to magic kingdom.  TimeMeasureStart and TimeMesureEnd blocks were inserted to log the time it took each agent to get to the entrance and to calculate a few statistics such as mean time, min time and max time.
  






## References


Ahmadi, R. H. (1997). Managing Capacity and Flow at Theme Parks. Operations Research. https://doi.org/10.1287/opre.45.1.1

Cheng, S., & Lin, L. (2013). An agent-based simulation approach to experience management in theme parks. In Winter Simulation Conference (pp. 1527–1538).

Gigliotti, A. R., Russell, A., & Gentry, R. J. (2016). It’s a Small World: Worldwide Declining Attendance and Disney Theme Parks. SAGE Business Cases Originals.

Richardson, S. (2014). 9 things you never knew about the Walt Disney world monorail system. https://www.themeparktourist.com/features/20141219/29760/10-things-you-never-knew-about-disney-world-monorail-system

Solmaz, G., & Turgut, D. (2017). Modeling pedestrian mobility in disaster areas. Pervasive and Mobile Computing, 40, 104–122. https://doi.org/10.1016/j.pmcj.2017.05.005

Spence, J. (2011). Transportation and ticket center - TTC. http://land.allears.net/blogs/jackspence/2011/04/transportation_and_ticket_cent.html

WDWMAGIC: An Unofficial Walt Disney World Fan Site. *Facts*. https://www.wdwmagic.com/facts!.html

https://forums.wdwmagic.com/threads/never-go-to-the-park-without-a-bag.935235/



## Image References
http://www.disneyeveryday.com/free-rides-at-the-richard-petty-driving-experience-in-walt-disney-world/

http://www.chipandco.com/monorail-happy-hour-adult-escape-87063/

https://www.undercovertourist.com/blog/rent-or-ride-car-rental-considerations-for-your-orlando-vacation/

https://itsofftoneverland.wordpress.com/tag/magic-kingdom/page/2/

https://www.tripsavvy.com/the-ultimate-guide-to-disney-world-transportation-4149857
