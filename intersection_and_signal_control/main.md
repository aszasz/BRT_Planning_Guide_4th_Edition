# Intersections and traffic signals



 
 
 on 3rd Edition


 Chapter 9
 9.1 Evaluating the intersection
 9.2 Restricting turning movements
 9.3 Designing for BRT turning movements
 9.4 Station location relative to the intersection
 9.5 Roundabouts
 9.6 Traffic signal priority

 9.1 Evaluating

9.1.1 Intersection audits

9.1.2 Impacts of signal dealy

    eq. 9.1: Total signal delay
    
    Time_signal = Time_wait + Time_signal-queue

    eq. 9.2. Average delay

    Time_wait= T_red² / 2 * Time_cycle * (1 - Freq_actual / Freq_max)

    eq. 9.3: Random queing delay:

    Time_signal-queue = (X_signal - x)/(1- X_signal) / Freq_max

    (what is x? x = Freq_actual/Freq_max? )




    eq. 9.4: Signal saturation for the bus lane:

    X_signal = Freq_actual / (Freq_max * Time_green)
    
    
    T_green (1 - T_red/T_cicle)

9.2 Restricting turning movements

9.2.1 Techniques for reducing the number of signal phases
    9.2.1.1. at-grade
    9.2.1.2. grade-separated options

9.2.2. Integrating pedestrians and cyclist movements


9.3 Designing for BRT turning movements

9.3.1. Dedicated turning lane for BRT vehicles
9.3.2. Mixed traffic operation
9.3.3. BRT vehicle turning onto secondary street
9.3.4. Convert intersection into roundabout

    eq. 9.5:Capacity available for a given area:
    Capacity_available-area = width_available * length_available / Practical-Area

    eq. 9.6: Required capacity:
    Capacity_required = Freq_turning-vehicles * Time_cycle

9.4. Station location relative to the intersection
9.4.1. Stations on each side of intersection
9.4.2. SIngle median station near intersection
9.4.3. Locating the station away from the intersection
        9.4.3.1. Station to intersection interference levels

        eq. 9.7 ratio of stopping time to red signal time:

        K_red = Time_red / Time_dwell-in-station

        eq. 9.8. Resulting saturation of station dwell and signal times

        X0_signal_&_station = X_station * Time_cicle / (Time_cicle - Time_dwell-in-station * K_red)


        eq. 9.9. Average bus dwell time:
        
        Time_dwell-in-station = X_station/Freq_current   ( * 3600 second/hour )

        9.4.3.2 Maximising right-of-way with mid-block-stations

        9.4.3.3. Otpimisation of station location when walking time is included

        9.4.3.4. Calculating the minimum distance to avoid station-intersection conflits

        eq. 9.10 Station minimum distance from intersection

        Dist_station-signal > N_queueing-vehicles * Length_vehicle

        eq. 9.11 Queuing vehicles at the signal

        N-signal-queing-vehicles =  Time_red * Freq_actual / ( 1 - Freq_actual/Freq_max) 

        9.4.3.5. Optimising station location when intersections are close together

        eq. 9.12 Distance to avoid conflict between signalised intersections

        Dist_1-2 = 3 * Max (T_green1 , T_green2)

9.4.4. Grade-separated stations

9.5. Roundabouts

9.6. Traffic signal priority

9.6.1. Passive signal priority
9.6.2. Active signal priority
    eq. 9.13 optimal distance for terminate the busway ahead of a mixed traffic bottleneck
    Dist_ahead-bottleneck ~3 * Time_green

4th Edition - Chapter 8. Traffic-impact assessment

