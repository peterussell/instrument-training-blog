---
layout: post
title:  "IR GS 55 - Enroute Charts (2)"
date:   2016-05-06 20:32:00
categories: instrument-training
---

# Compulsory Reporting Points

 - compulsory reporting points are used by controllers to update paper strips with airplane positions
 - the strips are used in the case of a radar, computer, etc. failure, where the IFR system continues
   to work based on movement of these strips
 - compulsory reporting points are denoted on enroute charts (and approach/departure charts?) by filled
   black shapes
    - the book only mentions filled black triangles in VORs, but there may be others, I'm not sure...
 - open, or non-filled triangles (or shapes) represent non-compulsory reporting points

**Making a Position Report**

 - position reports include information represented by the acronyms **PTA-TEN**:
    - **P**osition
    - **T**ime
    - **A**ltitude
    - **T**ype of flight plan
    - **E**stimate to the *next compulsory reporting point*
    - **N**ext compulsory reporting point

**Important:** compulsory reporting points are **used when radar contact is lost**. If you hear
a controller say "Radar contact lost", the unspoken part is to **resume position reporting**.

The corollary to this is that if you are in radar contact, then you don't need to provide position
reports (except for holds?).

**Other types of Compulsory Reporting Points**

 - any time you define a direct route of flight in your flight plan between fixes that **isn't flown
   on radials or courses of established airways or routes**, those fixes become compulsory reporting
   points (again, when *not in radar contact*)

# Chart Oddities

This section covers things on enroute charts that you don't see very often, but are still important.

 - some fixes may include a **holding pattern symbol** next to them, this is the 'as published hold'
    - these are often established as places where controllers might often ned to hold airplanes
 - some fixes use an **NDB radial** to identify a cross radial (probably with the intersection of a VOR radial)
 - **IFR Flight through Restricted Areas**
    - IFR routes that penetrate a Restricted Area are surrouneded by **small black dots** on either side
    - if your IFR clearance takes you through this area, then ATC has obtained permission for your passage
    - however, it might be wise to avoid planning your IFR flight throuhg this area if the restrictions will
      be in effect at the time of your passage
 - **ATIS at an Airport**
    - denoted by '(A)' printed under the airport information, along with a frequency
 - **Pilot Controlled Lighting**
    - denoted by an 'L' inside a circle in the airport information block
 - **Localizer Flag on the *Enroute Chart***
    - this is the triangle with one shaded half and one white half, leading to the localizer facility
    - denotes that the localizer serves an *enroute function*, such as identifying an intersection

There are other less-frequently found chart symbols which we won't cover here (they can be found in
Rod's 'Instrument Pilot's Survival Manual')

# Controlled and Uncontrolled Airspace

 - **Uncontrolled Airspace** (Class G)
    - **Brown Areas** indicate uncontrolled airspace up to but not included 14,500' MSL
    - in other areas, Class G may extend up to 700' AGL, 1,200' AGL, or not at all
    - you need to refer to a *sectional chart to determine the altitude at which controlled airspace begins*
 - **Controlled Airspace** (Class A, B, C, D, E)
    - beginning at 14,000' MSL in brown shaded areas
    - begins at either SFC, 700' AGL or 1,200' AGL (consult a sectional chart)
 - **Airways through Class G up to 14,500' MSL**
    - the controlled airspace around an airway **typically extends to 4NM either side of the airway**
    - because this is controlled airspace, it's shown as a white area through an otherwise brown section

# MEAs, MOCAs, MCAs, and OROCAs

**Minimum Enroute Altitude (MEA)**

 - the MEA is the minimum altitude at which you may fly on any existing airway segment
 - it gets you two important things:
    1. obstruction clearance
    2. reception of **navigation** stations
 - the MEA is printed *above the airway it applies to*
 - the MEA guarantees you 1,000' of obstruction clearance in non-mountainous terrain, and 2,000' in mountains
    - 'mountainous terrain' is officially known as *designated mountainous areas*

