# IDS6145(SimTech 2018) - DISNEYWORLD "MAGIC KINGDOM" GUESTS ENTRANCE SYSTEM

# MouseHeadz
![**Mickey.png**](images/Mickey.png)

> * ADAM HARDNEY
> * BLAKE NGUYEN
> * MICHAEL STERKEL
> * RACHEL STRANEY
> * Project Title: MAGIC KINGDOM GUESTS ENTRANCE SYSTEM

# Abstract
Magic Kingdom, at Walt Disney World in Orlando Florida, has lived up to its tagline as being "The most Magical Place on Earth" by becoming one of the most visited theme parks in the world. According to the Themed Entertainment Association Global Attractions Attendance Report in 2015, Walt Disney's Magic Kingdom hosted over 20 million vistors. (http://www.teaconnect.org/images/files/TEA_160_611852_160525.pdf). For anyone who has the visited Magic Kingdom theme park, the size of the crowds can affect guests' overall experience and impose safety issues. Compounding this issue is the bottleneck created by the Transportation and Ticket Center (TTC) where guests must take the water ferry, monorail or bus to get to the official main street entrance to Magic Kingdom. The goal of our system is to model the time it would take guests to arrive at Magic Kingdom based on which mode of transportation taken from the TTC.



![**MKE.png**](images/MKE.png)

(directions, - remove)
* (this Readme should "evolve" over time as you add and edit it)
* (once you are happy with it - copy it into the proposal directory, and remove the obvious sections that should be removed - Future work, etc)


## General Introduction


Walt Disney theme parks are one of the most well-known amusement parks in the world. Specifically, Magic Kingdom, which is located in Orlando, Florida is popularly known as the most happiest place on earth. The popular title is due to the innovation of Walt Disney himself. Walt Disney built his first theme park in Anaheim, California, known as Disneyland. When he first built Disneyland, he ran out of property to build so he sought out more property in Orlando, Florida. He then began to build Disney World theme park in Orlando, Florida. From our initial research, we found that Disney's Magic Kingdom averages about 53,000 guests per day. We can assume that the high volume of guests that visited the theme park can experience extensive wait times to travel from the transportation and ticket center (TTC) 


(States your motivation clearly: why is it important / interesting to solve this problem?)
(Add real-world examples, if any)
(Put the problem into a historical context, from what does it originate? Are there already some proposed solutions?)

(You should begin by introducing your topic. In this section, you should define the core terminology specific to the field, introduce the problem statement, and make clear the benefits (motivate!) of resolving that problem statement. The main difference between the ABSTRACT and Introduction sections is that the abstract summarizes the entire project, including results, whereas the introduction only provides the motivation of the problem and an overview of the proposed solution.)

(I tell students to answer the questions, one paragaph each to start if you are lost)

(Problem Statement. One paragraph to describe the prob-lem that you are tackling.)

(Motivation. Why is this problem interesting and relevant to the research community?)

(Proposed Solution. How do we propose to tackle this problem (that has been identified in the previous para-graphs, is interesting to the community, and has yet to be tackled by other researchers)?)

(Contributions. An enumeration of the contributions of the senior design project)

(This project makes the following contributions:)(you must have this!!)
•	(Contribution 1)
•	(Contribution 2)



## The Model

(Provide structural and behavior diagrams of the system you wish to study.) (Why is your model a good abtraction of the problem you want to study?) (Are you capturing all the relevant aspects of the problem?) (Use the model to tell us what is going on.)

(explicitly list your requirements of what the model will have and simulate for the proposal)

## Fundamental Questions
In order to make a final determination on the function of a designed system a series of fundamental questions must be asked and answered.  For this system, which involves transportation methods to and from Magic Kingdom, the following questions apply.

The overarching fundamental questions are

- Which transportation method (Monorail, Ferry, Bus or Minnie Van) is the quickest method to get from the Transportation and              Ticket Center to the entrance to Magic Kingdom?
	
- Does the design of the Transportation and Ticket Center create a bottleneck during high volume times that could lead safety            issues for the visitors?
	
- Does the design of the Transportation and Ticket Center lead to uneccessary wait times that can lead to a negative visitor             experience?
		
The sub questions that flow from the 3 funamental questions are
		
- What is the time, in minutes, that it takes to get to the Magic Kingdom Entrance from the TTC via the water Ferry, via the Monorail, via the buses adn via the Minni Vans?
			
