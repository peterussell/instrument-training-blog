---
layout: post
title:  "IR GS23 - The IFR System"
date:   2016-03-17 21:55:00
categories: instrument-training
---

# ARTCC (Air Route Traffic Control Center)

 - ARTCCs are the centers that handle air route traffic, including IFR traffic
 - there are currently 21 Centers in the United States
 - they handle airspace from the **base of controlled airspace** up to **60,000'** (flight level 600)
 - Centers use **radar** to control traffic
   - there are still some areas in the country where radar cover isn't available, usually at lower altitudes
 - each center is broken into **sectors**
   - controllers are responsible for traffic in one or more sectors
   - each sector is named. These are depicted on IFR Enroute charts in blue, with sectors separated by a square blue jagged line
   - each sector on the IFR enroute chart also has a **Center Frequency Box** containing the name and frequency for the sector
   - pilots refer to sector controllers by their Center's name, such as LA Center, or Albuquerque Center (they used to refer to the sector names, fun fact!)

**ATRCC Separation**

 - it's the controller's job to keep IFR airplanes separated by **five miles**, unless a smaller separation is permitted
   - for example: if an airplane is within 40miles of the controller's radar antenna, a controller can reduce separation to **three miles**; closer to the antenna means better target detection and target resolution

**Radar Beacon System/Transponder Interrogation**

The radar returns for an airplane are broken into two types:

 - **Primary:** this is the radar return from the **airplane itself**, and shows as a small white fuzzy dot. The resolution is worse than the return from a transponder and *gets worse with distance from the antenna*
 - **Secondary:** this is the radar return from the **transponder**. Requires the transponder and ATC computer equipment to be functioning properly. Gives a more accurate reading but is less reliable (might need to check that).

# Redudancy

Every step of an IFR flight is protected by multiple layers of redundancy, both in the airplane and at the ATC facilities controlling the flight. Here we examine some of those redundancies.

 - it starts with the flight plan and clearance. To fly IFR in the IFR system you need:
   - an instrument rating
   - an IFR-legal airplane
   - be IFR current
   - file an IFR flight plan
   - receive an IFR clearance

**IFR Clearance**

 - an IFR clearance is issued on the underlying assumption that either the airplane radio could stop working, or the controller's equipment could stop working
 - an IFR clearance gives you route, altitude, and other restrictions that you can follow in the event that you can't communicate with ATC
 - you will always receive an IFR clearance for an IFR flight
 - it's possible you won't actually fly the filed flight plan (eg. if the controller gives you radar vectors for part of the flight), but the IFR clearance gives you a set of instructions to fall back on if you're unable to communicate

**Controlled and Uncontrolled Airspace**

 - cloud clearances are designed to help keep VFR traffic out of clouds, but also far enough away that they can avoid IFR traffic entering/exiting clouds near them
 - these are defined by the [Basic VFR Weather Minimums][basic-vfr] (FAR 91.155)
 - the decision of which airspace to make controlled and which to leave uncontrolled:
   - based on the airspace that would be reasonably used by IFR pilots
   - below 1,200' AGL makes no sense controlling, because when VORs are (or, were) the main source of navigation, it was difficult to receive below 1,000' AGL for more than 25 miles
 - even today, there are no enroute airways having less than a 1,000' ground clearance
   - in a mountainous area, the minimum enroute altitude is 2,000' AGL
 - this is why controlled airspace, known as Class E airspace, starts at 1,200' AGL throughout the majority of the country

**Class E Airspace: 1,200' AGL to but not including 18,000' MSL**

 - below 1,200' AGL you mostly find uncontrolled Class G airspace
   - day: 1 mile visibility, clear of clouds
   - night: 3 miles visibility, 1,000' above, 500' below, 2,000' laterally

**Victor Airways:** controlled airspace always encompasses an area 4NM either side of an airway, starting at 1,200' AGL. This defines the airspace of a *Victor Airway*.

 - within this area, the controlled airspace begins at 1,200' AG, as indicated by faded blue lines
 - the area *outside* faded blue lines is uncontrolled airspace from the surface, up to but not including 14,500' MSL

**Controlled Airspace Near Airports**

 - controlled airspace is often found in areas around airports generally starting at 700' or 1,200' AGL where instrument approaches are conducted, even if there is no airway nearby
 - a **magenta faded border** indicates controlled airspace starting at 700' AGL
 - it allows airplanes on instrument approaches to remain within controlled airspace during their descent to the airport

 - when an instrument approach allows a significantly low descent, the controlled airspace may be lowered all the way to the ground
 - a **dashed magenta border** indicates controlled airspace to the ground

**ATC in Uncontrolled Airspace**

 - for example, what about Class G up to but not including 14,500' MSL with an airport in it (ie. *outside* the faded blue border)
 - in this case, ATC typically doesn't work with IFR pilots in these areas because they're located in *uncontrolled* airspace

 - it *is legal* to fly IFR in Class G airspace below 14,500' MSL without filing an instrument flight plan or talking to ATC, but it would be a really dumb idea

**The idea is that an IFR clearance applies only when in *controlled* airspace.**

**On a related note, separation in uncontrolled airspace is entirely up to you - ATC only provides these services when in *controlled* airspace.**

You may receive a clearance that gets you to fly through uncontrolled airspace. For example, if taking off at an airport where Class E begins at 700' or 1,200' AGL, you'll be climbing through uncontrolled airspace  In this case the clearance will include something like *'when entering controlled airspace, fly heading...'*. What you do while in uncontrolled airspace is totally up to you. There is one exception which will be discussed later in departures.

 [basic-vfr]: http://rgl.faa.gov/Regulatory_and_Guidance_Library/rgFAR.nsf/0/074608a2fa18b48a86256eeb006704ef!OpenDocument
