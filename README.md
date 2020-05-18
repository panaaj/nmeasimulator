# NMEASimulator

## NMEA data stream generator.

#### _Available for: Windows, Mac, Linux and Raspberry Pi_.

NMEASimulator is an NMEA data stream generator to mimic vessel movement, engine status, water depth, etc.

It can work in two modes:

__1. Set initial seed values and then perodically apply a delta to them to mimic vessel movemen t.__
- Individual values can be manually overridden _(supports using keyboard arrows Up-Down alters speed and L-R alters heading)_.
- Steering mode allows altering course by setting the rudder angle _(supports using L-R keyboard arrows)_.

__2. Follow a GPX Track.__
- NMEASimulator will walk through each point of the Track at the interval set in the configuration screen.
- If a track has multiple segments, NMEASimulator will concatenate all the segments into one contiguous Track*


_**NMEASimulator is a replacement for the NMEASimulator Chrome App** (Support for Chrome Apps end as of June 2020 for Windows, Mac & Linux)_

![image](https://user-images.githubusercontent.com/38519157/75314330-55c95380-58af-11ea-887c-392dcccbea3a.png)


Installation:
-------------

NMEASimulator is now available in _General Release_ for Windows, Mac, Linux and Raspberry Pi _(armv7l)_.

Head to [Releases](https://github.com/panaaj/nmeasimulator/releases) to download the latest version for
your device Operating System.