- What is the capacity of the water Ferry, Monorail, bus and Minnie Van, respectively?
				
- How often to each of the four methods run?
- Are any of the transportation methods on a set schedule?
		
- Does travel time of the four methods vary depending on the time of day?
- What are the hours of operation of the four transportation methods?
- Is there a cost associated with each of the transportation methods?
		
- If there was an emergency could park visitors exit the park in a safe and efficient manner?
	
(At the end of the project you want to find the answer to these questions) (Formulate a few, clear questions. Articulate them in sub-questions, from the more general to the more specific. )

(From Mike) I'll have my section completed on 23 Feb, hopefully not too late in the day either.

## Expected Results

The fundamental questions are to be answered by the simulation created to represent the system.  However, before the simulation is built there are notions of what answers to some of the questiosn will be and the simulation will be used to determine if these pre stated answers are correct. 

The expected results for travel time are that the buses and Minnie vans are the quickest route into the park, that the monorail is the second quickest route and that the ferry is the slowest route into the park.  Using google maps and its measuring tool to determine the distance of the bus route (and the Minnie Van route), the distance comes to about 1.12 miles, the distance the Monorail takes comes to about 1.56 miles and the distance the ferry takes is about .67 miles.  

For this system the time it takes to travel from the TTC to the MK entrance, regardless of transportation method, is expected to increase during peak visiting hours during the day.  This expectation is from personal experience at the parks during peak times and the perception that the time it took was statistically significantly longer.  This also applies to the direction of travel.  Getting into the park during normal business hours is expected to take longer than exiting the park and conversely as the park is nearing closing time the time to get into the park will decrease will the time to get out of the park will increase.

All modes of transportation are expected to run during the entire time the park is open except when a mode is not running due to a mechanical issue.

The expectation, before running the simulation, is that a bottleneck is created at the TTC during peak hours due to not being designed to handle the current capacity it receives at peak hours.

All modes of transportation, excluding the Minnie Vans, are included in the price of admission, while a ride in a Minnie Van is $20 per ride.

For the presented system the data will be presented in the form of line graphs, scatter plots and histograms.

A histogram will be used to plot the average time (in minutes) it takes to get into the park by the four different modes of transportation.

![Histogram Example](images/HistogramExample1)

A scatter plot will be used to track transit times (in minutes) of individual agents.  The scatter plot will visually show where most of the transit times fall.

![Scatter Plot Example](images/ScatterExample1)

A line graph will be used to show the change in transit time (in minutes) as the time of the day changes from the time the park opens until it closes.

![Line Graph Pot Example](images/LineGraphExample1)



(What are the answers to the above questions that you expect to find before starting your research?) (This changes from Expected (Proposal) to just Results (final report)) (you should verbally define them) (sketch a few graphs of what you are roughly going for - not the data but histogram of this, line graph of that, screen shot of an agent - use paper and pencil sketches)

So I'm not sure if this is correct.  The paragraph above says screen shot of an agent, though i'm not sure what it means by that.  Does it mean an agent in Anylogic or what an agent would be, which in our case are visitors to Disney.
**RS - I think we only need to describe an agent if we plan to use agent-based modeling.
QUESTIONS TO YOU ALL: which mode of transport will be the fastest - bus, rail or ferry? And why?
** 


![Mike Space Mountain](images/MikeSpaceMountain.png)

## Research Methods
(Cellular Automata, Agent-Based Model, Discrete Event Continuous Modeling...)(Python or Anylogic) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards) (Steps in the process)

- Past research has been conducted to estimate visitors at amusement parks and evaluate guest traffic flow. A few relevant publications to our project include:
	- Managing Capacity and Flow at Theme Parks by Reza H. Ahmadi
		- Focused on the Six Flags Magic Mountain theme park to address questions of daily operations such as managing traffic flow in the park and suggesting routing tours for guests. In his paper published in Operations Research, Ahmadi constructs two mathematical models to design touring plans of the park to avoid congestion. He also defined a Flow Pattern Model to identify visitor transitions within the park moving from one location to the next.
		- Data used in the analysis included primary data from a visitor questionnaire and direct measures provided by the park which included park attendance and queue lengths at rides.  
		
