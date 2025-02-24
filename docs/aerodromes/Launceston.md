---
  title: Launceston (YMLT)
---

--8<-- "includes/abbreviations.md"

## Positions

| Name              | Callsign       | Frequency        | Login Identifier                         |
| ----------------- | -------------- | ---------------- | ---------------------------------------- |
| Launceston ADC    | Launy Tower   | 118.700    | LT_TWR                         |
| Launceston ATIS       |                | 134.750          | YMLT_ATIS                                |

### Maneuvering Area Responsibility
<figure markdown>
![YMLT Maneuvering Area](img/ymlt_maneuvring_area.png){ width="500" }
</figure>

## Airspace
LT ADC is responsible for the Class D airspace in the LT CTR `SFC` to `A015`.

<figure markdown>
![Launceston Tower Airspace](img/LTTWR.png){ width="700" }
</figure>

Refer to [Class D Tower Skills](../../controller-skills/classdtwr) for more information.

## SID Selection
Aircraft planned via **IRSOM**, **ONAGI**, **NUNPA**, **MOTRA**, **IRONS**, **MORGO**, **KAREN**, **TASUM**, or **NOLAN**, shall be assigned the appropriate **Procedural SID**.  Other aircraft shall be assigned a visual departure.

## VFR Operations

### Circuit Direction
| Runway | Day | Night |
| ------ | ------ | ----|
| 14L     | Left  | - |
| 14R    | Right | Right |
| 32L     | Left  | Left |
| 32R     | Right | - |
| 18     | Left  | - |
| 36     | Left  | - |

## Coordination
### Departures
'Next' coordination is required to LTA for aircraft that are:   
  a) Departing from a runway not nominated on the ATIS; or  
  b) Not assigned the standard assignable level; or  
  c) Not assigned a SID

!!! example
    <span class="hotline">**LT ADC** -> **LT TCU**</span>: "Next, ABC, runway 14L"  
    <span class="hotline">**LT TCU** -> **LT ADC**</span>: "ABC, Heading 150 Visual, unrestricted"  
    <span class="hotline">**LT ADC** -> **LT TCU**</span>: "Heading 150 Visual unrestricted, ABC"   

    **LT ADC**: "ABC, turn right heading 150 Visual, Runway 14L, Cleared for Takeoff"  
    **ABC**: "Right heading 150 Visual, Runway 12, Cleared for Takeoff, ABC"

The LTA controller can suspend/resume Auto Release at any time, with the concurrence of **LT ADC**.

The controller assuming responsibility of **LT ACD** shall give heads-up coordination to LTA controller prior to the issue of the following clearances:  
a) VFR Departures  
b) Aircraft using a runway not on the ATIS  

The Standard Assignable level from LT ADC to LTA is:  
For Jets: `A080`  
For Non-Jets: The lower of `A045` or the `RFL`.
### Arrivals
LTA will coordinate all YMLT arrivals to LT ADC prior to 5 mins from the boundary.