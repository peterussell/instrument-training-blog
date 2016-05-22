---
layout: post
title:  "IR GS 71 - IFR Weather Charts (3)"
date:   2016-05-22 14:30:00
categories: instrument-training
---

# Terminal Area Forecasts (TAFS)

 - TAFs are *forecast weather* for a **24 hour period** (30 hours for some locations),
   and issued **every 6 hours**
 - they represent the expected weather within a **5 SM radius of the airport's
   runway complex**
 - a TAF provides a description of **surface weather** you can *expect* to occur at an
   airport, they provide a good idea of the present weather and how it's expected to
   change
 - codes are similar to a METAR - we'll examine the different sections of a TAF

TAF<br>
KLAX 091140Z 0912/1012 22020KT 3SM -SHRA BKN020<br>
BECMG 0916/0919 33015KT<br>
FM 100300 35014KT 2SM TSRA OVC015<br>
TEMPO 1006/1012 1SM +RA PROB40 1008/1009 1/2SM FG<br>

The sections of this forecast are:

 - **Station: KLAX**
 - **Date Forecast Issued: 091140Z**
    - the 9th day at 1140 Zulu
 - **Time of Forecast: 0912/1012**
    - the valid times for the forecast, it begins on the 9th at 1200Z and is valid
      until the 10th at 1200Z (24 hours)
    - *if **midnight UTC** is the **beginning** time it will be coded as **00**, if
      it is the **ending** time it will be coded as **24***. eg. a 24 hour forecast
      beginning and ending at midnight might look like 0900/1024
 - **Forecast Winds: 22020KT**
    - forecast winds to be from 220 at 20 knots
 - **Forecast Visibility: 3SM**
 - **Forecast Weather: -SHRA**
    - these are the same as for a METAR, in this case light rain showers
 - **Forecast Cloud Conditions: BKN020**
 - **Expected Changes (BECMG, FM, TEMPO, PROB): BECMG**
    - **BECMG:** used when *gradual* changes in the previaling conditions are expected
      (usually over a period not to exceed 2 hours). BECMG is followed by two 4-digit
      numbers seperated by a slash *(0916/0919)* - the conditions that follow are
      expected to change gradually over that time period. **Any weather condition
      forecast prior to BECMG that is not revised following that time period is expected
      to remain the same.** For example, our report *BECMG 0916/0919 33015KT* means that
      the wind is expected to change to 330 at 15KT over that time period, but all
      other weather is expected to remain the same.
    - **FM:** is followed by a six digit number (the date and a four digit time value)
      that indicates the beginning time of a self-contained portion of the forecast.
      **This is used when a *rapid* significant change in weather (usually < 1 hour) is
      expected**. In our report *FM 100300 35014KT 2SM TSRA OVC015* indicates that from
      0300 on the 10th we expect wind to be 350 deg at 14kt, vis 2SM, thunderstorms and
      moderate rain, and overcast clouds at 1,500'.
    - **TEMPO:** indicates fluctuations that usually last less than 1 hour from the
      predominant weather conditions that are expected. TEMPO is two 4-digit numbers
      separated by a slash *(1006/1012)* giving the date and time period that these
      variations are expected. In our case have *TEMPO 1001/1012 1SM +RA* which means
      from the 10th at 0100Z to the 10th at 1200Z, we expect visibility of 1SM with
      heavy rain.
    - **PROB:** PROBability is used when the likely occurrence of any weather
      phenomena falls into the **30-39% (PROB 30) or 40-49% (PROB 40)** range of
      expectation. If the probability is 50% or higher, the terms BECMG, TEMPO, or
      FM will be used. In our report *PROB40 1008/1009 1/2SM FG* indicates that
      on the 10th between 0800Z and 0900Z there is a 40 to 49% probability of 1/2SM
      visibility in fog.

# Area Forecasts (FA)

 - an Area Forecast (FA) is a general forecast often covering several states
 - they're issued **three times daily** for **six specific areas in the lower 48**
 - they are **12 hour forecasts with an additional 6 hour outlook**
 - the area forecast presents its **cloud heights in MSL** rather than AGL (unless
   noted by AGL or ceiling designation)
    - this makes sense, the area forecast isn't for a specific spot, and covers many
      different elevations
 - in the Area Forecast (FA), **CIG = Ceiling**
 The FA consists of four sections

    1. Communications and header section
      - information about the forecast times (synopsis 18 hours, WX/clouds 12 hours,
        outlook 6 hours from the end of the WX/clouds), types of information in the
        report, and areas covered (states, areas, etc.)
    2. Precautionary statements section
      - these will point out that hazardous information is available in AIRMETs and
        SIGMETs **(AIRMETs and SIGMETs *aren't* included in the FA)**, and other
        information that's required to know while reading the FA, *eg. TS IMPLY
        SEV OR GTR TURB SEV ICE LLWS AND IFR CONDS. NON MSL HGTS DENOTED BY AGL OR
        CIG.*
    3. Synopsis section
      - the *big picture* of what's going on. It's a brief summary of the **location
        and movements of fronts, pressure systems, and circulation systems** for
        an 18 hour period
    4. VFR clouds and weather section
      - includes a 12 hour specific forecast, followed by a 6 hour categorical outlook,
        giving a total forecast period of 18 hours. Often broken down by states or
        well-known geographical areas.
      - a **general description of clouds and weather with covers an area of *greater
        than 3,000 square miles* and is significant to VFR flight** follows each of
        the listed geographical areas

*For more information and to see how to an actual FA is decoded see page 10-19 in the
text.*
