 To meet the "Rough Terrain" requirement, we selected an off-the-shelf RC crawler chassis. This provided a robust suspension system capable of traversing potholes and mud, which would have been difficult to replicate with a custom-built frame within the 8-week timeline.
around the size of a small suitcase
2. 
 The lifting mechanism utilizes a custom-designed linear actuator powered by a 30 RPM DC motor. To generate sufficient lifting force for the 0.7 kg load, the Manufacturing team designed a custom 3D-printed reducer gear to step down the speed and increase torque.
3. 4 motors, 2 for drive, 1 for the linact, and 1 for the claw open/close
4. The chassis was purchased online, initially we weere planning on making it.
5. Teh power system was... honestly i wasn't working on it so idk
6. Sensors were, camera, argh not naming them all

SPECS:
Following the development of user requirements, a set of technical specifications was created to define measurable performance targets for the Towin’ Turtles Vehicle. These specifications were derived from operator needs, turtle safety requirements, and real-world environmental conditions. Each specification guided design choices for the chassis, gripper mechanism, drivetrain, camera system, and electronics, and established clear verification methods.
The specifications cover vehicle mechanics, gripper/lifting performance, communications and vision, electronics and power, and environmental durability, ensuring the system can safely and reliably operate across various terrains and traffic conditions. Performance targets were chosen based on standard roadway dimensions, expected turtle weights, and practical operational constraints, with testing verifying that most goals were met or exceeded.
Specifications Summary Table
Parameter
Requirement / Goal
Measured Value
Units
Verification
Status
Speed
≥ 0.6
5.81
m/s
Stopwatch
Pass
Climbing Angle
≥ 20
30
°
Tilted Surface
Pass
Tip Over Angle
> 20
25
°
Tilted Surface
Pass
Wheel RPM
≥ 91
104
RPM
Tachometer
Pass
Ground Clearance
≥ 4
8.9
cm
Obstacle Test
Pass
Lift Capacity
≥ 0.7
0.7
kg
Weight Test
Pass
Closing Time
≤ 2
1.4
s
Stopwatch
Pass
Boom Lift Time
≤ 5
4.0
s
Stopwatch
Pass
Transmitter Range
≥ 22
30
m
Range Test
Pass
Video Range
≥ 22
30
m
Range Test
Pass
Light Intensity
TBD
TBD
lumen
Lux Meter
Pending
Average Current Usage
≤ 2.4
2.3
A
Multimeter
Pass
Motor Voltage
≤ 14
12.5
V
Multimeter
Pass
Battery Capacity
> 2000
5600
mAh
Calculated
Pass
Max Current Draw / Claw
< 2
1.5
A
Multimeter
Pass
Average Battery Life
2
TBD
hr
Observation
Pending
Waterproofing / IP Rating
≥ IP42
TBD
N/A
Visual Check
Pending



 
Figure: Detailed spec sheet showing additional information

All specifications and validation testing presented in this report were conducted under controlled indoor conditions using a representative test payload of 0.7 kg. Testing assumed dry surfaces, moderate ambient lighting, and stable wireless connectivity. The system was not evaluated in active traffic, heavy rain, standing water, or extreme temperatures. Operator performance was assumed to meet basic training standards, including visual confirmation of turtle position before engaging the scoop. These assumptions define the operational limits of the current prototype and informed both the validation results and the associated risk analysis.

controversial or debated spec?? 
Hmm I don't remember at the moment but I think we debated speed , thats all ngl. Our spec for speed was too slow i think

Any spec change? I don't remember

3. The FMEA
The top 3 scariest failure modes?
see its not really about scary tho lol
Catch anythnig that woulda been broken? I think... well, like water ingress was pretty scary and we were on track to fixing  that, hmph. I can't remember anything else at the omment. I even made a little risk matrix haha, cute.
Design changes? Err yes there was influence, but its tough to pinpoint ONE, mostly i verbally stated the issues and then adjustments based on that.

Sub team count:
As this project was a collective project, with every student working towards the same goal, Professor Mark assigned the team of 20 students we had into sub-teams, each with a specific theme. The six teams were:
Analysis
Responsible for calculating engineering specifications, creating Free body diagrams, and determining the vehicle’s dynamics and center of mass. 
Business
Charged with defining user requirements, conducting cost analysis, and developing the business model and user agreement.
Documentation
Responsible for recording data, organizing the project meeting notes, and compiling the final technical report
Graphics
Tasked with creating the project logo, visual assets, and public-facing product website
Management
Responsible for the Project Timeline, facilitated communication between subteams, managed risks, delays, and blockers.
Manufacturing
Conducted CAD modeling, 3D printing, subsystem assembly and electronics integration, and the final assembly.


ppl total: 18
weeksyl stand ups: we would go table to table(team-to-team), asking questions and walking around

conflict? Many many times, oh we have stories! Haha
"save" moment? the whiteboard moment obv. Oh, also the fact that I actually propelled the project to testing a prototype, by taking initiative

Work on the final demo? YESSS
NOTHING WENT WRONG really
it was graded individually, but overall, like 90% i'd say
What would we do differently? PLAN THE F*** BETTER lol. Get moving quicker, and please, the teams should move together, not one team going forward and the others catching up


Copied from the report:
Contributions We Can Claim From This Work
Through this project, our team was able to design, build, and test a fully functional prototype that addresses the specific problem of safely transporting a baby turtle across hazardous terrain. Our main contributions include:
Building a working rescue vehicle from a modified RC platform
We took apart a standard RC car and rebuilt it into a more capable system with a redesigned chassis, better stability, and improved ground clearance. This shows that a simple consumer RC vehicle can be turned into a functional engineering solution with the right modifications.


Designing a custom lifting mechanism for small wildlife
We created a servo-powered lift system that can pick up and hold a 0.7 kg load, which meets the requirements for safely lifting a baby turtle. The mechanism proved stable and reliable during repeated tests, demonstrating a practical way to move small animals without human contact.


Integrating a remote camera system for safe, off-site operation
By installing a live-feed camera and pairing it with a drone headset, we made it possible to fully control the vehicle and the lift from a distance. This setup gives the operator a clear, first-person view of both the turtle and the terrain, allowing for precise and safe movement.


Improving terrain performance through engineering changes
The vehicle’s ability to climb slopes, avoid tipping, and move over debris came from our design choices like weight distribution changes, wheel selection, and reinforced mounting points. These adjustments helped the final system exceed most of our performance goals.


Developing a clear, repeatable testing method
We created a structured way to evaluate speed, lift capability, range, and stability using the BTC hallway as a controlled testing environment. This method can be reused or expanded by future teams working on similar rescue or transport robots.


Showing that low-cost rescue robotics is achievable
Our project demonstrates that an affordable, accessible, and functional rescue system can be built using common components. This makes the idea more realistic for wildlife groups that may not have access to expensive robotic equipment.


