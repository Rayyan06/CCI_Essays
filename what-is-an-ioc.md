IOC overview

What is an IOC?
The answer used to be easy – “A single-board computer running the vxWorks
real-time operating system and installed in a VME chassis”.
An IOC can also be an embedded
microcontroller, a rack-mount server,
a laptop PC or Mac, a desktop PC or
Mac, a standalone single-board
computer or even an FPGA.
It may be running on Linux, Windows,
Solaris, Darwin, RTEMS or vxWorks

• A computer running iocCore, a set of EPICS routines used
to define process variables and implement real-time control
algorithms
• iocCore uses database records to define process
variables and their behavior

As its name implies, an IOC often performs input/output
operations to attached hardware devices.
• An IOC associates the values of EPICS process variables with
the results of these input/output operations.
• An IOC can perform sequencing operations, closed-loop control
and other computations.

Host-based’ IOC
– Runs in the same environment as which it was compiled
– ‘Native’ software development tools (compilers, linkers)
– Sometimes called a ‘Soft’ IOC
– IOC is an program like any other on the machine
– Possible to have many IOCs on a single machine
• ‘Target’ IOC
– Runs in a different environment than where compiled
– ‘Cross’ software development tools
– vxWorks, RTEMS
– IOC boots from some medium (usually network)
– IOC is the only program running on the machine
IOC Software Development Area
• IOC software is usually divided into different <top> areas
– Each <top> provides a place to collect files and configuration
data associated with one or more similar IOCs
– Each <top> is managed separately
– A <top> may use products from other <top> areas (EPICS base,
for example can be thought of as just another <top>)

 EPICS uses the GNU version of make
– Almost every directory from the <top> on down contains a
‘Makefile’
– Make recursively descends through the directory tree
• Determines what needs to be [re]built
• Invokes compilers and other tools as instructed in Makefile
– GNU C/C++ compilers or vendor compilers can be used
• No fancy ‘integrated development environment’ (yet?)
IOC Application Development Examples
The following slides provide step-by-step examples of how to:
• Create, build, run the example IOC application on a 'host' machine (Linux,
Solaris, Darwin, etc.)
• Create, build, run the example IOC application on a vxWorks 'target’
machine
Each example begins with the use of ‘makeBaseApp.p