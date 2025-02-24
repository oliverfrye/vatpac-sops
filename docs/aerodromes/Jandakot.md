---
  title: Jandakot (YPJT)
---

--8<-- "includes/abbreviations.md"

## Positions

| Name               | Callsign       | Frequency        | Login Identifier                         |
| ------------------ | -------------- | ---------------- | ---------------------------------------- |
| Jandakot ADC  | Jandakot Tower  | 118.100          | JT_TWR                        |
| Jandakot SMC  | Jandakot Ground   | 124.300          | JT_GND                       |
| Jandakot ATIS     |                | 128.650          | YPJT_ATIS                                |


<figure markdown>
![YPJT Maneuvering Area](img/ypjt_maneuvring_area.png){ width="500" }
  <figcaption>Maneuvering Area</figcaption>
</figure>

## Airspace
JT ADC is responsible for the Class D airspace in the JT CTR `SFC` to `A015`.

<figure markdown>
![JT ADC Airspace](img/JTTWR.png){ width="700" }
  <figcaption>JT ADC Airspace</figcaption>
</figure>

## Fixed-Wing Operations
### VFR Inbound Procedures
VFR aircraft will report inbound at `BOAT`, `POWR`, `OAKF` or `RUSS` at `A015`. JT ACD will instruct aircraft to maintain `A015` or remain outside the control zone (workload permitting). Aircraft will then report again at `ADWD` when inbound from `BOAT` or `POWR`, or `FDL` when inbound from `OAKF` or `RUSS`. They should then be instructed to join the circuit as below:

| VFR Approach Point | RWYs 06  | RWYs 24 | RWY 12 | RWY 30 |
| ----------------| --------- | ---------- | ---------- | --------- |
| Adventure World (ADWD)   | *"Join base runway 06L"* | *"Join right downwind runway 24R, maintain A015"*, until the aircraft are clear of RWY 24R departures via `Fiona Stanely Hospital` and `FREM`, then *"Cleared Visual Approach"*  | *"Join final runway 12"* | *"Join downwind ruwnay 30, maintain A015"*, until the aircraft is clear of RWY 30 departures via `YGB`, then *"Cleared Visual Approach"* |
| Forestdale Lake (FDL)  | *"Join downwind runway 06L, maintain A015"*. Aircraft should fly overhead the airfield between the control tower and the upwind end of the runway and join the circuit. Once established in the circuit, *"Cleared visual approach"* | *"Join right downwind runway 24R, maintain A015"*. Aircraft should fly overhead the airfield between the control tower and the upwind end of the runway and join the circuit. Once established in the circuit, *"Cleared visual approach"* | *"Join right downwind runway 12"* | *"Join final runway 30"* |

All aircraft will arrive on runway 06L/24R or 12/30.

!!! note
    Circuit joining instructions given without an assigned altitude imply clearance to conduct the visual approach. There is no need to clear these aircraft for a visual approach.

### VFR Outbound Procedures
VFR aircraft should report ready to **JT ADC** with their departure intentions.  A takeoff clearance constitutes a clearance to depart the zone by extending the pilot's requested leg of the circuit.  Aircraft departing the zone into class G airspace will transfer to area frequency upon leaving the zone, **no explicit frequency transfer is given to these aircraft**.

Aircraft departing a leg of the circuit will climb to and maintain the following levels until clear of the zone:  
All runways: `A010`  

VFR aircraft will depart via set outbound departure routes. Aircraft will track extended circuit legs to the departure point. These departure points include: `YGB`, `FREM` via `Fiona Stanley Hospital`, and `SHOP`.

Departures via `FREM` and `YGB` will depart on runway 06L/24R. Runway 06R/24L is used for circuit traffic and departures via `SHOP`.

### Circuits
The circuit direction changes depending on tower opening hours and runway being used.

| Runway | Tower Open   | Tower Closed |
| -------| ----- | ----- |
| 06L    | Left  | Right |
| 06R    | Right | -  |
| 24L    | Left  | -   |
| 24R    | Right | Left  |
| 12     | Left  | Left  |
| 30     | Left  | Left  |

Circuits to be flown at `A010`

## IFR Inbound Procedures
Aircraft arriving from the Perth Class C in VMC will track via `CNB`. These aircraft will contract **JT ADC** approaching `CNB` and will be issued circuit joining instructions.  
Aircraft in IMC will track inbound via an instrument approach.  
**PH TCU** will coordinate all IFR arrivals in accordance with coordination procedures.

