---
  title: Adelaide (YPAD)
---

--8<-- "includes/abbreviations.md"

## Positions

| Name               | Callsign       | Frequency        | Login Identifier                         |
| ------------------ | -------------- | ---------------- | ---------------------------------------- |
| Adelaide ADC    | Adelaide Tower   | 120.500          | AD_TWR                                   |
| Adelaide SMC    | Adelaide Ground  | 121.700          | AD_GND                                   |
| Adelaide ACD         | Adelaide Delivery| 126.100          | AD_DEL                                   |
| Adelaide ATIS        |                | 134.500         | YPAD_ATIS                                |

## Airspace
AD ADC is responsible for the Class C airspace in the AD CTR `SFC` to `A015`.

<figure markdown>
![AD ADC Airspace](img/adadc.png){ width="700" }
  <figcaption>AD ADC Airspace</figcaption>
</figure>

### Maneuvering Area Responsibility

<figure markdown>
![YPAD Maneuvering Area](img/ypad_maneuvring_area.png){ width="500" }
  <figcaption>YPAD Maneuvering Area</figcaption>
</figure>

## Runway Modes
Single runway operations using Runway 05 or 23 (whichever is more favoured by the winds) are preferred at YPAD. However, when strong winds favour Runway 12 or 30, Non-Jets (Runway 12/30 is too short for most jets) would benefit from having that runway available to them as well. As a general rule of thumb, if the Crosswind on Runway 05/23 exceeds **20kts**, the more favourable of Runway 12 or 30 shall be in use as well as the more favourable of Runway 05 or 23.

!!! example
    METAR: `YPAD 210600Z 15030KT 9999 FEW030 21/11 Q1002 RMK RF00.0/000.0`  
    ATIS: `RUNWAY 23 AND 12 FOR ARRIVALS AND DEPARTURES`

### Runway 23 Arrivals
With **Runway 23** in use for arrivals and the cloud base above `A024` but below `A043`, the APCH field shall include:  
`ACFT FM THE EAST AND JET ACFT FM THE WEST EXP INSTR APCH`  

This allows aircraft on the Victor STAR from the west to join a visual right base without the need to conduct an instrument approach, while keeping aircraft from the east clear of the higher terrain near the Adelaide Hills.

### Curfew Mode

Between the hours of 1330-2030 UTC (1230-1930 UTC HDS), AD ADC may elect to simulate Curfew operations, ie: **Runway 23 for arrivals, Runway 05 for departures**. When this is in operation, the ATIS shall include `CURFEW IN OPERATION UNTIL (time) ZULU`.

## SID Selection

Jet Aircraft planned via **PANKI**, **BENDO**, **GILES**, **HAWKY**, **ORBUN**. or **SEDAN**, shall be assigned the **Procedural SID** that terminates at the appropriate waypoint. Jet Aircraft **not** planned via any of these waypoints shall receive amended routing via the most appropriate SID terminus, unless the pilot indicates they are unable to accept a Procedural SID.

!!! example
    Jet Aircraft planned via PANKI, assigned runway 23, shall be given the PANKI SID.

a) Non-Jet Aircraft; or  
b) Aircraft using Runway 12/30; or  
c) Aircraft that cannot accept a Procedural SID  
Shall be assigned the **Radar SID**.

!!! example
    Non-Jet Aircraft planned via EEMUE, assigned runway 05, shall be given the AD (RADAR) SID.

## Coordination
### Auto Release
'Next' coordination is required to AD TCU for aircraft that are:   
  a) Departing from a runway not nominated on the ATIS; or  
  b) Not assigned the standard assignable level; or  
  c) Not assigned a **Procedural** SID

!!! example
    <span class="hotline">**AD ADC** -> **AD TCU**</span>: "Next, RXA4362, Runway 23"  
    <span class="hotline">**AD TCU** -> **AD ADC**</span>: "RXA4362, Track Extended Centreline, Unrestricted"  
    <span class="hotline">**AD ADC** -> **AD TCU**</span>: "Track Extended Centreline, Unrestricted, RXA4362"  
    
    **AD ADC**: "RXA4362, Track Extended Centreline 222 degrees, Runway 23, Cleared for Takeoff"  
    **RXA4362**: "Track Extended Centreline 222 degrees, Runway 23, Cleared for Takeoff, RXA4362"

The AD TCU controller can suspend/resume Auto Release at any time, with the concurrence of **AD ADC**.

The Standard Assignable level from AD ADC to AD TCU is:  
For Jets: `A050`  
For Non-Jets: The lower of `A040` or the `RFL`

### Departures Controller
Refer to [Adelaide TCU Airspace Division](../../terminal/adelaide/#airspace-division) for information on airspace divisions when **AAE** is online.