- It's a Small World : Worldwide Declining Attendance and Disney Theme Parks by Robert Gigliotti, et al.
	- This is a report published through Disney with a purpose of assessing markets and competition in the theme park industry. The main points of interest from this report include attendance projections. Although this report was partially published in response to the decrease in attendance during recession years, the information summarized is from a direct and relevant source. 
- Modeling Pedestrian Mobility in Disaster Areas by Gurkan Solmaz and DamlaTurgut
	- This study focused on the foot traffic patterns of guests in amusement parks to evaluate mobility in the event of a disaster. The researchers used information collected from mobile devices carried by 11 volunteers to simulate visitor movement and travel around the park. The simulation used in the study was an agent-based model.

- An agent-based simulation approach to experience management in theme parks by Shih-Fen Cheng, et al.
	- This paper was presented at the 2013 Winter Simulation Conference. The researchers developed and constructed a very large agent-based model. 

	- <font color="red">Taken directly from Shih-Fen Cheng paper:
The tourism and entertainment industry plays an increasingly important role in global economy. In recent years, theme parks have been an important driver in the growth of the tourism and entertainment industry. Unfortunately, vibrant growth in the theme park industry comes hand-in-hand with worsening congestion and increased wait times. From field observations and our computational experiments, we can conclude that there are at least three major causes for severe congestions to happen predictably in a theme park: 1) the fact that a small set of highly popular attractions are preferred universally, 2) the design of connecting paths that would cause visitors to converge at a few bottlenecks, and 3) the lack of global information on both real-time and historical queue lengths at attractions.<br /><br /></font>
	- Crowd diversion systems have been an area of focus for the theme park industry for a while. Disney's FASTPASS and Universal Studios' Express Pass have both been implemented to reduce lines and wait times once guests are inside the park. (Shih-Fen Cheng, 2013)However, these solutions do not extend beyond that. Specifically, these strategies do very little to remedy the time it takes guests to enter the park.

- Analysis and Simulation of Theme Park Queuing System by Liou Chu, et al.
	- Chu and his team describe the strategies they used to design a Theme Park Queuing System and how it was used to improve customer satisfaction. 
	- According to Ohtani, a cited reference by the researchers, wait time before being served is one of the most significant factors to customer satisfaction.  
	- Although the authors modeled multiple rides within a theme park using Arena, this work can be generalized to our research by substituting rides with the main queuing points of the Magic Kingdom entrance, namely, the ticketing & transport center and the three modes of transport.  

**Rachel Notes: 
- Can we combine a queue (discrete-based) with agent based model? For example, our agents would be visitor groups... with attributes (family vs adults, avg age, etc.). Then we can simulate transportation for different types of visitor groups. Thoughts?
**

Although there are several approaches to simulating foot traffic and movement throughout an amusement park, our team has elected to develop a discrete-event based model to address the said research topic. As described in the Model section, there are assumptions and parameters that need to be estimated to develop a meaningful simulation. Specifically, resources mentioned above and others will assist us in identifying the following:
- Daily park attendance by way of the parking lot (this may be estimated by total parking spots)
- Typical travel time required for each mode of transport into park (bus, ferry, monorail)
- Typical wait time in line at the transport center

To simplify our scope, our system is focused on the point at which a guest parks to the point they reach the park entrance.



## (Other)
(change the title and amount of headers as needed) (mention datasets you are going to use) (mention base code or examples you)

## Discussion
(final only - remove whole section for proposal Readme) (What would you have done differently) (What are the contributions summerize)(what is the big take away)(what did you learn)

## Future Work
(final only - remove whole section for proposal Readme) (if you had 6 more months what would be the next steps in this project.) (What are a few questions you have now)

## References
(Add the bibliographic references you intend to use)  (Code / Projects / blogs / websites / papers...)


Ahmadi, R. H. (1997). Managing Capacity and Flow at Theme Parks. Operations Research. 
https://doi.org/10.1287/opre.45.1.1
Cheng, S., & Lin, L. (2013). An agent-based simulation appraoch to eperience management in theme parks. In Winter Simulation Conference (pp. 1527–1538).
Gigliotti, A. R., Russell, A., & Gentry, R. J. (2016). It’s a Small World : Worldwide Declining Attendance and Disney Theme Parks. SAGE Business Cases Originals.
Solmaz, G., & Turgut, D. (2017). Modeling pedestrian mobility in disaster areas. Pervasive and Mobile Computing, 40, 104–122. https://doi.org/10.1016/j.pmcj.2017.05.005
