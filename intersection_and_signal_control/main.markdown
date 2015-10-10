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

The objective of this chapter is to equip the reader with the best practice tools required to design the layout and operation of intersections along the proposed BRT corridors. Intersections are points where BRT vehicles can incur in significant delay and points where the BRT project has the most perceived impact on mixed traffic and walking.

An important strategy to improve the performance of intersections to better accommodate public transport and other vehicles is to restrict general-traffic turning movements at intersections. The BRT Standard awards up to 6 points for good handling of BRT movements through intersections, with the most points given to systems which prohibit all turns across the busway. 

Besides the above, this chapter also discusses the treatment of public transport vehicle turning movements, which are desirable, but equally harms intersections performance and the placement of stations relative to intersections along the corridor. Traffic-signal technology to provide public transport vehicles with priority and techniques to provide safety to pedestrians and cyclists are discussed too.

## Introduction

Intersection is the area where two or more roads encounter each other. 
The use of the word in Traffic Engineering technical environment implies in "roads for vehicles" and "at the same level",
but very often the expressions "at-grade intersections" or "single grade intersections" are used to confirm the concept;
for fly-overs and underpasses the term used is "interchange" or still "separated-grade interchange".
When more than one mode is involved, the common traffic engineers wording is "crossing", 
and one of the road is assumed to be a "carriageway", as in  "pedestrian crossing"; recently the term "multimodal intersection" has been applied.  

By this definition, intersection implies in conflicts for vehicles to use the same space,
and can refer to an unidirectional T-shaped or Y-shaped confluence area;
the conflicts there gets clear when there is no space to accommodate the two incoming
flows on the exiting stream in a congested situation.

![high volume in an Y-shaped intersection](img/crowded-Y-junction.png  "a Y junction that is an intersection")

Conversely a channelled Y-shaped junction may not be an intersection.

![channelled Y-shaped intersection](img/chanelled-Y-junction.png "a chanelled Y junction that is not an intersection" )

Considering the majority of cases of two or more roads meetings where there are many possible turning movements -- not all conflicting, intersections can be seen as several adjacent intersections as well. 

Once footpaths (or "roads for people") are more important to accessibility in populated areas, carriageways are usually constructed between footpaths. When two carriageways encounter, several walkways crossings are adjacent. So, a multimodal intersection encompasses a larger area where people conflict to use the same space. For clearance, let us remember that drivers and passengers are people.

The higher the number of conflicts in an intersection or in a crossing, higher is the time people will need to cross it safely.

If the frequency of vehicles arrivals at the intersection -- pedestrians and vehicles at a crossing -- is low, eventual passage negotiating is enough to maintain safety without compromising travel time.

If over the years the vehicle frequencies along the day rise to the point where queues happen often and last long or the time required to pedestrians to cross safely becomes too long is the moment to intervene.

An interference is justified by the comparing the present value of costs for its implementation, maintenance and operation against the value of its benefits, of which the most easier to establish are the time savings assuming a safe operation and does directly related to it (as fuel consumption and pollution).

Interventions start with zebras and yielding signs. Channelling the vehicles and creating refuge islands is a manner to clearly divide an intersection in the several smaller intersection components, improving traffic safety and reducing the overall delay; roundabouts or mini-roundabouts are ways to channel vehicles as well. Above a certain point, traffic lights are required, that may grow really complex in order to accommodate all conflicts; then traffic diversion and restricting direct movements come at play... until the grade separation becomes necessary.

Ideally a separated-grade traffic solution eliminates intersections, but in practice, due to space restrictions, intersections eventually remain.

![separated-grade solutions eliminate intersections](img/sep-grade-no-conflict.png "Separated-grade solutions may eliminate intersections")

![separated-grade solutions with remaining intersections ](img/sep-grade-solution.png "Separated-grade solutions may not eliminate intersections")


Once BRT vehicles may ride in mixed traffic and accessibility is paramount to BRT projects

## Basic Concepts

We present here only the concepts needed to understanding the equations that are included in this chapter, the reader may further investigate the concepts of traffic density and traffic headway, and how they relate with traffic average speed and traffic flow.

Before that, we emphasize that when applying formulas, attention should be given to units and units conversions, as the appropriate dimension to perceive phase times in traffic lights or the time to walk or ride a few blocks is seconds while we better perceive speeds in kilometres or miles per hour. It is useful to remember that 1 hour is the same as 3600 seconds and one mile is approximately 1.6 kilometres and 1 kilometre is approximately 0.6 miles.

###### Speed

For application with the concepts outlined in this chapter, speed, to which we use the letter V from the synonymous velocity, is the average traffic speed of all vehicles in a segment. It would be measured by the mean time all vehicles crossing the segment divided by the segment extension. Under our modelling intents (that is capacity evaluation) it can be imagined that all vehicles are moving in that speed.

