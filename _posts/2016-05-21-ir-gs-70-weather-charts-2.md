---
layout: post
title:  "IR GS 70 - IFR Weather Charts (2)"
date:   2016-05-21 22:01:00
categories: instrument-training
---

# ADS-B / FIS-B

ADS-B stands for **Automated Dependent Surveillance-Broadcast**. With it comes a great form of uplinked
cockpit weather called **FIS-B**. To understand how FIS-B works we need to look quickly at ADS-B first.

ADS-B is a revolutionary new way of identifying and controlling air traffic. **The main idea** is that
instead of bouncing radar waves from a ground-based antenna off flying airplanes, then trying to interpret
the ghostly signal, why not let the airplanes send the signal themselves?

ADS-B uses conventional Global Navigation Satellite System (GNSS) technology and a relatively simple
broadcast communications link as its fundamental components. It does this with a **Universal Access
Transceiver (UAT).** Garmin's GDL 90 is an example of a UAT that interfaces with an MFD. This UAT is
remotely mounted in your airplane and designed to transmit, receive, and decode ADS-B messages sent
from other airplanes and from ADS-B ground stations (called **Ground-Based Transmitters, or GBTs**).

**This data link broadcasts your aircraft's position, velocity, projected track, and flight identification**
to other ADS-B equipped aircraft in your area, as well as to GBTs. As of 2014 the network of GBTs covers
the whole United States.

The interesting thing about **GBTs is that they can send weather information such as NEXRAD, METARs, TAFs,
TFR information** (etc.) directly to your airplane via a data uplink. This gives you access to full time
weather in real time without having to call the AFSS. Of course, you'll need some sort of MFD in the
cockpit in order to show this information.

To use ADS-B and FIS-B, your airplane will need to established a two-way data link with the ground using
a UAT.

As an aside, it's not necessary to have ADS-B in order to *receive* uplinked weather in the cockpit. You
can, for example, purchase a Garmin 496 GPS unit and activate its weather uplink service. This will give
you weather, terrain, and airport info.

# Weather Advisories

**Center Weather Advisory (CWA)**

 - a *Center Weather Advisory* is an aviation warning that can be used to anticipate and avoid adverse
   weather in the enroute and terminal environments.
 - CWAs are created primarily for use by ATC, but they're available online
 - each CWA is an accumulation of the latest monitoring, analysis and interpretation of real time weather
 - technically, a CWA is not a flight planning product, but since it reflects current conditions expected
   at the time of issuance and/or is a short-range forecast for within 2 hours of issuance, it certainly
   has flight-planning value
 - CWAs are valid for a **maximum of two hours** - if conditions are expected to continue beyond the
   two-hour valid period, a statement will be included in the CWA
 - a CWA may be issued in the following three situations:
    1. as a **supplement to an existing in-flight aviation weather advisory** for the purpose of imporving
       or updating the definition of the phenomenon in terms of location, movement, extent, or intensity
       relevant to the ARTCC
        - *example: say a SIGMET for severe turbulence has been issued by the AWC in Kansas City, MO, and the
          outline covers the entire ARTCC area for the total four-hour valid time period. Three tornados,
          however, have appeared in one relatively small area. In this case the forecaster will issue a CWA
          covering only the affected portion of the ARTCC area.*
    2. **when an in-flight aviation weather advisory has not been issued but conditions meet the criteria**,
       based on current PIREPs, and the information must be disseminated sooner than the AWC can issue the
       in-flight avication weather advisory. In the case of an impending SIGMET, the CWA will be issued as
       urgent (UCWA) to allow the fastest possible dissemination of information
    3. **when in-flight aviation weather advisory criteria are not met but conditions are or will shortly
       be adversely aaffecting the safe flow of air traffic within the ARTCC area**

*Example of a CWA:*

ZME1 CWA 081300<br>
ZME CWA 101 VALID UNTIL 081500<br>
FROM MEM TO JAN TO LIT TO MEM<br>
AREA SCT VIP 5-6 (INTENSE-EXTREME) TS MOVFROM 26025KT. TOPS TO FL450.

 - issued by the Memphis Tennessee (TN) ARTCC
 - the 1 after ZME in the first line denotes this CWA has been issued for the first weather phenomenon
   to occur for the day
 - it was written on the 8th at 1300Z
 - the 101 in the second line denotes the phenomenon number again (1) and the issuance number (01) for
   this phenomenon
 - the CWA is valid until the 8th at 1500Z
 - the area is bounded by Memphis, to Jackson, Little Rock, and back to Memphis
 - within the CWA is an area with scattered level 5-6 (intense to extreme) precipitation thunderstorms
   moving from 260 deg at 25 knots
 - tops of the thunderstorms are at FL450

