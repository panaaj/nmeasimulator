# NMEASimulator

## NMEA data stream generator plugin.

NMEASimulator is an NMEA data stream generator to mimic vessel movement, engine status, water depth, etc.

It can work in two modes:

1. Set initial seed values and then perodically apply a delta to them to mimic vessel movement

1. Follow a GPX Track. NMEASimulator will walk through each point of the Track at the interval set in the configuration screen.

*Note: If a track has multiple segments, NMEASimulator will concatenate all the segments into one contiguous Track*


**_NMEASimulator is a replacement for the NMEASimulator Chrome App which are no longer supported beyond June 2020 for Windows, Mac & Linux_**

![image](https://user-images.githubusercontent.com/38519157/75314330-55c95380-58af-11ea-887c-392dcccbea3a.png)


Installation:
-------------

NMEASimulator is available as both a Windows and Linux application.

Head to [Releases](./releases) to download the relevant version.


