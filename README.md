# NMEASimulator

## NMEA / Signal K data stream generator.

#### _Available for: Windows, Mac, Linux and Raspberry Pi_.

NMEASimulator is an NMEA / Signal K data stream generator to mimic vessel movement, engine status, water depth, etc.

As well as generating both NMEA0183 and Signal K data streams it also sends `ViewSync`UDP packets which can be used by Google Earth(tm) and LiquidGalaxy installations.

It can work in three modes:

__1. Set initial seed values and then perodically apply a delta to them to mimic vessel movement.__
- Individual values can be manually overridden _(supports using keyboard arrows Up-Down alters speed and L-R alters heading)_.
- Steering mode allows altering course by setting the rudder angle _(supports using L-R keyboard arrows)_.

__2. Follow a GPX / KML Track.__
- NMEASimulator will walk through each point of the Track at the interval set in the configuration screen.
- If a track has multiple segments, NMEASimulator will concatenate all the segments into one contiguous Track*

__3. Replay a recorded log.__
- NMEASimulator can log the generated NMEA / Signal K output to a log file.
- These log files can be replayed allowing the recorded data to be re-sent.

_**NMEASimulator is a replacement for both the NMEASimulator and SignalKSimulator Chrome Apps** (Support for Chrome Apps end as of June 2021 for Windows, Mac & Linux)_

![image](https://user-images.githubusercontent.com/38519157/75314330-55c95380-58af-11ea-887c-392dcccbea3a.png)


Installation:
-------------

NMEASimulator is now available in _General Release_ for Windows, Mac, Linux and Raspberry Pi _(armv7l)_.

Head to [Releases](https://github.com/panaaj/nmeasimulator/releases) to download the latest version for
your device Operating System.

