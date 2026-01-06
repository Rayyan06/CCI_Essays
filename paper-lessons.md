1. Kongtawong:

- Improvements to FOFB system at NSLS-II
  Some technical moves to predict and improve performance.
  FOFB has multiple inputs and multiple outputs
  BPM collects beam signal, converst analog to digital, and calculates positions of beam.
  Data from all BPMs moved to cell controllers, where serious math compensates and calculates the corrector strength, math i wanna learn ngl. Transfers data to cntrolers and interfaces, which is fed to the corrector system. 10kHz UPDATe rate - okay, not quite as fast as PIP-II but still fast.

First: Latency was measured, then they made a model crazy math. Model vs. Data was compared.
The BPM latency of 115 microseconds (delay between signal and output), can be reduced by 1 machine clock, and latency for firmware was reduced to <20 microseconds. Slowdown in FOFB calc and extra delay reduced delays! a lot!

2. Hidaka
   they implemented somethnig only utilizing RFBPM's and compatible with FOFB. Simple feedback version, performing bump corrections automatically. Honestly i couldn't underrsntand this.
   But hey: Long term photon drifts mainly occur due to sources unrelated to electron beam orbit (varying heat loads and thermally induced motions) that should be addressed at the BEAMLINE.

3. Ma, 2019
this was RF wizardry. No idea.
4. Fliller:
 Active interlock: protects vacuum chamber from damage due to synchotromn radiation
 measures beam position and angle at all insertion devices and issues beam dump if outside window determined by somethnig.
idk anything else


Aww man the robot project and the coldbox project sound darn interesting but i might have to dump one!


























