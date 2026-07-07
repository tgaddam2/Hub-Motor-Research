[[BYU Intro to Sus and Frame Design.pdf]]
## Track Width
- - distance between center line of the two wheels on a single axle
- generally front track width is larger
	- reduces understeer for *rear wheel drive*
	- reduces difference in turn radius of rear wheels which makes it less likely for diff to lock up
- wider track width reduces weight transfer
- ![[track width.png|338]]
## Wheelbase
- - distance between front and rear axles
## Tire Size and Wheels
- certain tire sizes are generally limited to certain wheel sizes
- some suspension parts are mounted inside the wheel, so the wheel has to big enough to accommodate them
## Geometry
### Vehicle Steering Geometry
#### Scrub Radius
- - distance between the centerline of the wheel and the intersection of the line defined by the ball joints (steering axis) with the ground plane
- positive when the steering axis intersect the ground to the inside of the wheel centerline
- good to minimize, but small positive amount is desired to give driver feedback
- ![[sus geometry 1 - scrub radius.png|216]] ![[sus geometry 2.png|399]]
#### Kingpin Inclination (KPI)
- - angle between the steering axis and wheel centerline as seen from the front of the car
- incorporating KPI can help reduce scrub radius by designing the steering axis to intersect the ground closer to the wheel centerline
- excess KPI can lead to the outside wheel cambering positively and lifting off the ground
	- can be reduced/negated by static camber or positive caster
#### Caster
- - angle of the steering axis as seen from the side of the car
- **positive** if the top of the steering axis is tilted toward the back of the car
- positive caster makes the outer wheel camber negatively in a corner which combats the positive camber that comes from KPI and body roll
- causes the wheels to rise and fall as they rotate about the steering axis, which transfers weight diagonally across the chassis
- provides feedback to driver about cornering forces 
#### Toe
- - angle of wheels when viewed from above
- consequence of scrub radius, kpi, and caster
- toe in - front edges point inward toward vehicle centerline
	- better straight line speed
- toe out - back edges point inward toward vehicle centerline
	- better cornering
### Roll Center
-   - the point the chassis pivots about relative to the ground
- ICs are for the wheels relative to the ground
- front and rear roll center define the *roll axis* that the car pivots around when cornering
- generally the CG is above the roll axis and inertial forces from cornering create a torque about the roll axis that causes the chassis to roll towards the outside of the corner
	- lower chassis roll is ideal as it allows springs and anti-roll bars to be a lower stiffness which gives more tire compliance
- lower chassis roll implies the roll axis would have to be quite high up, which is also undesirable
- in general a roll axis that is too far above or below the ground would result in a "jacking force" during cornering
	- high roll axis - "jacking" force causes suspension to drop relative to the chassis
		- undesirable because it can ’cause positive camber, which results in less tire on the ground
	- low roll axis (below the ground) - suspension goes into bump (raises relative to the chassis) and could bottom out
- thus, roll center/axis at or near ground plane is best, as it reduces vertical chassis movement due to lateral forces
- moves with suspension movement, so it has to be tracked to ensure it doesn't cross the ground plane or else it may cause inconsistent handling
- ![[roll center.png|333]]
### Camber
-  - wheel tilt in and out - relative to vertical
- positive is top of wheel away from car
- negative is top of wheel towards car
	- generally negative camber is desired
- generally adjusted by tilting the steering axis from the vertical which is usually done by adjusting the ball joint locations
- camber compensation for vertical wheel movement is controlled by varying control arm length, which also effect how the camber changes through suspension travel
	- different control arm lengths have different arcs as they move, which effects camber differently
- in turning, positive [[#Caster|caster]] makes outer wheels camber positively and inner wheel camber negatively
- ![[camber.png|310]]
### Steering System
- bump steer - toe change during/due to suspension travel
	- can result in car changing direction without the driver expecting it
- Ackerman steering - when outside wheel turn less than inner wheel
	- reverse/anti-Ackerman steering is just opposite
	- good in theory to match appropriate turning radius of inner and outer wheel, but problematic in practice due to tire slip angles
- 

Wrap Up
- desired
	- small positive scrub radius
	- roll center/axis at or near ground plane
	- negative camber