# Mission Notes:
The Mars Phoenix mission had instruments mounted on the top deck that was designed for a previous mission
- Landed in May of 2008 in the north polar region of mars
- Had a robotic arm designed to deliver soil or ice samples to cells in the Thermal Evolved Gas Analyzer (TEGA)
- Each Cell has a Pair of spring loaded protective doors released by a pin puller device
- First command to open doors was issued in Early june
	- Doors only opened partially
- Second set of doors was commanded open in mid june
	- Only opened 25 degrees each
- 
# 1. Define The Failure
## Expected Result
## What Actually Happened
- Instrument doors following the landing failed to open
- Problem was attributed to the instrument contractors inadequate documentation of the anomaly and failure ot adequately communicate a redlined design change to the subcontractor
- The anomaly represents a violation of TLYF principle

# 2. Research of Failure
## Sources
- https://www.planetary.org/articles/1521
- https://www.jpl.nasa.gov/news/nasas-phoenix-mars-lander-puts-soil-in-chemistry-lab-team-discusses-next-steps/
## Notes
- First door opening happend on SOL 8
- Second door opening happened on sol 25
- Mission Engineers determined out of the 8 doors 6 of them would have the same fault

# 3. Define the Cause
## First Level Cause
- Probably proximate cause of the anomaly to a mechanical interference
- Stiffeners impeding the opening of the 6 inboard cell doors due to a raised profile
- Failure was re-verified on an EQM.
	- Instrument contractor modified the EQM lower rail to avoid interference
	- Change drawings was provided to the subcontractor but the rail modifications was not annotated or dimensioned for change
	- Subcontractor drawings only incorporated the changes that had dimensions called out or annotated
	- Contractors development process does not generate any other documentation
	- Failed to provide full, post-assembly testing of the flight doors in a flight assembly
## Second Level Cause

# 4. Root Cause Analysis
## Tool 1: The Five Whys

**Problem**  
TEGA doors did not fully open.

**Why?**  
Mechanical interference blocked the doors.

**Why did Blocking interference exist?**  
Flight hardware retained the original bracket design.

**Why wasn't the corrected design incorporated?**  
The design change was never fully documented or communicated.

**Why wasn't it documented?**  
The contractor relied on informal redlined drawings instead of formal engineering change documentation.

**Root Cause**

Weak configuration management and inadequate engineering change control.
## Tool 2: Fishbone Diagram
![[FishBone Diagram.png]]
# 5. Relate to
Mission: 