Sometimes the MEA has to be increased considerably to ensure solid reception of nav stations, or because of
precipitous terrain along a portion of the airway (which can generate unusual pressure changes which could
dangerously affect the altimeter).

When the MEA is increased becase of precipitous terrain (or other reasons aside from obstacle clearance), it's
sometimes possible to offer an altitude lower than the altitude that can be flown when close to the VOR.

**Minimum Obstacle Clearance Altitude (MOCA)**

 - a MOCA is shown by an asterisk on the chart next to its respective altitude, eg. "\*5700"
    - you'll usually find the MOCA under the MEA
 - **the MOCA provides obstruction clearance and adequate reception *within 22 NM (or 25 SM) of the VOR***
 - beyond 22NM, the MOCA guarantees only obstacle clearance
 - a MOCA can also be useful if you're navigating using GPS, for example if you had to descend to the MOCA
   due to ice buildup, you know that the MOCA will keep you free from obstructions

**MEA or MOCA Changes at Fixes**

 - when an airway goes through a fix *without* an MEA or MOCA change, the line continues through
   the fix (ie. triangle), with space between the line and fix
 - when an airway **has an MEA or MOCA change at a fix**, the lines leading up to the fix will
   **have a cap on the end of them** (eg. ---|, or |---)
 - the cap indicates that the MEA or MOCA will change when crossing this fix
 - this is **important for lost comms* - if you see a cap on the end of a line, you know to expect
   an altitude change (remember, the highest of MEA, Expected, or Assigned)

**Minimum Crossing Altitude (MCA)**

 - denoted by a **flag attached to a fix with a cross ('X') inside it**
 - means you should look around for the name of the intersection with the MCA under it
 - will often have a condition on the MCA related to the direction you're flying
    - *example: "PANOS V230 8000 E"
    - this means if you're traveling *east* on *V230*, the MCA at *PANOS* is *8000'*
 - some VORs will have multiple MCAs depending on direction and route of flight
    - in this case the flag will be indicated the same way (flag with a cross on the VOR), and the list
      of MCAs and conditions will be listed nearby

**MEA or MOCA changes *without* an MCA**

 - if there's an MEA or MOCA change but no MCA is specified (the fix has no flag with a cross), then
   you begin your climb to the MEA (or MOCA) *when you cross the fix*
 - if there **is an MCA**, then you need to have climbed to that altitude **before you cross the fix**

**Off-Route Obstruction Clearance Altitude (OROCA)**

There are times during IFR flight, such as during an emergency, when it's necessary to leave an established
airway or route. The OROCA exists to give you terrain and obstruction clearance information in this situation.

 - the OROCA is written in large faded letters over the chart (kind of like the Maximum Elevation Figure
   on a sectional, or MEF)
 - it's bounded by a quadrangle, made of **whole number latitude and longitude lines**, the OROCA applies
   to the whole quadrangle
 - the obstruction clearance is the same as for MEAs (and MOCAs?) - 1,000' in non-mountainous, 2,000'...
 - it **only provides obstruction clearance**, ie. it *doesn't necessarily provide...*
    - ground-based navaid reception
    - comms reception
    - radar service

*Note: the Minimum Reception Altitude (MRA) and Maximum Airway Altitude (MAA) are covered below. First we
need to cover some concepts related to intersections.*

# Minimum Climb Rates

The *minimum* rates of climb expected depend on the altitude that the MEA or MCA is at, and are expressed
in feet per NM.

 - **5,000' or less:** 150' per NM
 - **5,001' to 10,000':** 120' per NM
 - **Above 10,000':** 100' per NM

