[[WR-217e In-Hub Motor System.pdf]]
## VD
- three operating states
	- traction limit
		- oversizing motors for this results in excess weight
	- torque limit
		- under sizing motors for this results in slower lap times due to underutilization of traction
	- perfectly riding traction limit
		- generally best to design around this
## Torque Vectoring
- a method of distributing power to all four wheels/tires based on current vehicle state
- gives driver more control and quicker response, allowing for later braking and earlier accelerating in corners
	- car can reach steady state max grip capability much quicker
- can also combat flaws in chassis/other hardware setup (e.g. under/oversteer)
## Planetary Gearbox Design
things to account for
- space between motor and caliper
- strength of sun gear given that it has to mount to mount to motor shaft
- calculate and simulate bending and contact stresses on gear teeth ([[Shigley's 10th Edition.pdf#page=748|Shingley's 10th Edition Chapter 14]])
- calculate friction between ring and press fit bearing to ensure it can withstand max torque from motor