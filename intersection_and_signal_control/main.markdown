# Intersections and traffic signals

 BRT Standard: Intersection treatments | POINTS
---------------------------------------------------------------------------|------------
All turns prohibited across the busway | 6  
Most turns prohibited across the busway | 5  
Approximately half of the turns prohibited across the busway and some signal priority | 4
Some turns prohibited across the busway and some signal priority | 3 
No turns prohibited across the busway but signal priority at most or all intersections |  2
No turns prohibited across the busway but some intersections have signal priority | 1 
No intersection treatments	| 0							

            

### Chapter overview

The objective of this chapter is to equip the reader with the tools required to optimally design the layout and operation of intersections along the proposed BRT corridors. Intersections are points where BRT vehicles can incur in significant delay and points where the BRT project has the most perceived impact on mixed traffic.

An important strategy to improve the performance of intersections to better accommodate public transport and other vehicles is to restrict general-traffic turning movements at intersections. The BRT Standard awards up to 6 points for good handling of BRT movements through intersections, with the most points given to systems which prohibit all turns across the busway. 

Besides the above, this chapter also discusses the treatment of public transport vehicle turning movements, which are desirable, but equally harms intersections performance and the placement of stations relative to intersections along the corridor. Traffic-signal technology to provide public transport vehicles with priority are discussed too.

## Introduction

Intersection are areas where two or more roads encounter each other. 
The use of the word in Traffic Engineering technical environment implies in "roads for vehicles" and "at the same level",
but very often the expressions "at-grade intersections" or "single grade intersections" are used to confirm the concept;
for fly-overs and underpasses the term used is "interchange" or still "separated-grade interchange".
When more than one mode is involved, the common traffic engineers wording is "crossing", 
and one of the road is assumed to be a "carriageway",
as in  "pedestrian crossing".

By this definition, intersection implies in conflicts for vehicles to use the same space,
and can refer to an unidirectional T-shaped or Y-shaped confluences;
the conflicts there gets clear when there is no space to accommodate the two incoming
flows on the exiting stream in a congested situation.

Conversely a channelled Y-shaped junction may not be an intersection.

![high volume in an Y-shaped intersection](img/crowded-Y_junction.gif  "a crowded Y junction is an intersection")

![channelled Y-shaped intersection](img/chanelled-Y-junction.gif "a chanelled Y junction is not an intersection" )

A bi-directional T-shaped junction is clearly an intersection, as there are several conflicts to the use of the space.

Ideally a separated-grade traffic solution eliminates intersections, but in practice, due to space restrictions, intersections eventually remain.

![separated-grade solutions with and without intersections ](img/sep-grade-solutions "Separated-grade solutions may not eliminate intersections" )

As conflicts get more intense

## Basic Concepts

We present here only the concepts needed to understanding the equations that are included in this chapter, the reader may further investigate the concepts of traffic density and traffic headway, and how they relate with traffic average speed and traffic flow.

Before that, we emphasize that when applying formulas, attention should be given to units and units conversions, as the appropriate dimension to perceive phase times in traffic lights or the time to walk or ride a few blocks is seconds while we better perceive speeds in kilometres or miles per hour. It is useful to remember that 1 hour is the same as 3600 seconds and one mile is approximately 1.6 kilometres and 1 kilometre is approximately 0.6 miles.

###### pcu

A passenger-car unit, or pcu is a reference used to bring different vehicle types to a common denominator. The conversion factor from a certain type of vehicle to a passenger car unit depends of application intended after the conversion, being eventually calibrated for an specific use in an specific situation (for example if stress upon the pavement or congestion potential is considered, if such is in urban environment or in a highway, in a ramp or in plain terrain).

In any case, a motorcycle for example tends to have an equivalent of less than one vehicle, and a mini-bus is equivalent to more than one vehicle, the larger and heavier the vehicle, higher the equivalence is.

###### Speed

For application with the concepts outlined in this chapter, speed is to which we use the letter V from the synonymous velocity, is the average traffic speed of all vehicles in a segment. It would be measured by the mean time all vehicles crossing the segment divided by the segment extension. Under our modelling intents (that is capacity evaluation) it can be imagined that all vehicles are moving in that speed.

###### Flow 

Traffic engineering borrow concepts from fluid mechanics and uses "flow" as a measure traffic intensity.
Flow can be expressed by the number of vehicles crossing a transversal section (like a stop line) during a certain time interval.
Flow is usually represented by letter q in equations, but we will avoid that here and use the full word instead.

It should be noted the use the word "volume" to express the same idea is generally accepted even it is conceptually wrong; volume should refer to total number of vehicles in the same way litres refers to volume and litres/second refers to flow in hydraulics. The term is specially common in the expression "volume/capacity ratio".

###### Capacity

Capacity, by its turn is defined as the maximum flow a section can handle. As mentioned in Chapter 8, capacity and speed are related concepts and the maximum flow does not happens when speeds are maximum. This happens due to the fact that the distance a driver maintains from the vehicle in front of it raises more than proportionally than the speed increase. The speed maximum capacity occurs in a section of unconstrained road is between 60 and 80 kph (km/hour), being subject to local road conditions, including: width of lanes, number of lanes of the section, ramp inclination, visual surrounding and cultural driving behaviours.

As a general rule, for urban environment, the capacity of a lane is 1800 pcu/hour. For the purpose of capacity measuring an 18-metres-articulated bus is equivalent to 2.5 car-passengers-unit. Therefore, in a busway section with no interference, the capacity per lane is 720 articulated buses/hour.

The capacity of a segment is given by the lower capacity of a section within it, the term "bottleneck" for the lower-capacity-section express this concept quite clearly.


###### Traffic sign times

In this chapter, cycle time alone refers to a traffic light cycle time.


###### Intersection capacity

Considering the definition of intersection as the area where vehicles come into conflict, the capacity of the intersection will be measured as the total number of (equivalent) vehicles that crossed it (meaning 



