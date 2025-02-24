---
  title: Parafield (YPPF)
---

--8<-- "includes/abbreviations.md"

## Positions
| Name               | Callsign       | Frequency        | Login Identifier                         |
| ------------------ | -------------- | ---------------- | ---------------------------------------- |
| Parafield ADC  | Parafield Tower  | 118.700          | PF_TWR                        |
| Parafield SMC   | Parafield Ground  | 119.900          | PF_GND                       |
| Parafield ATIS        |                | 120.900          | YPPF_ATIS                                |


<figure markdown>
![YPPF Maneuvering Area](img/yppf_maneuvring_area.png){ width="500" }
  <figcaption>Maneuvering Area</figcaption>
</figure>

## Airspace
PF ADC is responsible for the Class D airspace in the PF CTR `SFC` to `A015`.

<figure markdown>
![PF ADC Airspace](img/PFTWR.png){ width="700" }
  <figcaption>PF ADC Airspace</figcaption>
</figure>

## Circuits
Circuits to be flown at `A010`

| Runway | Day  | Night |
| -------| -----| ------|
| 03L  | Left   | Left  |
| 03R  | Right  | -     |
| 21L  | Left   | -     | 
| 21R  | Right  | Right |
| 08L  | Left   | -     |
| 08R  | Right  | -     |
| 26L  | Left   | -     |
| 26R  | Right  | -     |

## VFR Inbound Procedures

| VFR Approach Point | RWYs 03 | RWYs 21 | RWYs 08 | RWYs 26 |
| ----------------| --------- | ---------- | ----- | ----- |
| Outer Harbour   | Join base (or downwind) RWY 21R | Join base (or downwind) RWY 03L | Join final RWY 08L| Join downwind RWY 26R | 
| Dam Wall | Join downwind RWY 03R | Join 3NM final RWY 21L| Join downwind RWY 08L | Join final RWY 26R |

!!! note
    Visually monitor all aircraft to ensure tracking South of Bolivar Strobe, to ensure aircraft remain outside of Edinburgh CTR. 
    <figure markdown>
    ![Bolivar](img/bolivar.png){ width="700" }
    </figure>

## ATIS
### Operational Info

ATIS broadcast **BY DAY** shall follow the format:   
`RWY 21R (OR 03L) FOR ARRS & DEPS WEST, RWY 21L (OR 03R) ARRS & DEPS EAST`  
OR   
`RWY 26R (OR 08L) FOR ARRS & DEPS, RWY 26L (OR 08R) FOR CCT TRAINING`
   
ATIS broadcast **BY NIGHT** shall follow the format:  
`RWY 21R (OR 03L) FOR ALL OPERATIONS`  

### Approach Expectation

The APCH field should include `EXP INST APCH` when:   
  - the ceiling is at or below `A020`; or  
  - visibility is less than 5000m  

## Coordination
### PF SMC / AD TCU
#### Taxi Call
For aircraft planned via a CTA departure into Adelaide's class C airspace, **PF SMC** will coordinate a clearance for the aircraft with the relevant Adelaide TCU position.  
Whilst the aircraft is taxiing, **PF SMC** will perform TAXI coordination with Adelaide TCU, who will issue an airways clearance for Parafield Tower to relay to the aircraft.  Aircraft planned above `A030` will be cleared initially to `A030`.
  
!!! example
    <span class="coldline">**PF SMC** -> **AD TCU**</span>: "Taxis, XMM for YSBK, 03L”  
    <span class="coldline">**AD TCU** -> **PF SMC**</span>: “XMM, cleared to YSBK via AD, flight planned route, PF1 Departure, climb via SID A030, squawk 1427”  
    <span class="coldline">**PF SMC** -> **AD TCU**</span>: “Cleared to YSBK via AD, flight planned route, PF1 Departure, climb via SID A030, squawk 1427, XMM”  

### AD TCU / PF ADC

#### Next Call
When aircraft planned via a CTA departure are ready for takeoff and expected to depart imminently, **PF ADC** shall seek release of the aircraft through a 'Next' call.

!!! example
    <span class="hotline">**PF ADC** -> **AD TCU**</span>: "Next, XMM, 03L"  
    <span class="hotline">**AD TCU** -> **PF ADC**</span>: "XMM, Heading 020, unrestricted"  
    <span class="hotline">**PF ADC** -> **AD TCU**</span>: "Heading 020, unrestricted, XMM"

The Standard Assignable level from PF ADC to AD TCU is the lower of `A030` or the `RFL`, any other level must be prior coordinated.
#### Arrivals
AD TCU will coordinate with PF ADC for incoming IFR arrivals on either Visual Tracking or RNP approaches.  
If tracking visually, AD TCU must coordinate the level assignment with the estimate for aircraft arriving directly from Class C.  
PF ADC must not alter an aircraft's tracking until the aircraft is within **3NM** of the aerodrome.

#### Visual Tracking
!!! example
    <span class="coldline">**AD TCU** -> **PF ADC**</span>: "Estimate, UJE via PAL time 02."  
    <span class="coldline">**PF ADC** -> **AD TCU**</span>: "UJE"

#### IAP Tracking
Reserved.