---
layout: post
title:  "IR GS39 - Approach Chart Analysis (1)"
date:   2016-04-04 21:11:00
categories: instrument-training
---

Approach Chart Booklets

 - Instrument Approach charts created by the government are contained in the **U.S. Terminal Procedures Publications (TPP)**
   - TPPs contain 24 bound volumes of instrument charts, produced by NACO (National Aeronatucail Charting Office)
   - also available on CD or for download
 - Jeppesen also produces Instrument Approach charts, but we'll concentrate on NACO charts here
 - we'll cover ILS, Localizer, VOR, and NDB charts, then GPS/RNAV charts later

# ILS (Instrument Landing System) Approach

Further to the information in previous posts, it's worth noting a few other things about IA charts:

 - the airport and city names can be different; the *City Name* is printed at the top left of the chart, the *Airport Name* is printed near the top right, directly under the approach name
 - at the left of the middle briefing area, there may be a **T and/or A in black triangles**. These symbols indicate the presence of non-standard takeoff and alternate minimums, which we'll discuss later in the *Departure* and *Enroute* sections
 - in the **plan view**, an ILS has a feathered shape symbol, representing the **localizer portion of the ILS**
 - the **outer and middle marker** may be shown on the chart, depicted as squashed ovals with pointed ends, and (possibly?) the letters 'OM' and 'MM' respectively
   - remember that marker beacons can be collocated with another navaid, such as an NDB, in which case it may be referred to as a *compass locator*  An NDB and Outer Marker is a *Locator Outer Marker (LOM)*, with the Middle Marker it's a *Locator Middle Marker (LMM)

**Dead Reckoning Routes**

 - some routes are shown without navaids leading you along the course
 - in this case, the directions will be printed on the chart
   - *example: '244 degrees (2.6) and 301 degrees (7.1)'*
 - to fly this route you use the compass headings and distances printed
 - you are *not expected to correct for wind drift* when flying it
 - *dead reckoning segments* are usually short and built with enough tolerance so that even in strong winds you won't drift into obstacles or terrain

# Altitudes & Clearances for Non-Published Routes