8 Traffic-impact Assessment
	8.1 Requirements for a Traffic Impact Assessment
	8.2 Data Needs
	8.3 Study Area and Extent of Assessment
	8.4 Level of Analysis
    8.5 Estimating Traffic Volumes
	8.6 Methodologies and Performance Measures	
	8.7 Mitigation

    Overview

	8.1 Requirements for a Traffic Impact Assessment 
    = overview

	8.2 Data Needs
    = covered in surveys

	8.3 Study Area and Extent of Assessment
    = not mentioning modal shift

	8.4 Level of Analysis
    - Planning and Preliminary
    - Operational
    - Microscopic Simulation

    8.5 Estimating Traffic Volumes
	steps:
    
    1 design alternatives
    2 remove routes shifted to BRT
    3 return BRT vehicles in mixed-traffic
    4 Modal shift and reduce vehicles (with stated preference surveys?)
    5 change of capacity, other routes diverted
    6 determine localized changes due to detours
    
    8.6 Methodologies and Performance Measures	
        - macro: pax flow, speeds, travel times, emissions to a future year
        - micro: bottlenecks capacities and demands, delays, stops per vehicle, saturation for turning movements

    LOS from HCM (cars, pedestrians and bikes)

	8.7 Mitigation

    Often positive results overall... Measures presented.


Chapter 24 - 24 Intersection and Signal Control