## Helicopter Operations
### General
Unless otherwise depicted in the `ERSA FAC YPJT`, all helicopters must comply with fixed wing procedures.

### Circuits
Circuits are conducted within the lateral confines of the fixed-wing circuit at `A008`, in the same direction as the current runway config.  The termination point of the circuit is the Main Pad.


## ATIS
### Runway Nomination
The ATIS must indicate the current runway config and nominate what each parallel runway is being used for.  The northern runway (06L/24R) is primarily used for VFR arrivals and departures, the southern runway (06R/24L) for circuit training and departures via `SHOP`, and the cross runway (12/30) for arrivals/departures when weather is unsuitable for parallel rwunay operations.  

This should be reflected on the ATIS as below:  
`RWY 06R FOR CIRCUITS AND DEPARTURES VIA ARMADALE SHOPS; RWY 06L FOR ARRIVALS AND ALL OTHER DEPARTURES`  
`RWY 24L FOR CIRCUITS AND DEPARTURES VIA ARMADALE SHOPS; RWY 24R FOR ARRIVALS AND ALL OTHER DEPARTURES`

When PH RWY 03 is in operation, the ATIS should include:
`DUE PERTH DUTY RUNWAY 03, CAUTION WAKE TURBULANCE`
## Coordination
### JT SMC / PH TCU

#### Taxi Call
For aircraft planned into the overlying class C airspace, an airways clearance must be coordinated with the TCU controller responsible for Perth Approach or Departures (dependant on runway configuation at PH).  This is achieved by performing 'Taxi' coordination and then relaying the clearance to the aircraft when they are ready in the run up bays.

!!! example
    <span class="coldline">**JT SMC** -> **PH TCU**</span>: "Taxis FD420, YKBR, runway 24R"  
    <span class="coldline">**PH TCU** -> **PH SMC**</span>: "FD420, cleared to YKBR via RECKS flight planned route, MANTL3 depature, climb via SID A030, squawk 3342"  
    <span class="coldline">**JT SMC** -> **PH TCU**</span>: "Cleared to YKBR via RECKS flight planned route, MANTL3 depature, climb via SID A030, squawk 3342, FD420" 


### JT ADC / PH TCU

#### Next Call
When the aircraft is ready for departure, Tower will coordinate with the relevant Class C sector above them for permission to release the aircraft into their CTA.

!!! example
    <span class="hotline">**JT ADC** -> **PH TCU**</span>: "Next, FD420, runway 24R"  
    <span class="hotline">**PH TCU** -> **JT ADC**</span>: "FD420, Unrestricted"  
    <span class="hotline">**JT ADC** -> **PH TCU**</span>: "Unrestricted, FD420"  

The Standard Assignable level from JT ADC to PH TCU is the lower of `A030` or the `RFL`, any other level must be prior coordinated.

#### Arrival Coordination
PH TCU will coordinate with JT ADC for incoming IFR arrivals on either Visual Tracking, RNAV or NDB approaches.

##### Visual Tracking
!!! example
    <span class="coldline">**PH TCU** -> **JT ADC**</span>: "Estimate, FD416 via `CNB` time 02."  
    <span class="coldline">**JT ADC** -> **PH TCU**</span>: "FD416"

##### IAP Tracking
!!! example
    <span class="coldline">**PH TCU** -> **JT ADC**</span>: "Estimated approach time, FD416 via RNAV-Z at time 59"  
    <span class="coldline">**JT ADC** -> **PH TCU**</span>: "Via RNAV-Z, FD416"  

Given that the instrument approach procedure will terminate inside another controller's airspace, TCU controllers must obtain a clearance from JT ADC prior to issuing an approach clearance to an aircraft.  If no conflict exists, respond to this call by providing clearance for the approach.  

!!! example 
    <span class="hotline">**PH TCU** -> **JT ADC**</span>: "Request clearance for final, FD416"  
    <span class="hotline">**JT ADC** -> **PH TCU**</span>: "FD416 cleared RNAV-Z 24R"  
    <span class="hotline">**PH TCU** -> **JT ADC**</span>: "Cleared RNAV-Z 24R, FD416"  

!!! tip
    Remember that IFR aircraft are only separated from other IFR or SVFR aircraft in class D.  You should *generally* be able to issue a clearance for an approach and use other separation methods (visual separation, holding a departure on the ground) if separation is required with these aircraft.