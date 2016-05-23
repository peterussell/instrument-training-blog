---
layout: post
title:  "IR GS 72 - IFR Weather Charts (4)"
date:   2016-05-22 15:30:00
categories: instrument-training
---

# Winds Aloft Forecast (FB)

 - issued **4 times daily**, valid for **6, 12,** or **24 hours** (each forecast
   includes a valid time for its use)
 - issued for true altitudes starting at 3,000', and up to 12,000' in 3,000'
   increments
 - **winds less than 1,500' AGL (above the reporting station) are *not forecast**
   (this isn't very 'aloft')
 - **temperatures less than 3,000' AGL (above the reporting station) are *not forecast***
 - winds aloft are provided in *knots,* direction is always in reference to *true
   North (as with other weather reports and forecasts)
 - encoding *2714* = wind from 270 deg at 14 knots
 - *temperatures*: the + or - after the winds represent a negative or positive
   temperature value, in **degrees Celsius**
    - *eg. 2321-04 means winds from 230 deg, at 21 knots, temperature -4 deg C*
 - **winds: light and variable are coded as 9900**
    - technically this means the winds are less than 5 knots
 - **winds: calm winds are coded as 0000**
 - forecast temperatures can be useful to figure out whether there's a temperature
   inversion, if you see forecast temperature increasing (not decreasing), you know
   you have an inversion - this means stable air and crappy visibility
 - **XC flight planning:** one of the most important things to check for XC flights
   is the winds aloft, you want to find an altitude give you less headwind and more
   tailwind

# Weather Depiction Chart

 - prepared from **METARs** - it provides you with a broad overview of weather
   conditions
 - issued **every 3 hours beginning at 0100Z** (1700 PST, 1800 PDT)
 - perhaps most useful for giving a view of **where VFR and IFR conditions prevail**
 - includes a key that gives the following information:
    - shaded areas: IFR with ceiling less than 1,000' and visibility less than 3 miles
    - contoured areas without shading: MVFR, ceilings 1,000' - 3,000', vis 3-5 miles
    - no counters: VFR with ceilings > 3,000', vis > 5 miles
 - **numbers and symbols surrounding the individual stations** inform you about:
    - cloud heights and coverage
    - weather and obstruction to vision
 - *note: the legend is provided to you for the knowledge exam, but it's still good
   to know the symbols - I'll omit them here but see page 10-24 of the text*
 - cloud height is determined the same was as for METARs and TAFs, by adding two
   zeroes to the numbers underneart the station circle
    - *example: '50' under station circle indicates the **height of the cloud coverage
      shown in the circle** is at 5,000'*
 - the Weather Depiction chart can be useful for **flight planning** because it quickly
   shows you where there's VFR or MVFR weather (in case you need to head that way in
   an emergency) and the positions of fronts and their movement

# Radar Summary Chart

 - issued **16 times during a 24-hour period** (some private weather services offer
   it 24 hours a day)
 - presents the **location of radar echoes resulting from precipitation** (usually
   water or hail) suspended in clouds
    - recall, radar energy doesn't reflect of *clouds*, it reflects off the *water in
      clouds* - therefore this only shows the locations of clouds with water in them
 - page 10-26 has a legend, this legend is **not available in the exam**
 - recall that precipitation heights and echo intensities provide a good idea of how
   nasty an area of precipition might be - taller returns with more intense echoes
   indiciate more water suspended, which requires stronger updrafts to suspend that
   greater amount of water
    - it's a good bet that any Level 3 storm (second contour or higher) indicates the
      presence of thunderstorms
 - finally, keep in mind that a Rady Summary chart (unlike other charts) **can show
   the lines and cells of hazardous thunderstorms - *if you see a solid line, you've
   got thunderstorms***

# Radar Weather Report (SD)

 - thuderstorms and general areas of precipitation can be observed by radar
 - a Radar Weather Report, or SD, may be transmitted as a separate report, or it may
   be included in a schedule weather broadcast by the FSS
 - although you may not come across them often, it's important to know how to read them:

*example: LZK 1133 AREA 4TRW +/+ 22/100 88/170 196/180 220/115 C2425 MT 31 AT 162/110*

 - this is a Little Rock (LZK) radar weather observation taken at 1133Z
 - an area of 4/10 coverage, containing thunderstorms (T) and heavy rain showers (RW)
   are increasing in intensity (+/+ ?)
 - the area it covers is defined by points reference from the LZK radar site:
    - 22 deg, 100NM
    - 88 deg, 170NM
    - 196 deg, 180NM
    - 220 deg, 115NM
 - cells are moving from 240 at 25 knots (C2425)
 - the maximum tops (MT) are at 31,000' MSL, and are at 162 deg at 110NM

# Low-Level Significant Weather Prognostic Chart

 - the **prognostic** chart gives a prognosis (future outlook) of the weather
 - it contains **similar information to a TAF, but in a graphical format**
 - it shows four different panels, two sets of two
    - the **two left panels are 12-hours, right panels are 24-hours**
    - the **two top panels are from the surface to 24,000' (400 millibar pressure level**,
      and the bottom two panels are **surface weather**
 - prog charts are **issued 4 times daily, approximately every 6 hours**
 - zig zag lines = freezing level at the surface
 - dashed lines = freezing level at altitude
 - thick, dashed, yellow lines indicate areas of turbulence - the amount of turblence
   is indicated inside the area
    - **altitudes:** 080/ indicates from the surface to 8,000', 130/050 means from
      5,000' to 13,000'
 - *there are a number of other symbols that aren't provided for the written test, shown
   on page 10-28*
 - the **12 and 24 hour surface prog charts** provide you with the expected location and
   movements of *fronts, pressure systems*, and their *generated weather*
    - **unshaded area within a solid line** indicates the forecast within that area
      will cover 30-50% of the area
    - **shaded area within a solid line** indicates the forecast within that area will
      cover >50% - 100% of the area during the first part of the forecast period
