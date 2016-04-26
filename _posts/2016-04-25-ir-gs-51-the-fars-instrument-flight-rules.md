---
layout: post
title:  "IR GS 51 - The FARs: IFR"
date:   2016-04-25 22:12:00
categories: instrument-training
---

# Instrument Flight Rules

# FAR 91.167 - Fuel Requirements for Flight in IFR Conditions

 - [FAR 91.167][far-91-167]
 - to be legal flying IFR, you need enough fuel to fly **to your destination, from that airport to your
   alternate (if one is required), and then fly for 45 minutes at normal cruising speed**

**When are you required to have an alternate?**

 - the '1-2-3' rule. If...
    - within **1 hour before or after** your ETA at your destination airport, the weather is forecast to be...
    - a **ceiling less than 2,000'** above the airport elevation, *or*...
    - a **visibility of less than 3 statute miles**...
    - then you need to list an alternate airport on your IFR flight plan
 - if none of these conditions exist (ie. weather is better than required for filing an alternate), then you
   also don't need to carry the extra fuel required to fly to the alternate
 - any forecast of conditions 'occasionally', 'intermittently', 'chance of', or 'briefly' below 1-2-3 are
   considered legally binding reasons to file an alternate

# FAR 91.169 - IFR Flight Plan

 - [FAR 91.169][far-91-169]
 - all instrument flight plans require the same information as VFR flight plans require, that is:
    - aircraft identification, and approved radio calls sign (eg. 'Cactus One') if you're using one
    - the type of aircraft, eg. C172, as shown on the FAA Order 7110.65
    - full name and address of the PIC
    - departure airport and proposed time, as UTC
    - destination and ETE
    - fuel on board in hours and minutes
    - alternate airport if required
    - number of people on board
    - colour of the aircraft
    - any other information the PIC or ATC believe is necessary for ATC purposes

