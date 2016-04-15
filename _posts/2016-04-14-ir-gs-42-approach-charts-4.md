---
layout: post
title:  "IR GS42 - Approach Chart Analysis (4)"
date:   2016-04-14 18:19:00
categories: instrument-training
---

# Granularity of Radar Coverage

Although radar coverage may not be available at an airport, it's worth keeping in mind how
the radar coverage (if you can get it) is affected by the different types of facilities.

If it's provided by an ARTCC facility (eg. Seattle Center), then the coverage would be at higher
altitudes and may or may not extend to the airport. In this case, you probably wouldn't expect
vectors to the final approach course, but could reasonably expect them to an IAF or feeder route.

If it's provided by an approach/departure controller, or the tower at the airport, then there's
a much higher chance that you may recieve more specific vectoring as you get closer to the final
approach course.

# Towered/Non-Towered Fields & Cancelling Flight Plans

 - when landing at a controlled airfield, the controller cancels your IFR flight plan for you
 - at an uncontrolled field, it's up to you to cancel the IFR flight plan
 - when landing IFR at an uncontrolled field, Center will release you to contact the unicom, CTAF,
   or advisory frequency
 - at this point, you'd change to the advisory frequency and give position reports
 - once you've landed, or in a position to land, call Center and tell them you'd like to cancel your
   flight plan
 - if you're unable to contact Center, you can either call the local FSS via an RCO or similar, or phone
 - **it's important to cancel a flight plan** because until you cancel, the controller cannot let another
   airplane into that airspace for landing (or any other purpose)

# NDB Approaches

 - NDB approaches are similar to VOR approaches, except they use an NDB as the primary navaid
 - they consist of flying a bearing to and/or from an NDB station
 - the NDB station may be co-located with a marker beacon

# Turns-to-Inbound Limits

 - if the turn on the feeder route to the final approach course at the FAF is **more than 30 degrees**, it's
   considered an excessive angle for getting safely established on the final approach course.
 - if the altitude difference between the mininmum altitude on the feeder route and the FAF is **more than
   300'** above the minimum altitude for crossing the FAF inbound, this makes the required descent for
   landing too steep for the FAA's taste, thus requiring a procedure turn

# MDA vs. Distance to MAP

 - even if you manage to see the runway or runway environment, it doesn't necessarily mean it would be
   safe to land
 - consider the case where you see the runway environment only when you're passing over the threshold,
   if you were at an MDA of 600', and travelling at 90 knots, you could easily have passed most of the
   runway by the time you descended to the runway elevation
 - this is part of the reason why the FAA allows you descend when you have some *parts* of the runway
   environment in sight ([FAA 91.175][faa-91-175] states you must have the required flight visibility
   and one of 10 specific runway environment items in sight - more on this later)
     - this essentially gives you a better chance of seeing something early and being able to descend
       in time
 - FAA 91.175 also says that you may only leave the MDA if the airplane is in a position from which a
   **descent to landing can be made by normal maneuvering while using a normal rate of descent**

# Approach to an Airport

 - as discussed earlier, some approaches don't have runway numbers associated with them, in which
   case the approach is to an *airport*, not a specific runway
 - an approach to an airport instad of a runway **only has circling minimums**
 - there are two main reasons an approach may be a circling approach instead of a straight in approach:
   1. if the final approach course is **offset more than 30 degrees** from the runway
   2. if the **descent rate** on final from the mininmum altitude *at the FAF to the runway threshold*
      is in **excess of 400'** per NM
      - *eg. 400FPM at 120 knots = 800' per NM*
      - circling minimums allow you to maneuver in order to dissipate altitude in preparation for landing
 - just because a controller tells you to circle for landing *doesn't mean you can't land straight in* if
   you're in a position to do so
     - it's possible the runway is more than 30 degrees off the final approach course, or the descent rate
     is excess of 400' per NM, but if you see the runway environment from a long way off, it may be safe
     for you to maneuver visually to land

# Additional Required Equipment for an Approach

 - some approaches may require additional equipment aside from the primary navaid in order to fly
   the approach, eg. DME, ATC radar
 - additional equipment required can be identified on the chart by a **note in the planview**
   - eg. the FUL LOC RWY 24 chart shows 'DME or RADAR REQUIRED' in the plan (top-down) view
 - if this additional equpiment is required *outside the final approach segment*, it will be noted
   in the briefing portion of the approach chart
 - **this equipment is mandatory** despite it not being shown in the title of the approach chart
 - this notes are *not* shown when VOR is required outside the final approach segment

**Keep in mind that an IFR approved WAAS-based GPS unit can be used as a substitude for VOR, DME,
and NDB.** It *can't* be used to track a VOR, localizer, or NDB course that's part of an approach's
finall approach segment **unless "GPS" is shown in the title** of the approach chart, and you fly
the approach as a GPS approach.
[faa-91-175]: http://rgl.faa.gov/Regulatory_and_Guidance_Library%5CrgFAR.nsf/0/66AFE97435E47B3A86256E1A00518D27?OpenDocument
