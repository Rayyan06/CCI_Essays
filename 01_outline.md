Describe your previous technical/research experience or equivalent experience on complex projects, including the level of independence, while working as a member of a technical/research/project team.

VERBS: Describe, working
NOUNS: technical, research, projects, experience, team, member, "level of independence" - how much of the work did i do myself?
ADJECTIVES: previous - past, equivalent (relating), 

LIST OF PROJECTS:
1. Foam Cutting CNC
2. Optical Encoder
3. Mug Warmer
4. Turtle Mover
5. Self-balancing Robot

characteristics:
foam cutting cnc - 3d printed parts, cad skills, motor controller, mechanical design (bearings, linear rods, stepper motors), end switches, forgot a lot of details about this project tho
optical encoder - C++ ISR, LabVIEW VI (producer-consumer) serial reading data visualizer, AVR C coding, State Machine, Photointerrupt, case and mechanical design, very fine disk with minute holes, 3d printed
mug warmer - 3d printed enclosure, thermal calculations in MATLAB, thermostat circuit w/ big SLA battery, 
self-balancing robot - hooking up arduino with IMU, PID control, 2 motors

Qualities:
foam cutting cnc - Design knowledge, 
optical encoder - problem solving, technical competence, curiosity,
mug warmer - math proficiency, teamwork, leadership, analysis
turtle mover - goal setting, planning ahead, teamwork, leadership
self-balancing robot - math proficiency, technical competence, leadership


Outline:

1. Introduction
1.1 Purpose Statement: This essay offers an overview of my technical development on mechatronic projects, providing the reader with an idea of my progression and evolution into complex team-based projects
1.2 Hook: just start here, but do we need it? we just need a short catchy sentence here of some type. Solitary builder hook?
2. Independent Complexity Foam Cutting CNC & Optical Encoder| Goal: show engineeringjudgement
2.1 Project A: The 2-axis foam cutting CNC: 
2.1.1 Antibacklash nut & lead screw, decision to use linear bearings w/ linear steel rod vs. other options
2.1.2 electronics and endswitches
2.2 Project B: The Optical Encoder
2.2.1 Mechanical: Disk slots, snap fit casing, Photointerrupt, PCB
2.2.2 Electrical: C++ ISR, LabVIEW VI, Serial Communication, 
3. Mug Warmer & Turtle Mover: focus on technical handoffs
3.1 Mug Warmer - this taught me that you can apply theory before building
3.1.1 theoretical: thermal calculations for mug warmer, all the analysis documents we did for the  for turtle mover, FMEA, 
3.1.2 PRactical: succeeding and meeting the specs, testing, etc.
4. RPI hackathon
4.1 functioning under pressure!

4. Self-balancing robot and Conclude
4.2: relatively short, just talk about what i'm thinking here 
4.3: Conclude, advancing my skills

WRITING

One of my first hardware projects was a 2-axis foam cutting cnc. There were a lot of decisions to be made in this project. For example, I had to decide guide system to use, I chose Linear Rods over Linear Rails or V-Slot Wheels for .... good balance between cost and structureal rigidity & simplicity. I used antibacklash nut and lead screws(selecting the lead screw?).
Another project was the Optical Encoder. I had to use AVR C ISR and circular buffer to process, read, and send the serial data because standard arduino code was too slow. I even overclocked the AVR microcontroller. On the frontend, I used a Labview Producer-consumer loop to process the serial data starting with the whole "data block" byte packet thingy, "checksum" and all that stuff. This project showed me the complexity of Data Acquisition and Integration.
Then, I transition to team based projects as I enter college. In my engineering design course, I was placed in a team of 4 to design a Mug warmer. Instead of jumping to fabrication, we had to work on the theory first. I conducted the thermal calculations in MATLAB and then we moved on to building it based on what those calculations said. I made the enclosure out of PETG as thick as the calc said. Initially used Ceramic Resistors for heating the aluminum plate, but switched that to nichrome wire (greater contact area) under trial and error. Used a piece of cut ceramic tile for the base (good insulator). Anyhow, we met the spec target of keeping the coffee mug warm to 55 plus minus 1 degree C. The turtle mover project taught me... management! Yeah so it taught me project management on a large team, all the FMEA, TRL Levels, SPECS stuff, Gantt chart, Test reports, all cool stuff ya! Facilitating communication between sub-teams, stand-up meetings, technical documentation  .So we did meet specs in the end! but yeah! 
The RPI hackathon taught me functioning under pressure and adapting quickly, to present and deliver a video game controlled by hand-gestures! The self-balancing robot is... idk, PID stuff, blah blah blah, haven't even started with the PID code here so its tough to talk about maybe a brief mention of this project, thats it. In conclusion, I'm ready to bring these lessons and team blah forward to the next level.

So basically each project taught me an engineering lesson! 

My technical experience is a journey from independent tinkering to teamwork.
One of my first complex hardware projects was a custom 4-axis Foam Cutting CNC. Using a modular 3D printed design, I chose linear rods over rails or V-wheels to balance cost, structure, and simplicity. To minimize mechanical play in the axes, I used anti-backlash nuts with the lead screws, ensuring correct positioning during direction changes. I integrated the electronics into my design, with end switches and motor controller board. This project taught me the difficulty of mechactronic design and design decisions. In a seperate project, I developed an optical encoder for high-frequency position data for science experiment. I implemented firmware in low level AVR-C rather than the Arduino, for the learning and because I used needed better performance, safely overclocking the Atmega chip.  I implemented Interrupt Service Routines, and a circular buffer to process serial data efficiently and not miss a byte. On the frontend, I devolped a LabVIEW because I needed high frequency polling. So instead of polling, I used ISR and circular buffer to send the serial data , overclocking the Microcontroller cuz it was too slow. For the frontend, I used Labview Producer-Consumer Loop to process the serial data, designing a custom byte packet structure with checksums to ensure data integrity. This project taught me the complexity of data acquisition and integration.

As I enter college, I transition to team-based projects. In my engineering design course, I was taught about applying theory before building. In my Mug Warmer Project, I was placed on a team, and I conducted the thermal calculations in MATLAB to determine the stats and insulation type, heating element power usage,insulation thickness, etc. Based on that, I built a prototype using ceramic resistors, but it failed ,so I switched to nichrome wire . The enclosure was PETG. We met the target spec of 55 +- 5 degrees C. 

Later, our class was tasked with building an RC robot that would rescue turtles from road traffic, divided into sub-teams. I was placed on the management team. I tracked the progress of the project around TRL levels to mark milestones. I devoleped the specification document, maintained the Gantt chart, and conducted the Failure Modes and efefcts analysis (FMEA). In addition, I wrote and recorded the test document. I learned the value of rigorous documentation and processes in engineering. 

Finally, the RPI Hackathon tested my ability to deliver under pressure. When my original teammates were unavailable, I partnered with a CS student I met onsite to integrated computer vision libraries into our video game controlled by real-time hand gestures in under 24 hours.
Currently, I'm combining my skills in the IEEE Club's Self-Balancing Robot, where I'm indpendently writing the PID control algorithms to interpret IMU data and drive the motors. 
