# SEU OBDH-Lab
*OBDH laboratory for the "Embedded and Ubiquitous Systems" subject at UPM*

This repository contains the required software (source code and models)
to carry out the *Cross-Development Environment Work* assignments
from the *Embedded and Ubiquitous Systems* subject of the
UPM's *Máster Universitario en Ingeniería Informática (MUII)* program.

The assignments are based on a simplified version of the
On-Board Data Handling System (OBDH) from the UPMSat-2 microsatellite.
OBDH systems are basically in charge of the communication with the ground station,
as well as the data acquisition and control of the satellite.
These functionalities require interaction with the embedded devices,
thus, an OBDH is said to be a real-time embedded system.

The main objectives of the assignments are to get the students acquainted
with the activities for cross-development of an embedded system.

## Install
This repository contains submodules. To clone it, you must use the `--recursive` git option:

```
git clone --recursive https://github.com/STR-UPM/SEU-OBDH-Lab.git
```

## Project Structure
This repository is decomposed in the following top-level directories:
- [`doc`](./doc): Contains the laboratory manual, slides, and related documentation.
- [`lab-1`](./lab-1): Contains the source code for the Hello program from the 1st assignment, "Set up".
- [`lab-2`](./lab-2): Contains the source code for the Led demo from the 1st assignment, "Set up".
- [`lab-3`](./lab-3): Contains the source code for the 2nd assignment, "OBDH".
- [`lab-4`](./lab-4): Contains the source code and Simulink models for the 3rd assignment, "OBDH with ACS".
