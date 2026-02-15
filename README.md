# PHIL-MER-HamSCI-PSWS
The PHL-MER Group's HamSCI RX888WSPRDaemon SDR Personal Space Weather Station

> **Note:** This will be an 'essential' PSWS build. It will not incorporate WSPR transmitter, VLF or Magnetometer modules
---

## HamSCI RX888 WSPRDaemon SDR Station

This repository documents the build of a **Personal Space Weather Station (PSWS)** node. This is a cooperative project involving a subgroup of Delaware Valley Radio Association (DVRA) members in association with **HamSCI**.

> **Note:** While the participants are DVRA members, this project is independent of and not in association with the DVRA.

### Project Overview

The goal of the PSWS project is to create a geographically distributed, multi-instrument system for ground-based space environment measurements. Data from this node is aggregated into a central database for space science research, specifically for analyzing phenomena like **Traveling Ionospheric Disturbances (TIDs)**.

### Hardware Stack

The essential **RX888WSPRDaemon SDR** node is a low-cost, high-precision receiver designed for scientific data collection:

* **SDR:** RX888 Software Defined Radio.
* **SDR Support:** TAPR RX-888 Clock kit and thermal pad.
* **Filter-Preamp:** Turn Island Systems Low pass filter and preamp.
* **Computing:** Off-the-shelf Linux-based system - Ubuntu 24.04 Server LTE.
* **Timing:** Leo Bodnar GPS-Disciplined Oscillator GPSDO + antenna for frequency stability.
* **Target:** Monitoring WWV frequency Doppler shift and WSPR signals.

### Research & Collaboration

Coordinated by the **University of Scranton**, this project supports a global network of "Citizen Science" monitors. Key partners include:

* **TAPR** (Tucson Amateur Packet Radio)
* **NJIT** Center for Solar-Terrestrial Research
* **MIT** Haystack Observatory
* **Case Western Reserve University**

---

