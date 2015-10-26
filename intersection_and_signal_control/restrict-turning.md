
 ## Restricting General Traffic Turning Movements

**"Change means movement. Movement means friction. Only in the frictionless vacuum of a non-existent abstract world can movement or change occur without that abrasive friction of conflict."** - Saul Alinsky, political activist, 1909 – 1972

The overall capacity of the intersection is given by the sum of the capacity of each approaching lane. By its turn, the capacity of each approaching lane is given by the sum of saturation flow of the lane multiplied by the sum of relative green times of the phases the lane is active.

No matter how many phases there is on the traffic light, the sum of relative green for all vehicular phases with relative lost time is constant (if there was no pedestrian phases, it would be equal 1). The initial step to programming traffic lights is divide this fixed amount among the phases. With the general assumptions that a movement not allowed during a given phase will block a lane and that the saturation flow per lane is the same (for turning it can be lower): for any given signalized intersection, if a phase is removed (therefore the movements of that phase) and the green time and approaches for the movements of the removed phase are incorporated into another phase the overall capacity of the intersection will necessarily increase.

This is empirically clear for a relatively balanced intersection, a larger number of phases in a traffic light means waiting longer and having a lower share of green time.

Of course it is not interesting to create capacity for movements without demand, the following subsections will discuss alternatives to divert traffic in order to increase capacity by eliminating phases. We will see that in some cases, intersection capacity still is increased even if the demand for eliminated movements, namely cross-traffic turns are forced to pass over the intersection twice.

Widening the intersection can be of great assistance, but rarely to the point it can achieve the same benefits of reducing phases. If widening is possible, it shall be done in order to permit reducing the number of phases to two.

\startbox(narrowing-lanes)

###### Narrowing lanes

Narrowing lanes is a recognized traffic calming measure and a possible way to increase the intersection approach capacity. Even the saturation flow will be reduced in each lane, if one more lane can be squeezed in the stop line, capacity may increase and a better use of space for queueing is promoted.

Places where congestion is a serious issue may already have addressed regulation that allows using narrow measures, if not Public Works guidelines have to be changed.

US Federal Highway Administration suggests that, despite desired lane width of 3.6 metres to maximize flow, right-of-way or pedestrian needs may dictate use of a narrower lane width; lane widths bellow 2.7 metres are not recommended for new design, but in some very constrained retrofit situations on low speed roadways, lane widths as low as 2.4 m should be considered where appropriate (figure \fignum(montgomery-narrow-lane)).

![montgomery-narrow-lane](montgomery-narrow-lane.png "Lanes as narrow as 2.4 metres are an effective way to improve intersection capacity, as in this intersection in Montgomery County, Maryland, US. Image from Google Earth.")
\endbox

### Eliminating intersections

The extreme case of reducing phases would let only one phase, which would be equivalent to eliminate the intersection itself, clearly increasing capacity. 

Thus eliminating intersections along the busway seems at first a good idea. For median-side busway this can be provided by simply forbidding cross-traffic, while still allowing flow from transversal street join the mixed-traffic in the corridor to the kerb-side as in figure \fignum(quito-closed-cross) providing access to the corridor.

![quito-closed-cross](quito-closed-crossing.jpg "Prior to Quito’s Ecovía line, mixed-traffic vehicles were allowed to cross through this intersection as well as negotiate cross-traffic and kerb-side turns. To give priority to public transport, crossing straight  and cross-traffic turn movement have been blocked. Photo by Lloyd Wright.")

The flaw in adopting such extreme solution is that eliminating phases is based on diverting traffic demand for the excluded movements, so its movement can be done with other flows. Eliminating the movement (in this case, crossing the corridor) does not eliminates the demand for it; the movement has to happen somewhere else.

This measure indistinctly applied will reduce accessibility and concentrate demand in few locations (figure \fignum(permeability)). Before eliminating an intersection, it is necessary to understand which alternatives paths the demand will use to cross the corridor and compare the impacts of both situations: if the volumes are low or if the alternatives will not cause more delay to the BRT then it is really a good idea eliminate the intersection.

Eventually, creating new intersections, to split conflicting volume of one intersection into several is the needed strategy to increase green times for the BRT.

