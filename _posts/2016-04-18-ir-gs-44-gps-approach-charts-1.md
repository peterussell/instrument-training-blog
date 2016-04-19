---
layout: post
title:  "IR GS44 - GPS Approach Charts (1)"
date:   2016-04-18 21:27:00
categories: instrument-training
---

# Phases of GPS

To date, there have been three distinct phases of GPS approach chart development. Phase 1 was the earliest,
or 'pioneer' phase, and no longer of significance so we won't cover it.

**Phase 2** is known as **GPS Overlay Approach**, many still exist. This hybrid is a *GPS approach built
over the underlying structure of a non-precision approach procedure.

 - the titles will be something like 'NDB or GPS-A', this would be *both* an NDB and GPS approach
 - the GPS portion follows the same routing as the underlying non-precision approach, but uses
   GPS for navigation instead
 - you must *choose one or the other*, you can't mix and match, if you choose GPS it's a GPS approach, if you
   choose NDB, it's an NDB approach
 - other common GPS overlay approaches may be combined with VOR or VOR/DME

**Phase 3** is known as the **Standalone Approach**. These are not based or overlaid on any non-precision
approach.

**RNAV vs. GPS**

 - GPS is simply area navigation (RNAV) that uses GPS to create waypoints rather than a unit which uses
   a combination of VOR and DME to create waypoints
 - therefore, all GPS is RNAV, but not all RNAV is GPS
 - there are still a few RNAV approaches around based solely on area navigation equipment
    - eg. there's an approach at Truckee-Tahoe which is a VOR/DME RNAV approach

There's also one other type of RNAV approach, often called **RNP SAAR**:

 - RNP = *Required Navigation Performance*
    - uses equipment is required to meet 'Required Navigational Performance' specs (RNP)
 - SAAA = *Special Aircraft and Aircrew Authorization (SAAA)*

These are often approaches with unusual curved feeder routes. Just keep in mind that if an RNAV approach
*doesn't* have GPS in parenthesis, then it isn't one you're likely to fly based on the IFR-certified GPS
equipment in your airplane.

# GPS Approach Construction
**Primary and Secondary Obstacle Protection**

Accuracy when flying a GPS approach is even more important than with a non-GPS approach due to a number
of reasons which we'll examine here.

All sections of the route structure for a GPS approach (including the feeder/enroute portion) have a
*primary* and *secondary* area of obstacle protection.

 - **Enroute and Feeder Routes** leading to the IAF provide **1,000' obstacle clearance** (2,000' in
   certain designated mountainous areas) for 4 miles on either side of those routes.
    - the **secondary area** offers 500' obstacle clearance
    - this begins at the border of the primary area, and *tapers* to 0' obstacle protection at 2 miles
    - *for clarification, at 5.5 miles from the airway centerline, obstacle clearance could be as low as
      125'*
 - a memory aid for remembering the protection widths around an airway is:
   - **2-4-4-2** - remember that the *secondary area tapers* from 500' to 0' across its width
 - on non-GPS feeder routes, the 2-4-4-2 rule applies **all the way to the IF**
 - on **GPS feeder routes**, this ramps down to **1-2-2-1** at a point where a 30 NM arc from
   the airport intersects that segment
    - the important implication of this is that the slope in the secondary area is much steeper
      at this point (ie. where the widths are 1-2-2-1)
    - *eg. at just 2.75 miles from the airway centerline, you have only 125' of clearance*
 - next we'll examine how the sensitivity of the GPS unit is affected by these different levels of
   protection during the approach

# Changing CDI Course Sensitivity

 - there are two types of IFR certified GPS panel units:
    1. WAAS-Capable (more on this later), certified under TSO-C146a
    2. non-WAAS unit, certified under TSO-C129a
 - from an enroute perspective, the difference is that the HSI's CDI scale dot/mile deflection is *more
   sensitive in a WAAS unit*
 - we'll look at non-WAAS units first, then WAAS units

**Non-WAAS GPS**

**Enroute Mode:**

 - when flying in the enroute structure and *more than 30 miles from the destination airport*, your
   non-WAAS unit GPS's course needle has a  **dot-scale sensitivity of five nautical miles**
    - this is called the GPS's **enroute mode**
    - because there are typically five dots, this means that for *every dot the CDI needle is from the
      center position, you're off course by 1 NM
    - for convenience, we'll refer to this as a CDI scaling of +/- 5NM
    - *note: when the CDI is used for VOR navigation, each dot reprsents 2 degrees of course deviation*

**Terminal Mode:**

 - the moment you're within 30 miles of the airport, and have either manually armed or configured the GPS
   to fly an approach, you'll enter what's known as the **Terminal Mode** of the approach
 - at this point the margin for error decreases drastically
 - the **CDI scaling automatically changes to +/- 1NM**, each dot is a 0.2NM deviation (5 dots = 1 mile)

**Approach Mode:**

 - occurs at **2 miles from the FAF**
 - CDI scaling is **+/- 0.3NM**, each dot is approximately 365 feet of course deviation

Because of this increasing CDI sensitivity, the boundaries of protected airspace can be built to much
tighter geometric tolerances. This is good because it allows you to fly approaches with the lowest
possible minimums.

Perhaps the biggest difference between RNAV (GPS) and non-RNAV approaches (VOR, NDB, etc) is in the
final approach course area. At the **Missed Approach Waypoint (MAWP)** the primary area on either side
of the centerline is **0.5NM wide**. That's about 40% less than the primary protected area for many
non-precision, non-RNAV approaches.


**WAAS GPS**

 - **Enroute Mode:** +/- 2NM - each dot represents 0.4NM deviation
 - **Termianl Mode:** same as a non-WAAS unit (+/- 1NM), each dot represents 0.2NM deviation
 - **Approach Mode:** similar as for an ILS approach (very low margins) - more on this later

Because of the reduced protected area and requirement for greater navigational precision, not all
RNAV equipment will meet the Required Navigational Performance (RNP) needed for the approach.
We'll look at how to find out whether your equipment is able to be used for the approach next.