Still matching the broader concept of speed -- the ratio of motion expressed in distance per unit of time -- it is useful to remember that given a segment length (D_segment, for distance), knowing the speed (V_segment) is equivalent of knowing the travel time (Time_segment) through the segment and vice-versa, as the equivalent equations show:

V_segment = D_segment / Time_segment  <-->  Time_segment = D_segment / V_segment

###### pcu

A passenger-car unit, or pcu is a reference used to bring different vehicle types to a common denominator. The conversion factor from a certain type of vehicle to a passenger car unit depends of application intended after the conversion, being eventually calibrated for an specific use in an specific situation (for example if stress upon the pavement or congestion potential is considered, if such is in urban environment or in a highway, in a ramp or in plain terrain).

In any case, a motorcycle for example tends to have an equivalent of less than one vehicle, and a mini-bus is equivalent to more than one vehicle, the larger and heavier the vehicle, higher the equivalence is.

###### Flow 

Traffic engineering borrow concepts from fluid mechanics and uses "flow rate" as a measure traffic intensity.
From that definition, the word "rate" is commonly dropped and "flow" alone becomes treated as physical quantity expressed by the number of vehicles crossing a transversal section (or cross-section, like a stop line) during a certain time interval. Flow is usually represented by letter q in equations, but we will avoid that here and use the full word instead.

It should be noted the use the word "volume" to express the same idea is accepted even it is conceptually even more far from the original definition (fluid mechanics original comparative term would be "volume flow rate" even "mass flow rate" is more appropriated reference as the same number of vehicles can be compressed); volume should refer to total number of vehicles in the same way litres refers to volume and litres/second refers to flow in hydraulics. The term is specially common in the expression "volume/capacity ratio", which makes particular sense.

###### Capacity and Saturation 

The capacity (flow rate) of a segment is given by the lower capacity of a section within it, the term "bottleneck" for the lower-capacity-section express this concept quite clearly.

The capacity of a section by its turn is defined as the maximum flow a section can handle under prevailing use. It is subject to the number of lanes, width of lanes, ramp inclination, the use of surrounding areas --  as parking and stopping regulations, presence of intersection or traffic light ahead, bus stops existence and frequencies and  cultural driving behaviours.

Capacity can be easily and objectively measured, but some of the influential factors cannot. Many models have been developed to improve forecast of road capacity based on the knowledge of design and use of surrounds and even the more detailed simulators needs careful calibration to correctly represent driver behaviours changes, that tend to be unique to each place.

The simpler models commonly don't fit exactly to theories either and are usually adjusted by experimental evidence. These resort to the concept of *basic saturation*.

Basic saturation (flow rate) is the capacity for a section of a given standard ideal carriageway, divided by number of lanes of that given standard carriage way.

Capacity and speed are inter-dependent and the maximum flow does not happens when speeds are maximum. This happens due to the fact that the distance a driver maintains from the vehicle in front of it raises more than proportionally than the speed increase. The speed maximum capacity occurs in a section of unconstrained road is between 60 and 80 kph (km/hour).

Capacity models then define a way to forecast a *saturation flow* multiplying the basic saturation flow by adjustment factors to account for various non-ideal geometric, traffic, and environmental conditions of a given section, such as number of lanes, lane width, heavy vehicles, grade, parking facilities, bus blockage, area type, turning traffic along the segment, radius of turnings, pedestrian crossing traffic, but not considering traffic lights.

Saturation (flow rate), therefore, is the capacity of a section that is not under the influence of traffic light; for section that approach the traffic light, saturation is the capacity assuming a constant green, which would equal to the flow observed during the queueing discharge. For this reason saturation maybe called discharge (flow rate).

A practical rule, even distorting a bit the concept of ideal conditions is that: for urban environments, the basic saturation of a lane is 1800 pcu/hour. For the purpose of capacity measuring an 18-metres-articulated bus is equivalent to 2.5 car-passengers-unit. So in a busway, the basic saturation per lane is 720 articulated-bus/hour.





###### Traffic sign times

In this chapter, cycle time alone refers to a traffic light cycle time.


###### Intersection capacity

Considering the definition of intersection as the area where vehicles come into conflict, the capacity of the intersection will be measured as the total number of (equivalent) vehicles that crossed it (meaning 


Similarly to most of other design decisions that affect infrastructure needs, this is made considering the peak conditions, and to represent the peak we both use and measure the busiest hour of the day (as a reminder: we survey data with smaller intervals than on hour, so a given measure of busiest hour might have happened from 7:15 AM to 8:15 AM for example).