![permeability](img/permeability.png "Closing intersections reduces accessibility, and may lead to harder to handle interesections. ith no stations, BRT vehicles can benefit from signal coordination. Image courtesy of Elebeta.")

If there are no stations in the surrounding, then BRT vehicles can pass through several intersections at once if a synchronised signal system is used (see sections \sectionnumname(coordination) and \sectionnumname(passive-signal-priority)), however, when there is stations between intersections, the BRT vehicle will pass through the green phase at the first intersection and then stop at the station for passenger boarding and alighting. By the time the vehicle resumes movement towards the second intersection the signal phase may have changed to red (figure \fignum(BRT-fail-synchro)).

![BRT-fail-synchro](img/BRT-fail-synchro.png "Coordination for mixed-traffic does not sot applies to BRT corridor when there is station between intersections. If the green time of green wave has the same magnitude of total dwell time at stations, the effect can be particularly harmfull, as it increases the chances that BRT arrival at intersection be during the red time.")

But when intersections are too close together in order to optimise the station location relative to them, an assessment has to be made in terms of how important the station location is for boarding and alighting passengers against the detour forced to mixed traffic to close the station and hindering the whole BRT system due to interference between the station and the intersection. There are three options:

1. Close one of the intersections: generating mixed-traffic detour time and higher cross volumes in other points that may impact the BRT corridor as well;
2. Transfer or remove the station: generating walking time for BRT users of that station;
3. Keep station and intersections: generating delay for all passengers in the BRT the pass through the intersection.