# Intersection Identification

 - each intersection comes with little arrows pointing toward it
 - these arrows bordering the intersection come from the facility whose VOR radials (airways) designate
   that intersection - no arrow, don't use that radial
 - **the important point to note is that the *absence* of an arrow means you should not use that
   radial to identify the intersection**
    - for example, REDDE intersection lies on radials from the ROM, PRB, and AVE VORs
    - however, *only* the radials from ROM and PRB have arrows next to them (or in same cases on them, if
      the radial isn't also an airway), so only they can be used to identify the intersection
    - in this case, the Avenal (AVE) radial *should not* be used to identify the intersection, this could
      be due to terrain or some other interference

**Using DME to Identify an Intersection** (Route Segment Distance)

 - a **hollow tipped arrow** means that **DME can be used for intersection identification**
 - this value is shown under the airway or radial, and is known as the **Route Segment Distance**
 - conversely, a **solid tipped arrow** indicates that you *can't* use DME to identify the intersection
 - sometimes DME values are tallied for ease of identification and displayed in a **DME Thumbnail**
    - in this case, the DME thumbnail contains the number (it looks like a little 'D' with the number
      inside)

# Altitudes (continued)

**Minimum Reception Altitudes (MRA)**

 - whilst an MEA will guarantee you navaid recpetion *on the airway*, some intersections may require
   off-course VORs to identify them
 - in some cases, the **MEA may not guarantee reception of all navaids required to identify a fix**
 - in this case, there will be a **Minimum Reception Altitude (MRA)**
    - this is the **altitude you need to be at to get a reliable signal from all navaids required
      to identify the intersection**
 - this also appears to be denoted by a flag with an 'R' inside it (the book doesn't mention it, but
   it seems likely that the symbol's related to the intersection having an MRA)

**Maximum Authorized Altitude**

 - where this exists, it's denoted on the airway, above the MEA, with the letters 'MAA' before the
   altitude
    - *example: "MAA-10000"
 - this is the highest altitude at which you're allowed to use this airway
 - this can happen due to potential conflict with overlying routes, but it's more often to
   **prevent you from receiving the wrong VOR signal**
    - the FAA tries to separate similar VOR frequences, but the higher you are the further you can 'see'

# Airway Mileage and Changeover Points (COP)

**Total Mileage Boxes**

 - on low altitude enroute charts, the **total mileage between navaids is shown within a box, often
   located at the midpoint of the airway**
 - where airways have shared designators (eg. "V-165 - 197"), an effor is made to place the total
   mileage box under the corresponding airway number (eg. under the text "V-165", instead of "V-197")
 - the total mileage box may also have light gray text next to it, indicating the navaid that it
   corresponds to, as a helper

**Changeover Points (COP)**

 - airway changeover points are indicated by what appears to be a half swastika
 - this is the point where you switch between navaids on the airway you're flying
 - COPs exist primarily to assure adequate signal reception, but they can also be located in order to
   avoid signal interference from another navaid

**Small 'X' on the airway instead of an intersection**

 - this denotes there's a change in the airway direction - these can also happen at COPs, intersections etc.
 - when a change occurs that's **more than 3 degrees* but there's no intersection etc., then the 'X'
   symbol is used to indicate this change
 - this mileage break fix **may include an identifier in brackets**, eg. "(WIJYI)"
    - this is known as a **Computer Navigation Fix, or CNF**
    - these letters have value only if the database in your FMS or navigation system uses them to help
      identify the mileage break
    - these letters **have no other function, and should not be used in a flight plan or when talking to ATC**

# GPS-only Q and T Routes

Given the popularity of IFR approved GPS unites in smaller airplanes, the FAA has started publishing
GPS-only low altitude routes, called **T-Routes**.

 - T-Routes are shown in **blue**
 - the main purpose is to provide airplanes with a route around or through congested terminal airspace
   in the low-altitude enroute system (eg. Class C and B airspace)
 - these routes provide **more flexibility than VOR routes**
 - when you file as a /G aircraft, you should be prepared to use these T-Routes (as well as RNAV based
   SIDs, DPs, and STARs)
 - there are still MEAs and MOCAs associated with T Routes
    - the letter G next to the MEA indicates that this MEA and MCA are specifically for airplanes using
      RNAV that's **based on GPS**

**Q-Routes** are for use in the high altitude airspace system. These routes are commonly used to alleviate
traffic congestion for aircraft flying at or above 18,000' MSL.
