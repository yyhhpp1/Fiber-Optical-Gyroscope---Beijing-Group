# Fiber Optical Gyroscope (FOG) - Beijing Group
Our project is a fiber optical gyroscope. The goal of this project was to demonstrate the Sagnac effect.

### Table of Contents


- [List of Components](#1-list-of-components)
- [Design](#2-design)
- [Building Process](#3-building-process)
- [Code](#4-code)
- [Finished Product](#5-finished-project)
- [Contributors](#6-contributors)
  * [1.1 Purpose](#11-purpose)
  * [1.2 Scope](#12-scope)
  * [1.3 Acronyms](#13-acronyms)
  * [1.4 References](#14-references)
    + [1.4.1 Internal References](#141-internal-references)
    + [1.4.2 External References](#142-external-references)
  * [1.5 Overview](#15-overview)

# List of Components

- A turntable [two choices]:
  * Lazy susan (~¥100)
    + most of the lazy susans can not rotate very fast.
  * We made one with small turntable and cardboard.
- Manual 3-Paddle Fiber Polarization Controller [1310nm] (~¥400)
- 1310nm 5mW FP SM Laser Diode (~¥100)
- 75um 2.5GHZ Analog InGaAS PIN Photodiode 
- 
- Labjack HV

Note:
All of the components are bought in Beijing, China, so their prices are typically cheaper than in the United States. Here is an example purchase link that include most of the components for people in the US: https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=343.

The

# Design


# Building Process
### Tips:
  - Selecting fibers and adapters
    * Fibers should be all single mode or all multimode. Single mode fibers are typically cheaper, so it is better to use them in labs.
    * All of the components should be in the same light range (e.g. 1310nm).
    * All of the components should have the same type of connectors (e.g. FC/APC).
  - Stablization
    * Since a small change in the geometry of the fibers will result in a big difference in interference patterns, we need to make sure that the whole system is stable.
      + Battery - use a buck converter to stablize the power
      + Fibers - use iron wires and tapes to ensure that when we rotate the whole structure, the geometry of cables do not change