Even for normal mixed traffic, having two intersections too close together will sometimes lead to problems of the same nature of the discussed in sections \sectionnum(Minimum Recommended Distance between the BRT Station and the Intersection from mixed-traffic perspective and \sectionnum(Minimum Recommended Distance between the BRT Station and the Intersection from BRT perspective): vehicles queued at one intersection will back up to the point where vehicles are unable to clear the previous intersection during a green phase.

Equation \eqnum(dist-inters-mixed-traffic) bellow  defines the calculation for the distance above which this type of conflict shall not occur.

![eq-dist-inters-mixed-traffic](eq-dist-inters-mixed-traffic.png "D_{i1-i2} >= 3 * Max(T_{green-i1} , T_{green-i2})")

where:
D_i1-i2 = Distance in meters between intersection 1 and intersection 2;
T_green-i1 = Green signal time in seconds at intersection 1 
T_green-i2 = Green signal time in seconds at intersection 2 

A mixed traffic lane can generally handle 1,800 vehicles per hour.  This quantity translates to two vehicles per second (3,600 seconds in an hour).  When vehicles are stopped at a stop light, the average amount of space they take up is 6 metres; this space includes the vehicle and some space between vehicles.  This average vehicle distance means that for each second of time, 3 metres of vehicle-equivalents can be moved through the intersection.  

This distance between the intersections guarantees that there is enough space to queueing vehicles, so that it does not happens that the green light is open and there the vehicles are stuck in the upstream traffic light. Proper synchronization can reduce this distance practically to zero.

###### Example

The following scenario is outlined in order to determine whether two intersections apart 100 metres from each other  will result in free-flow operation or in congestion:

D_i1-i2 = 100 metres;
T_green-i1 = 40 seconds; 
T_green-i2 = 30 seconds.

To determine if the distance between these intersections is sufficient,equation  \eqnum(dist-inters-mixed-traffic)can be applied:

100 >= 3 * Max (40,30) 
100 >= 120  <-- FALSE

Since 100 metres is less than the required 120 metres, there is not enough space between the intersections. 

In the direction from 1 to 2 it is possible (if 2 is red while 1 is green) that vehicles queuing at 2 will back-up onto the first intersection and the last 20 metres of queue will be trapped before intersection 1. 

In the direction from 2 to 1 it is possible (if 1 green start the same time the first vehicle from 2 arrives at the intersection) that the last 10 seconds of green in 1 will be useless, since vehicles stop flowing after 30 seconds  in intersection 2.


### Eliminating movements

#### Typical 4-phases-intersection

In a typical that allows all movements (figure \fignum(twelve-moves)), four phases are required; usually each origin has its phase (figure \fignum(typical-four-phases)) but an alternative scheme with one phase for each direction (two ways) straight movement and kerbside-turns and one phase for each direction (two ways) cross-traffic turn may be used as well (figure \fignum(cross-traffic-four-phases)).

![twelve-moves](img/twelve-moves-3ed9.5.png "Possible movements at a typical four-leg intersection. Image courtesy of ITDP.")

![typical-four-phases](img/typical-four-phases-3ed9.7.png "Typical four-phases diagram. Image courtesy of ITDP")

![cross-traffic-four-phases](img/cross-traffic-four-phases-3ed9.6.png "Alternative four-phases diagram. Image courtesy of ITDP.")

The typical configuration has the advantage of not requiring dedicated queue space (queue box) for cross-traffic turns and also allow sharing one lane for cross-turn and straight movements (it can be the most median-side or the second close to it). The scheme with phases for cross-traffic-turn only are interesting when its flows are relatively low and straight movements are intense in both ways (cross-traffic-turn phase will be short and straight will be long)

A composition of the two is also possible, using cross-traffic-turn phase for one direction, and one phase per origin in the other direction (figure \fignum(mix-typical-and-cross-turn)).

![cross-traffic-four-phases](img/cross-traffic-four-phases-3ed9.6.png "Mixed four-phases-diagram. Image courtesy of Elebeta.")

#### Movements conflicting with BRT

When the BRT has to cross a typical four-staged intersection, the main concern is to increase the green time for the corridor direction. Eliminating phases are likely to be very effective in doing so, but it is important to keep in mind that it is not the primary goal. Eliminate phases in a way that green time is not increased for the BRT approaches will improve only mixed-traffic performance.

To eliminate the phases we must focus in the **movements that conflict with the BRT** (figure \fignum(conflicting-movements))and try to reroute them in a form such that they can cross the corridor in one phase and briefly, i.e., providing width to the crossing movements approaches. Providing width to parallel movements is important to improve general traffic, which is also desirable, but not paramount.

For the reminder of the section we will assume that the bus way is median-side aligned and that the busway cross the intersection straight; if the busway is kerb-sided and/or it is turning between perpendicular roads, the same reasoning can be followed and the alternatives for detour mixed-traffic movements shall be considered, but in a different and appropriated way.

![conflicting-movements](img/conflicting-movements.png "With the insertion of BRT (red) conflicting movements(in blue) shall be addressed. Image courtesy of Elebeta.")

With a median-side BRT, typical four-phase stage can no longer be applied; once it will conflict for the cross-traffic turn, alternative cross-traffic turn stage has to be present in BRT direction (figures \fignum(four-phases-with-brt-one) and \fignum(four-phases-with-brt2)).

![four-phases-with-brt-one](img/four-phases-with-brt-one.png "With the insertion of BRT (red) in a four-stage signal, cross-traffic-turn from the same direction need to have own phase. Image courtesy of Elebeta.")

![four-phases-with-brt-two](img/four-phases-with-brt-one.png "With the insertion of BRT (red) the phases from other direction can still be one for each origin leg. Image courtesy of Elebeta.")

#### Diverting kerb-side-turns

Moving kerb-side turns away from the intersection is usually simple if parallel streets are available (figure \fignum(detour-kerb-side). Detouring the kerb-side flow from the crossing street is particularly interesting because it can leave the whole approach width available to the conflict movements, reducing the crossing time (red for the corridor) in the same proportion this kerb-side-turn flow is to the total flow, even if four-phases are in use (figure \fignum(shorter-four-phase)).

![detour-kerb-side](img/detour-kerb-sid.png "Kerb-side-turn detour can leave width in the main intersection available to crossing flows. Image courtesy of Elebeta.")

![shorter-four-phase](img/shorter-four-phase.png "Without kerb-side-turn, cross street phases will be shorter. Image courtesy of Elebeta.")

#### Diverting cross-side-turns

###### Loop

###### Kerb-side and u-turn

###### U-turn and kerb-side

###### Previous turn

(displaced left-turn)


#### Diverting straight flow

The use of the imediate parallel street in one-way as an auxiliary street is an effective alternative for mixed-traffic. Even a narrow two-way street transformed into one-way street with parking prohibition in one-side can represent a three lane parallel corridor with larger capacity than the main corridor.r


It a common situation to main corridors, to  that auxiliary streets para

