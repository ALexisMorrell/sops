---
  title: Coordination
---

--8<-- "includes/abbreviations.md"
# SY TCU / ENR
#### Departures
Voiceless coordination is in place from SY TCU to all surrounding ENR sectors (**ARL** (and subsectors) to the North and East, **YWE** (and subsectors) to the West, **BIK** (and subsectors) to the South) for aircraft:  
Planned at or above F280: `Assigned F280`  
Planned below F280: `Assigned the RFL`  
with ADES YWLM at or above F130: `Assigned F130`  
with ADES YWLM below F130: `Assigned the RFL`  

Any aircraft not meeting the above criteria must be prior coordinated to ENR.

!!! example
    **SY TCU** -> **ARL**: "JST789, with your concurrence, will be assigned F240, for my separation with ANZ12"  
    **ARL** -> **SY TCU**: "JST789, concur F240"  

#### Arrivals
Standard assignable levels from ENR to SY TCU are as follows:  
via RIVET, BOREE, or MARLN: `A100`  
All other routes: `A090`  
# SY TCU Internal
### APP / DIR

Voiceless coordination is in place between APP and DIR, with the following conditions:

a) Assigned `A060`  
b) Routed/vectored as per the table below:

| STAR  | 07   | 16L  | 16R   | 25   | 34L | 34R
| ------| --------------| -------------- | ----- | -----|-----|-----|
| BOREE   |H240| LOC/IVA  | LOC/IVA  | H060 | STAR | STAR|
| MEPIL   |H240| STAR  | STAR  | H060 | H150 | H150|
| MARLN   |H240| H330  | H330  | STAR | H150 | STAR|
| RIVET  |STAR| H330  | H330  | H060 | STAR | STAR|
| ODALE |LOC| H330  | H330  | H060 | H150 | H150|

Where an aircraft needs to cross the approach paths or overfly Sydney to join the opposite circuit, the following altitudes shall be used until radar separation is established with respect to the approach paths:  
Eastbound: `A070`  
Westbound: `A080`

Any aircraft not meeting these requirements **must** be prior coordinated to DIR.

!!! example
    **QFA123** -> **SAS**: "QFA123, Requesting DCT SOSIJ"  
    **SAS** -> **QFA123**: "QFA123, Standby"  
    **SAS** -> **SFW**: "QFA123, requesting DCT SOSIJ"  
    **SFW** -> **SAS**: "QFA123, concur DCT SOSIJ"  
    **SAS** -> **SFW**: "DCT SOSIJ, QFA123"  
    **SAS** -> **QFA123**: "QFA123, Cancel STAR, Recleared DCT SOSIJ, A060"  
    **QFA123** -> **SAS**: "Cancel STAR, Recleared DCT SOSIJ, A060, QFA123"  

!!! example
    **SAS** -> **SFW**: "VOZ456, with your concurrence, will be assigned A070, for my separation with ABC"  
    **SFW** -> **SAS**: "VOZ456, concur A070"   

### APP / DEP
Aircraft are permitted cross the MARLN corridor at or above A060 without coordination with APP. DEP is responsible for separation with respect to aircraft in the corridor.
# SY TCU / SY ADC
#### Auto Release

Auto Release shall be used for aircraft that are:    
a) Departing from a runway nominated on the ATIS; and  
b) Issued a Procedural SID; and   
c) Assigned the standard assignable level.

Any aircraft that don't meet these criteria must be coordinated to SY TCU with a "Next" Call.

"Next" Coordination is a procedure where the **SY ADC** controller gives a heads-up to the SY TCU controller about an impending departure. The SY TCU controller will respond by assigning a heading to the aircraft, for the **SY ADC** controller to pass on with their takeoff clearance.

!!! example
    **SY ADC** -> **SY TCU**: "Next, ABC"  
    **SY TCU** -> **SY ADC**: "ABC, Heading 030"  
    **SY ADC** -> **SY TCU**: "Heading 030, ABC"  
    **SY ADC** -> **ABC**: "ABC, Assigned heading right 030, Runway 34R, Cleared for Takeoff"  
    **ABC** -> **SY ADC**: "Right heading 030, Runway 34R, Cleared for Takeoff, ABC"  
    `AIP GEN 3.4`

The SY TCU controller can suspend/resume Auto Release at any time, with the concurrence of **SY ADC**.
# SY TCU / BK TWR
#### Departures

Aircraft departing YSBK in to SY TCU Class C will be coordinated from **BK TWR** at Taxi. Aircraft will need to be passed airways clearances to **BK TWR** at this point, to be relayed to the aircraft.

!!! example
    **BK TWR** -> **SY TCU**: "Taxi, TFX12 for YMML via WOL"  
    **SY TCU** -> **BK TWR**: "TFX12, BK, WOL, Flight Planned Route, A030, Squawk 3601"  
    **BK TWR** -> **SY TCU**: "BK, WOL, Flight Planned Route, A030, Squawk 3601, TFX12"  
    **BK TWR** Will then pass the airways clearance to TFX12

**BK TWR** will then give a "Next" call, where the SY TCU controller shall assign a heading (usually 290, for separation from YSSY).

!!! example
    **BK TWR** -> **SY TCU**: "Next, TFX12"  
    **SY TCU** -> **BK TWR**: "TFX12, Right Heading 290, A030"  
    **BK TWR** -> **SY TCU**: "Right Heading 290, A030, TFX12"  
    **BK TWR** Will then clear the aircraft to takeoff with the assigned heading, and instruct them to contact SY TCU passing A020.

#### Arrivals

YSBK arrivals shall be coordinated to **BK TWR** from SY TCU prior to transfer of jurisdiction.

!!! tip
    Ensure the aircraft's FDR is up-to-date in order to give **BK TWR** maximum situational awareness of the traffic picture. (eg. if the aircraft is doing the RNP approach, ensure the FDR has been rerouted via the appropriate points)

!!! example
    **SY TCU** -> **BK TWR**: "ABC, via ODALE, Number 1"  
    **BK TWR** -> **SY TCU**: "ABC, Number 1"  

# SY TCU / CN TWR
#### Departures

Aircraft departing YSCN in to SY TCU Class C will be coordinated from **CN TWR** at Taxi.

!!! example
    **CN TWR** -> **SY TCU**: "Taxi, DEF for YBTH via KADOM"  
    **SY TCU** -> **CN TWR**: "DEF, Squawk 3601."  
    **CN TWR** -> **SY TCU**: "Squawk 3601, DEF"  

CN TWR will then give a "Next" call.

!!! example
    **CN TWR** -> **SY TCU**: "Next, DEF"  
    **SY TCU** -> **CN TWR**: "DEF"  
#### Arrivals

YSCN arrivals shall be coordinated to **CN TWR** from SY TCU prior to transfer of jurisdiction.

!!! example
    **SY TCU** -> **CN TWR**: "New Sequence of 2, ZYX, via TONTO, Number 1. QET, via WATLE, Number 2"  
    **CN TWR** -> **SY TCU**: "ZYX Number 1, QET Number 2"  
# SY TCU / RIC TWR

Reserved
