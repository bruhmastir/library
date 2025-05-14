# 2. Ground Movement Control ("Salalah Ground")
## 2.1 General Provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

GMC is also responsible for managing aircraft movements on all aerodrome movement areas except for runways and their associated taxiways. Departing aircraft are given pushback instructions and instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed to taxi as appropriate. 

## 2.2 Departure Clearance
#### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

- Callsign;
- Aircraft type;
- Parking stand;
- Destination
- ATIS letter and QNH;
  
#### 2.2.2 Information Contained in a Departure Clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

!!! example
    **Pilot**: "Salalah Ground, QTR1131, Airbus A320, information B, stand 12, clearance to Doha-Hamad."

    **Controller**: "QTR1131, Salalah Ground, information B correct, cleared to Doha-Hamad via the DAXAM1S departure, initial climb 10,000 ft, squawk 4701."

    **Pilot**: "Cleared to Doha-Hamad via the DAXAM1S departure, initial climb 10,000 ft, squawk 4701, QTR1131."

    **Controller**: "QTR1131, readback correct, QNH 1004, report ready for pushback."

!!! note
    GMC must obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

#### 2.2.3 Aircraft Requiring a Reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged. 

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

## 2.3 Departure Procedures
### 2.3.1 RNAV Instrument Departures
Salalah primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use. 

!!! info
    RNAV SIDs which have an identifier ending in **Q** are valid for **07.** RNAV SIDs with an identifier ending in **S** are valid for **25.** *(Table 2-1)*