You can have direct access to CWAs by visiting the NWS web site

# Weather Reports

There are many other weather reports available from the National Weather Service (NWS) and private weather
services to aid pilots in flight planning. Being able to find and interpret this information is an
important IFR skill.

Available weather products are available in two basic types: *observation* and *forecast*. Observations
are *historical*, they're the weather conditions that existed at the time of the observation. Forecasts
are *weather estimates* for several hours (sometimes days) in the future.

Here we'll examine the different types of charts.

# METARs

METARs are already fairly familiar, so I'll just include anything that was a surprise or less-known (or..
just less known to me).

 - the letters *SPECI* before a METAR indicate a special METAR, special, unscheduled reports as a result
   of a significant weather change
 - the METAR includes a number of different sections, which can be remembered by the sequence *Should Tina
   Walk Vera's Rabbit Without Checking The Dog's Appetite?*
    - **S**tation Idenficiation
    - **T**ime in Zulu or UTC
    - **W**ind direction and velocity
    - **V**isibility
    - **R**unway Visual Range (if available)
    - **W**eather
    - **C**louds
    - **T**emperature
    - **D**ewpoint
    - **A**ltimeter setting
 - gusts are reported when a 10 knot fluctuation occurs between the wind's peaks and lulls
 - a calm wind is reported as **00000KT**
 - variable (VRB) is reported if the wind speed is **5 knots or less**
 - if the wind direction **varies by 60 degrees or more and the speed is greater than 6 knots** then
   the variable wind direction follows the reported wind, eg. **280V350** (always in clockwise order)
 - in *visibility*, the US is an exception in reporting prevailing visibility as the *greatest
   visibility equalled or exceeded through at least one-half of the horizin circle, but not necessarily
   contiguous*. Significant differences in any sector from the prevailing visibility or a differing
   tower visibility will be stated in the remarks (RMK)
 - RVR is an **electronically measuredvalue used to determine the distance (in hundreds of feet) down
   a runway that a pilot can see HIRL**
    - an M or P prefix before the RVR indicates its value is below the minimum value measurable, or
      above the maximum value measureable by the system (respectively)
 - the Weather section includes all of the weather codes and qualifiers etc. We'll cover these in depth
   after these points
 - clouds: when the sky is obscured and cloud details can't be assessed, but information on vertical
   visibility *is* available, the cloud group is replaced by a five-character group. The first two
   characters are **VV** (vertical visibility) followed by the VV in hundreds of feet. eg. VV004 means
   the vertical visiblity is 400'

# AWOS vs ASOS

**AWOS (Automatic Weather Observing System)**

The main difference is that **AWOS stations are typically operated by the FAA or private agencies, while
ASOS stations are controlled by the NWS or DOD**. (Think of the weather service providing systems that
are able to report on more information - ie. precip - mentioned below).

 - broadcast minute-by-minute, real-time, local weather information
 - receivable within 25NM, at or below 10,000' AGL
 - four basic levels of AWOS are available
    1. AWOS-A reports only altimeter setting
    2. AWOS-1 usually reports altimeter, wind, temperature, dewpoint, density altitude
    3. AWOS-2 reports AWOS-1 plus visibility
    4. AWOS-3 reports AWOS-2 plus cloud-ceiling
 - AWOS only reports vertical visibility directly above the stations

**ASOS (Automatic Surface Observing System)**

 - sort of an AWOS on steriods
 - in addition to basic weather measurements, it **also reports precipitation type and intensity,
   and occurrence of freezing rain**
 - also receivable within 25NM, at or below 10,000' AGL

# AWOS/ASOS vs METAR

 - ASOS *can't report clouds above 12,000'*
    - it will report CLR (clear) instead of SKC (sky clear) - if there's a solid overcast at 15,000'
      the ASOS won't see it
 - automated (printed) reports include the word **AUTO** - when a human observer interprets the output
   they remove the word AUTO from the report
 - similarly, the word **COR** indicates that a human manually made a correction to the METAR
 - **AO1/AO2** in the remarks section of an **ASOS** indicates the level of sophistication of the
   precipitation discrimination sensors associated with the ASOS unit
    - **AO2** can discriminate between different liquid and frozen precipitation, rain, snow, etc.