ATC will often give vectors *to* a published route on an instrument approach, which raises the question of how low you're allowed to descend if you're not following a route shown on the chart. The answer is:

 - in [FAR 91.175(i)][far-91-175-i]
 - **maintain the last altitude you were given, until established on a segment of a published route or instrument approach procedure** (provided ATC hasn't assigned a different altitude
 - that is, don't change altitude from the last ATC instruction during the vector until your airplane is on a published flyable route, with a minimum altitude, direction, and distance
 - upon reaching the final approach course or fix, you may either complete the approach in accordance with the published instrument procedure, or continue a surveillance or precision radar approach to a landing, if you've made arrangements for such an approach

**Flying to an Approach Path *without* an Approach Clearance**

 - if you cross an approach path as a result of ATC vectors, and an approach clearance *hasn't* been issued, then you should **maintain your last heading and query ATC**

# ILS: Intercepting the Glideslope

 - on an ILS, the official glideslope interception point is depicted as a **zig-zag arrow**
 - in the profile view, an altitude will be written *above* the glideslope intercept point which gives the altitude you'll intercept the glideslope at
   - this is a good time and method to check your altimeter and/or glideslope indicator, they should correspond to the numbers printed here
   - remember that **false glideslope signals may exist above the glideslope**, so if you're attempting to intercept the glideslope from high above it you may end up tracking an erroneous signal
   - erroneous glideslope signals require excessive descent rates to maintain, so if you're descending very quickly this should alert you that you may be on a false glideslope
   - this is why it's good to cross-check the glideslope intercept altitude against the glideslope indication and the chart
   - *intercept from below and false glideslope signals won't be a concern*

**Decision Altitude**

 - all the approaches discussed so far have MDAs, but the ILS has a **Decision Altitude, or DA** (sometimes still referred to as DH or Decision Height)
 - the DA is **the lowest altitude to which you're allowed to descend before making a decision to continue the approach or make a missed approach
 - the Missed Approach Point (MAP) on an ILS is always the DA shown in the minimums section
   - *ILS: DA = MAP*

# ILS: Visibility Minimums / Runway Visual Range (RVR)

 - the visibility minimums for an ILS approach are in *hundreds of feet* (not parts of a mile like other approaches)
   - *example: S-ILS 30: 249/24 - this means a DA of 249', and an RVR of 2,400' are required to land*
 - the **RVR** is an electronically derived estimate of the visibility in hundreds of feet that a pilot should have horizontally down the runway from the approach end - supposedly - in a moving airplane
   - they are measured by instruments called *transmissometers*, and reported to ATC

**Issues with the RVR**

 - recall that the RVR is electronically derived from a few feet off the ground, most often at the beginning of the approach end of the runway
 - this isn't a good indication of the flight visibility at DA, where you have to make the call whether to land or execute a missed approach. It's often displaced by hundreds of feet vertically, and thousands of feet horizontally
 - for this reason, the **FAA is very specific in saying that you must have the required *flight* visibility shown on the approach chart to descend below DA**
 - so where's the required flight visibility?
   - the answer is that you use the RVR, and convert it to a useful value using a conversion table

**Flight Visibility**

 - because the FAA has said we need a required *flight* visibility, but the approach chart only gives us RVR (which is *not* flight visibility), we need to convert RVR to flight visibility
 - these can be calculcated using these values:
   - **RVR (feet) / Visibility (*statute* miles)** (SM because they're easier to estimate than NM)
   - 1,600 / 1/4
   - 2,400 / 1/2
   - 3,200 / 5/8
   - 4,000 / 3/4
   - 4,500 / 7/8
   - 5,000 / 1
   - 6,000 / 1 1/4
 - flight visibility is **forward visibility in the direction of the runway**, and **must be maintained all the way to touchdown**
   - if it can't be maintained, a missed approach must (legally) be executed

Note: if the RVR equipment at the airport is inop, the tower would estimate the visibility

**Using Flight Visibility**

 - as a Part 91 operator (airlines are Part 121, air taxi pilots are Part 135) - you actually get to estimate your flight visibility at DA (which is why it's so useful to convert it to miles)
   - note that Part 121/135 can't begin a descent if RVR is *reported* to be less than the minimums
 - flight visibility calculated from RVR is *usually* a good indicator of the flight visibility at DA, but not always
 - if you are at DA with the required flight visibility while the RVR indicates a smaller value, it's legal to land as long as you maintain that flight visibility until touchdown

**Approach Lighting and Visibility Requirements**

 - all ILS approaches have a large Approach Lighting System (ALS) associated with them
 - according to FAR 91.175(C)(3)(i), you *can* use the approach lights for a descent if you can't see anything on the landing side of the runway
   - you can descend to 100' above the TDZE
   - if you don't have any of the other 9 required items (more on that later), then you can't descend below 100', unless the terminating red bars or red side row bars are visible
 - as discussed earlier, ALSF 1 & 2 approach lighting systems have these red bars
   - since these red bars are close to the runway threshold, or are strategically placed (in ALSF-2), it's legal to continue your descent to land knowing that the runway's directly ahead of the red bars
   - *red is important because red doesn't affect your night vision*
 - then again, it's assumed that you'll always have the required visibiity for landing, so there should be no excessive risk when descending below 100' above the TDZE while using these red bars
 - the practical uses for these red bars are situations where you may have the required forward visibility, but it's difficult to make out the actual runway, such as in heavy rain or snow
 - this is a big deal if the lights are inop - we'll cover *Inoperative Componenets* and what to do in these scenarios soon

**Approach Lighting System Symbols**

 - on the approach chart, a *dot above the ALS symbol* (not the actual diagram of the lighting, the symbol will usually be a small ball with letters in it, eg. 'A5') indicates that **sequenced flashing lights** are part of the ALS
 - a reverse (white on black) bold of any symbold indicates **pilot-controlled lighting** (7 times in 5 seconds to activate)
 - some pilots find the sequenced flashing lights distracting, it's absolutely fine to ask ATC to turn them off
   - apparently the correct phraseology for this is 'kill the rabbit'

[far-91-175-i]: http://rgl.faa.gov/Regulatory_and_Guidance_Library%5CrgFAR.nsf/0/66AFE97435E47B3A86256E1A00518D27?OpenDocument