**Alternate Airport Requirements**

 - if the airport has a **non-precision approach**: 800-2 (ceiling of 800', 2 miles vis)
 - if the airport has a **precision approach**: 600-2 (ceiling 600', 2 miles vis)
 - this must be forecast at **the time you expect to arrive *at the alternate***
 - you may choose an airport *without any IAPs* if you're able to fly to and land at that airport
   in VFR conditions based on the forecast at the time of arrival
    - this includes checking the TAF, as well as the *area forecast*

**GPS Approaches at Alternates**

 - it's legal to file an IFR flight plan based on a GPS IAP at *either* the destination or
   alternate, but not both
 - if you're filing an alternate for an airport that only has a GPS approach (or that being the only
   IAP that you can fly, due to equipment requirements or similar), then the following requirements
   must be met:
    1. the GPS unit must have fault detection and exclusion (FDE) capability
    2. the pilot must perform a preflight RAIM prediction for the airport where the RNAV (GPS approach
       will be flown
    3. the pilot must have proper knowledge and any required training and/or approval to fly a GPS
       based IAP
 - if you're flying a non-WAAS based approach, **or have WAAS enabled GPS but don't have baro-VNAV**
   (which is most small single engine piston airplanes), then you **must use the 800-2 weather
   minimums**
    - *even if there's an LPV approach and you have WAAS-enabled GPS, you must **still use the
      non-precision minimums***

# Non-Standard Alternate Minimums

 - we've seen that the minimums for listing an alternate are 800-2 for non-precision and 600-2 for
   precision IAPs at the ETA at the alternate
 - for some airports the requirements are even more stringent, such as if the area is particularly
   hazardous, or the standard minimums make a landing dangerous for some other reason
 - in this case, they will list **non-standard alternate minimums**
    - *eg. Palm Springs, CA*
 - non-standard alternate minimums are **identified by a white 'A' in a black triangle in the
   briefing section of an approach chart**
 - the non-standard minimums are listed **in the front of the approach chart booklet**

# Real Alternates vs. Paper Alternates

 - if you aren't able to land at your destination, it doesn't mean you *have* to go to the alternate
   airport listed on your flight plan - this is the 'paper' alternate
    - this is the airport you *must* have fuel to fly to, and continue to fly for 45 minutes at normal
      cruise power after reaching
    - this is also where the FAA expects you to turn up if you're unable to land at your destination
      and also have a communications failure (ie. having a 'really bad day')
 - the *real* alternate could be somewhere you decide to divert to if you notice the weather is
   deteriorating while you're enroute, it may or may not be your filed alternate
 - note: legally, the 800-2/600-2 rules only apply to the alternate you're *filing*
    - *eg. if you're enroute in worsening weather, and decide to divert to to a big airport with multiple
    ILS approaches, but the forecast is 400-1. You're still allowed to divert there, assuming you can
    complete the approach legally*

**Tips for Picking an Alternate**

 - **"Downhill, downwind, and VFR**
    - downhill - pertains mainly to mountainous terrain, means you want to find an alternate at lower altitude
    - downwind - makes it quicker to get to your alternate, and you're not fighting wind/losing fuel
    - VFR - if possible, you should fly toward improving weather instead of deteriorating weather

# FAR 91.171 - VOR Equipment Checks for IFR Operations

 - [FAR 91.171][far-91-171]
 - if you plan to use your VOR equipment on an IFR flight plan, it either has to be maintained, checked,
   and inspected under an approved procedure, or it has to have been **operationally checked within the
   preceding 30 days**

There are several ways accomplish the VOR check, we'll examine in the order of desirability.

 1. the most accurate method is to use a **test signal** generated by a 'certificated and appropriately
    rated radio repair station', or an FAA-operated VOT test signal
     - if you use a repair station, they must make the entry in the aircraft log or *other record*
       certifying the bearing transmitted by the repair station, and the date of transmission
     - if there is an **FAA-operated VOT test signal**, you'll find that information **in the Chart
       Supplement** (CS - formerly A/FD)
     - tune in the frequency
     - center the CDI
     - it should read 0 degrees and 'FROM', or 180 degrees and 'TO' (think Cessna '182')
     - some VOTs can also be used airborne, also listed in the CS
     - **in all cases (radio repair station, VOT ground, VOT air) the tolerance is +/- 4 degrees**
 2. **VOR check form a known position**. Some airports have a designated spot on the airport for
    VOR check purposes. These checkpoints are also in the CS, which contains the frequency of a
    nearby VOR to be used, the bearing to be checked, and the location on the airport
     - **the permissible error for this check is also +/- 4 degrees**
 3. you can also use **airborne checkpoints** designated by the FAA and listed in the CS
     - these should be done during a VFR flight
     - **permissible error is +/- 6 degrees**
 4. you can **make your own airborne checkpoint** in flight
     - select a VOR radial that is the centerline of an established runway
     - find a prominent landmark on your chart that lies under the selected radial, and **is at least 20
       miles from the VOR**
     - maneuver directly over this landmark at a reasonably low (but legal) altitude
     - note the VOR bearing shwo n on your receiver
     - **permissible error is +/- 6 degrees
 5. if you have two VOR receivers, you can perform a **VOR receiver cross-check**
     - only allowed if the systems are *totally separate, apart from the antenna*
     - tune both VOR receivers to the same ground station
     - note the indicated bearings to that station on each receiver
     - **permissible error is *4 degrees*** (note: not +/- 4 degrees, that doesn't make sense in this case)

No matter what method's used and who does the checks, the following needs to be logged:

 - **"SPED"**
 - **Signature** of the person making the check
 - **Place** of the check
 - **Error** observed
 - **Date** the check was done

# FAR 91.173 - ATC Clearance and Flight Plan Required

 - [FAR 91.173][far-91-173]

If you are going to operate in less than basic VFR conditions (ie. IMC, or fly IFR) in *controlled*
airspace, you must

 - file an IFR flight plan
 - have received an appropriate clearance from ATC

*Note: it is legal to fly in uncontrolled (Class G) airspace without an IFR flight plan or ATC clearance,
but that may not be such a good idea...*
[far-91-167]: http://rgl.faa.gov/Regulatory_and_Guidance_Library/rgFar.nsf/FARSBySectLookup/91.167
[far-91-169]: http://rgl.faa.gov/Regulatory_and_Guidance_Library/rgFar.nsf/FARSBySectLookup/91.169
[far-91-171]: http://rgl.faa.gov/Regulatory_and_Guidance_Library/rgFar.nsf/FARSBySectLookup/91.171
[far-91-173]: http://rgl.faa.gov/Regulatory_and_Guidance_Library/rgFar.nsf/FARSBySectLookup/91.173