BRT Standard about treatment of intersections

    Overview:
    £1 - Objective of the chapter: teach design layout and operations of intersections
       - Importance of intersections to BRT design (BRT delay and most impact over mixed traffic)

    £2 - Important strategy: restrict mixed-traffic turns; BRT standard award points for this.

    £3 - Chapter discusses also:
            - treatment of public transport movements,
            - station placement relative to intersections
       - Finally traffic-signal controlled intersection, placement of signal equipment <--does it?,
         and techniques to provide public transport vehicles with priorities are discussed in more depth.

	24.1 Approaches to Intersection Design
        
    £1 Importance of intersections, problems a bad design can cause. Objectives of the design:
            1. Minimize delay for BRT
            2. Provide safety and convenience to pedestrians
            3. Minimize delay for mixed traffic

    £2  - Do not use a standard configuration. Impact over intersection is to be taken in account service plan, location and design of stations.
    £3  - Approach steps:
            - simplify route structure 
            - identify bottlenecks, solve with standard practice (this is where formulas are gone and less detail than 3rd edition is given)
            - restrict mixed traffic turns
            - locate stations 
            - signal phasing
            - signal priority

    £4  - Solutions must be supported by data


	24.2 Intersection Spacing and Rationalization
		24.2.1 Identify Existing Bottlenecks
        
        £1  - what are bottlenecks
            - problems they cause
      (A long part how to do this from the 3rd edition is gone, is this to go to chapter 8?)

        £2  - Once identified, data shall be collected
            - Chirag Dilli did not do that and face problems till today
            - Mixed traffic movements and congestion should be outside BRT infrastructure

      (I would have only one section as is... And I would bring back the text of 3rd edition... Or should that go to Chapter 8?

	24.3 Grade Separation
        24.3.1 Criteria for Grade Separation
        £1  - Flyover or underpass can be good.
            - Concern is access to users
            - Flyovers can cause adverse visual impact 
        £2  - Where needed, access and visual impact can be solved. Example from Boyacá Avenue Station, for the second phase of TransMilênio.

            (Image here is not good, and is not clear how this transfer will be improved... Legend has nothing to do with the matter...)

    (Criteria was not, in fact, given here...)

		24.3.2 Design Options

        £1. Four options presented (all possible)
    (would invert the order 1 and 2 to make more clear that covers all)

        £2. Option 1 and 2 do not need special comments
        £3. Option 3 can have problems (need an extra draw)
        £4. Option 4 can lead to stations too far apart and difficult to connect with other corridor

        £5. Underpasses are preferred, but may be too expensive

        £6. Busway flyover costs 10 X regular, underpass can be the same, unless they are too expensive (similar information as previous)

	24.4 Restricting General Traffic Turning Movements

        £1. - Optimise handling demand X optimise speed (should be maximise)
            - What is best for achieving demand
            - Stations and intersection are some of the main focal points (quite repetitive)
            (not exactly emphasizing intersections as possible operational disruption)
            - In signalized- intersections capacity is determined by:
                - movements allowed
                - vehicle volumes in the intersection
                - necessary green time to each movement throughput (<--in fact is only this)
            - Removing movements translates in more green time.
            - Optimizing intersections should be about reduce intersections and simplify movements that are impossible to eliminate (<-- impossible is too strong...)

		    (this as well as grade separation are needing introduction
		
        24.4.1 Evaluating Need for Turning Movement Restrictions
            
            -  standard technique for increasing BRT travel speeds and reducing signal delay is to restrict as many mixed-traffic turning movements across the corridor as possible (<--repetition of previous)
            - If the busway is reaching saturation, or the introduction of the BRT system increases mixed-traffic saturation to critical levels, it becomes imperative to consider some form of turning restrictions with the objective of achieving an ideal two-phase intersection. (<-- ideal was not explained)

            (This subsubsection does not address the evaluation of need for restriction, evaluation should be addressed or subsubsection eliminated... an introductory text about signal phases, should be considered)

        24.4.2 Alternatives for Restricting General Traffic Movements

        £1-6 6 options are presented (1 and 3 are the same and option 6 is a variant of 2), described and schematic drawn
        
        (need to clarify some draws and reorder)

        £7. 
        - There are other options combining the above.
        - Consider adjacent streets have capacity to absorb additional traffic.
        - residential areas will encounter resistance to such changes 

        (would notice that residential areas rarely have congested intersections)

        £8. 
        - Alternatives to restrict turns are:
            (1) separated turning lanes
            (2) pre-signal to BRT to queue jump
            (3) grade separation (<-- this is not)

        (Neither of this is about restrict turns, but about how to enable them with less disruption)

    24.5 Busway Turning Movements
 
        £1-3: BRT vehicles turning are needed and convenient.
            - should be planned
        £4  - There are several solutions to this.
            - Optimal solution is location specific
            - 5 main options:
              (1) Dedicated turning lanes and additional signal phases for BRT vehicles;
              (2) BRT vehicles operating in mixed traffic turning lanes;
              (3) BRT turning movements prior to the intersection;
              (4) Queue jump signalization for BRT vehicles (pre-signals);
              (5) BRT lanes at roundabouts 




		24.5.1 Dedicated Turning Lanes and Additional Signal Phases for BRT Vehicles

        £1 - Offers the advantage  of keeping BRT vehicles in controlled space.
            - May require extra phase 
            - if left turn phase do not exist
            - challenge is is find space for an extra lane



        24.5.2 BRT Vehicles Operating in Mixed-traffic Turning Lanes
        (This is missing)


		24.5.3 BRT Turning Movements Prior to the Intersection
        (This is missing)

		24.5.4 Queue-jump Signalization for BRT Vehicles (Pre-signals)

        24.5.5 BRT Lanes at Roundabouts
            1. Mixed-traffic operations
            2. Mixed traffic operation with signalized waiting area
            3. Exclusive lane along the inside of a roundabout
            4. Exclusive busway through the middle of a roundabout
            5. Grade separation

	24.6 Station Location Relative to Intersection
		24.6.1 Locating the Stations at the Intersection
		24.6.2 Locating the Stations away from the Intersection
		24.6.3 Locating the Station Mid-block between Intersections
		24.6.4 Calculations for Optimizing the Location of Stations
		24.6.5 Locating the Station under or over the Intersection (Grade Separation)
	24.7 Traffic Signal Control and Intersection Layout
		24.7.1 Traffic Signal Control
		24.7.2 Intersection Layout
		24.7.3 Intersection Capacity Analysis
		24.7.4 Location of Detection Loops
		24.7.5 Signal Priority
24.7.5.1 Passive Signal Priority
			24.7.5.2 Active Signal Priority
		24.7.6 Special Turn Movements Using Vehicle-activated Signals
		24.7.7 Pedestrian and Cyclist Crossing Considerations

             

