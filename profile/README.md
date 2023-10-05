# SnapperGPS

[https://snappergps.info/](https://snappergps.info/)

The SnapperGPS receiver is a small, low-cost, and low-power GNSS receiver for non-real-time wildlife tracking.
It employs the snapshot GNSS technology, which offloads the computationally expensive data processing to the cloud, and:
* Can operate for more than a year,
* Needs only 12 ms of signal reception for a fix,
* Employs multiple satellite systems for improved reliability (GPS, Galileo, and BeiDou),
* Achieves a median real-world tracking accuracy of about 12 m (before smoothing),
* Measures the temperature in addition,
* Is configured via USB in your browser without the need to install a driver or an app, and
* Is [certified](https://certification.oshwa.org/uk000049.html) open-source hardware.

In this GitHub organisation, you can find:
* Manufacturing files, design files, and instructions to build various versions of the SnapperGPS receiver yourself: [V1.0.0](https://github.com/SnapperGPS/snappergps-pcb), [V2.0.0](https://github.com/SnapperGPS/snappergps-pcb-2), [V2.1.0](https://github.com/SnapperGPS/snappergps-pcb-2-1), [V2.2.0](https://github.com/SnapperGPS/snappergps-pcb-2-2).
* [Housing solutions](https://github.com/SnapperGPS/snappergps-housings) for your SnapperGPS receivers.
* The [frontend](https://github.com/SnapperGPS/snappergps-app) and [backend](https://github.com/SnapperGPS/snappergps-backend) code for the public SnapperGPS [web app](https://snappergps.info/).
* The [firmware](https://github.com/SnapperGPS/snappergps-firmware) that runs on your SnapperGPS receivers.
* A [daughterboard with an accelerometer](https://github.com/SnapperGPS/snappergps-accelerometer-daughterboard).
* Some [Python scripts](https://github.com/SnapperGPS/snappergps-scripts) for your post-processing.
* A [user forum](https://github.com/orgs/SnapperGPS/discussions).

### Acknowledgements

SnapperGPS was developed in the Department of Computer Science
of the University of Oxford and is currently maintained by
[Jonas Beuchert](https://users.ox.ac.uk/~kell5462/) under supervision of
[Alex Rogers](https://www.cs.ox.ac.uk/people/alex.rogers/).

Jonas Beuchert is
funded by the EPSRC Centre for Doctoral Training in
Autonomous Intelligent Machines and Systems
(DFT00350-DF03.01) and works on
SnapperGPS as part of his doctoral studies.
The implementation of SnapperGPS 
was co-funded by EPSRC IAA Technology Funds
(D4D00010-BL14 and D4D00190-BL03.01).