| First Fix |       07      |   Initial Climb   |     25    |   Initial Climb   |
|:---------:|:-------------:|:-----------------:|:---------:|:-----------------:|
|   DAXAM   |    1Q/**1U**  |      10,000 ft    |     1S    |      10,000 ft    |
|   LADAR   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
|   MUTVA   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
|   SILTA   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
<figure markdown>
  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

!!! warning
    The DAXAM1S and LADAR1Q departures require radar surveillance and must not be assigned if radar coverage is unavailable. Assignment of the MUTVA1Q departure depends on the activation status of the OO(D)-65 danger area. The DAXAM departure offers two routing options: DAXAM1Q and DAXAM1U, DAMXAM1U routes aircraft over the sea to avoid terrain. Aircraft unable to meet the required climb gradients must inform ATC during the clearance request to avoid being assigned a straight-out departure over the terrain.

### 2.3.2 Conventional Instrument Departures
Aircraft unable to comply with RNAV Standard Instrument Departures (SIDs) shall be assigned a conventional (non-RNAV) Instrument Departure procedure as an alternative.

!!! info
    Conventional SIDs which have an identifier ending in **P** are valid for **07.** Conventional SIDs with an identifier ending in **R** are valid for **25.** *(Table 2-2)*

| First Fix |       07      |   Initial Climb   |     25    |   Initial Climb   |
|:---------:|:-------------:|:-----------------:|:---------:|:-----------------:|
|   DAXAM   |    1P/**1T**  |      10,000 ft    | 1R/**1V** |      10,000 ft    |
|   LADAR   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
|   MUTVA   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
|   SILTA   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
<figure markdown>
  <figcaption>Table 2-2: Conventional SIDs</figcaption>
</figure>

!!! warning
    Assignment of the MUTVA1P departure depends on the activation status of the OO(D)-65 danger area. The DAXAM departure offers two routing options: DAXAM1P/DAXAM1T and DAXAM1R/DAXAM1V, DAMXAM1T and DAXAM1V routes aircraft over the sea to avoid terrain. Aircraft unable to meet the required climb gradients must inform ATC during the clearance request to avoid being assigned a straight-out departure over the terrain.

## 2.4 Rerouting Aircraft
An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-3. 

Several routing restrictions exist within the Muscat airspace and must be complied with when issuing a departure clearance.

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.

| Destination                       | Level Restrictions | Routing                                           |
|-----------------------------------|--------------------|---------------------------------------------------|
| OOMS & OOMM                       |          -         | DAXAM Y414 MCT                                    |
| OOSH                              |          -         | DAXAM Y414 DEDSO R401 VELIK Y515 EMISO Q730 LADBI |
| Landing Northern U.A.E Airports   |          -         | DAXAM Y414 DEDSO R401 MUSAP                       |
| Landing Southern U.A.E Airports   |          -         | DAXAM Y414 DEDSO R401 DOLFI P558 SODEX            |
| Exiting the Muscat FIR Northbound |          -         | DAXAM Y414 DEDSO R401 HAI then as filled          |
<figure markdown>
  <figcaption>Table 2-3: Standard routes</figcaption>
</figure>

!!! info 
    Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In **all** cases, the next lowest valid cruise level should be assigned and the aircraft advised.

    Offering two valid levels (one above and below their requested level) is discouraged; a lower level than what is requested can be complied with certainty factoring the aircraft's maximum capable cruise level as per their gross weight. On the other hand, higher levels may be rejected due to aircraft performance or maximum cruise altitude capabilities.

    Thus, resorting to issuing the next lowest valid cruise level minimises radio transmissions and simplifies the correction process between the controller and the aircraft.

## 2.6 Runway Change Procedure

AIR shall provide ample notice to GMC before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMC, and RDR. 

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 2.7 VFR Aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Salalah Visual Approach**” chart for VFR traffic navigating out of the Salalah ATZ into neighbouring airspaces. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 2.7.1 and 2.7.2.

### 2.7.1 VFR Departures into Controlled Airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. As Salalah Radar operates within the Salalah ATZ (Class D) and its own CTR (Class C), coordination with Salalah Radar is required when online for all VFR departures.

All VFR departures shall initially be assigned a squawk code of 7000. Salalah Radar may issue a discrete squawk code for identification purposes if necessary.

!!! example
      **Pilot:** Salalah Ground, A4O-OAD, Diamond DA40, request eastbound departure on track Mukhaizna, altitude 7,500 ft.

      **Controller:** A4O-OAD, Salalah Ground, cleared eastbound departure, altitude 7,500 ft VFR, Runway 07, squawk 7000.

      **Pilot:** Cleared eastbound departure, altitude 7,500 ft VFR, Runway 07, Squawk 7000, A4O-OAD.

      **Controller:** A4O-OAD, readback correct. QNH 1004, Report ready for start-up.

### 2.7.2 VFR Traffic Remaining in Circuit
All VFR aircraft shall be instructed to conduct circuits to the south of the aerodrome (left-hand circuits for 25 and left-hand circuits for 07) at an altitude of 1,100 ft.

All VFR departures shall initially be assigned a squawk code of 7000. Salalah Tower may issue a discrete squawk code for identification purposes if necessary.

## 2.8 Departure Pushback Procedures
### 2.8.1 General Pushback Procedures
Assuming no obstructions, aircraft shall be instructed to pushback immediately.

Aircraft requesting pushback that are not squawking their assigned transponder code shall be instructed to hold position and squawk the correct code; movement of such aircraft is prohibited.

Pushback direction is based primarily on aircraft location.

Aircraft parked at the Cargo Apron and Nothern Apron shall be instructed to push back *facing east* when Runway 25 is in use, and *facing west* when Runway 07 is in use.

Aircraft parked at the southern apron are positioned on straight-out stands and therefore do not require pushback clearance. These aircraft shall request engine start-up clearance first, followed by taxi clearance when ready.

!!! example
      **Controller:** ADY268, Salalah Ground, pushback approved, facing east.

      **Pilot:** Pushback approved, facing east, ADY268.

!!! note
      Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
      **Controler:** ADY268, Salalah ground, behind the Qatari A320 passing left to right, pushback approved, facing east, behind.

      **Pilot:** Behind the Qatari A320 passing left to right, pushback approved, facing east, behind, ADY268.

### 2.8.2 Pushback Types
#### 2.8.2.1 Standard Pushback
This type will normally have the aircraft stop abeam the adjacent stand. The phraseology for this type of pushback is identical to the pushback phraseology as provided in 2.8.1.

#### 2.8.2.2 Short Pushback
A short pushback instruction shall require the aircraft to complete the pushback abeam the current stand such that the adjacent stand will not be blocked.

!!! example
    **Pilot**: "Salalah Ground, OMS106, on stand 15 request pushback."

    **Controller**: "OMS106, Salalah Ground, short pushback approved, face east to finish abeam stand 13R."

    **Pilot**: "Short pushback approved, facing east to finish abeam stand 13R, OMS106."

#### 2.8.2.3 Long Pushback
A long pushback instruction shall require aircraft to complete the pushback operation two stands away from where the pushback was commenced. This manoeuvre may be used when aircraft are vacating a stand to be used by another aircraft that is taxiing in.

!!! example
    **Pilot**: "Salalah Ground, OMS106, on stand 13R request pushback."

    **Controller**: "OMS106, Salalah Ground, long pushback approved, face east to finish abeam stand 10."

    **Pilot**: "Long pushback approved, facing east to finish abeam stand 10, OMS106."

## 2.9 Departure Taxi Procedures
### 2.9.1 General Departure Taxi Procedures
Where aircraft are taxied to runway holding points, transfer of control to AIR should be made early enough such that the aircraft is not required to stop its taxi. 

To deconflict traffic and to reduce the length of taxi clearances, intermediate holding points shall be used wherever possible.

!!! example
      **Controller:** ADY268, taxi via A2 and C, holding point D8, Runway 25.

      **Pilot:** Taxi via A2 and C, holding point D8, Runway 25, ADY268.

### 2.9.2 Runway 07 Departure Taxi Procedures
When departing from Runway 07, aircraft taxiing from the Cargo and Nothern Aprons shall be instructed to taxi westbound to exit their aprons and then taxi via C to holding point D1.

Aircraft on the southern apron shall be instructed to taxi westbound on G to holding point E2.

!!! warning
    Aircraft on the Cargo Apron and Nothern Apron shall exit westbound via taxiways B3 or B5 to allow arriving aircraft to access the apron via B4 or B6.

### 2.9.3 Runway 25 Departure Taxi Procedures
When departing from Runway 25, aircraft taxiing from the Cargo and Nothern Aprons shall be instructed to taxi eastbound to exit their aprons and then taxi via C to holding point D8.

Aircraft on the southern apron shall be instructed to taxi via H8 to holding point E8.

!!! warning
    Aircraft on the Cargo Apron and Nothern Apron shall exit eastbound via taxiways B4 or B6 to allow arriving aircraft to access the apron via B3 or B5.

## 2.10 Arrival Taxi Procedures
### 2.10.1 General Arrival Taxi Procedures
GMC shall assign an arrival stand to aircraft when they are on final approach.

Once the aircraft is handed off to GMC, they shall be taxied to their stand in accordance with the procedures laid down in 2.10.4. 

### 2.10.2 Runway 07 Arrival Taxi Procedures
Aircraft shall vacate Runway 07 onto D6 and are then handed off to GMC.

Aircraft shall be taxied via Taxiway C to the assigned stand. Aircraft destined for the Southern Apron shall be taxied to holding point D8 for runway crossing.

### 2.10.3 Runway 25 Arrival Taxi Procedures
Aircraft shall vacate Runway 25 onto D3 and are then handed off to GMC.

Aircraft shall be taxied via Taxiway C to the assigned stand. Aircraft destined for the Southern Apron shall be taxied to holding point D2 for runway crossing.

### 2.10.4 Stand Allocation Procedure
|                 Area                |        Operator        |
|:-----------------------------------:|:----------------------:|
| Northern Apron (Passenger Terminal) | Commercial Air Traffic |
|             Cargo Apron             |    Cargo Air Traffic   |
|            Southern Apron           |           Any          |
<figure markdown> 
  <figcaption>Table 2-4: Stand allocation procedure</figcaption>
</figure>

### 2.10.5 Stand Restrictions
All stands without an 'L' or 'R' designation are capable of accommodating aircraft up to Code E. Stands with an 'L' or 'R' designation are limited to Code C operations. All stands on the Southern Apron are capable of accommodating aircraft up to Code E.

## 2.11 Designated Areas of Responsibility
### 2.11.1 GMC Positions
GMC is responsible for all aprons and associated taxiways.

### 2.11.2 Handoff Procedure
Where transfer of control is to be made between controllers, aircraft shall not be cleared to a point beyond the current controller’s designated zone of responsibility unless there has been prior coordination with the next controller. Intermediate holding points may be used to satisfy this requirement. 