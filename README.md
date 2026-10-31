# FPV Drone — Build and Repair

> **Work in progress.** A personal FPV quadcopter project by **Adam Abu Toamy**.

[العربية](README_AR.md) · [Hardware register](docs/HARDWARE.md) · [Repair log](docs/REPAIR_LOG.md)

## Media gallery

Six original photographs supplied by the owner. The files are unchanged; the page only limits their display width.

| Assembly and wiring | Build details |
| --- | --- |
| <img src="docs/media/20260903_023007.jpg" width="360" alt="Original assembly photo"> | <img src="docs/media/20260903_023031.jpg" width="360" alt="Original wiring photo"> |
| <img src="docs/media/20260917_181246.jpg" width="360" alt="Original repair-bench photo"> | <img src="docs/media/20260917_181249.jpg" width="360" alt="Original ESC photo"> |
| <img src="docs/media/20260917_181548.jpg" width="360" alt="Original donor-board photo"> | <img src="docs/media/20260917_190053.jpg" width="360" alt="Original component-work photo"> |

[Original file register](docs/MEDIA_SOURCES.md)

## Project and my work

I assembled and wired a 5-inch FPV drone, configured it with Betaflight, and worked through setup and electronics faults. After an initial flight ended in a hard landing, I investigated motor and ESC damage and reported the drone working again after an ESC repair. This is a historical milestone; the project remains in development.

My contribution covers assembly, wiring, soldering, configuration and fault diagnosis. Betaflight is third-party firmware, not a flight controller algorithm I wrote.

## Parts

| Component | Confirmed information / missing detail |
| --- | --- |
| Frame | Mark4, 5-inch |
| Battery | 4S LiPo; capacity and C rating not confirmed |
| ESC | 60 A; exact model/revision not confirmed |
| Motors | Brushless; current model and KV not confirmed |
| Propellers | 5-inch; exact model/pitch not confirmed |
| Radio link | ExpressLRS receiver and RadioMaster transmitter; exact models not confirmed |
| Flight controller | Used in the build; exact board and firmware target not confirmed |
| FPV system | Present in the recorded build; exact model not confirmed |
| Configuration / training software | Betaflight / Liftoff |

Unconfirmed shopping-list recommendations are not treated as installed components. See [hardware register](docs/HARDWARE.md).

## Difficulties and what happened

| Difficulty encountered | Recorded work / outcome |
| --- | --- |
| Sensor detection and firmware setup | Connection, voltage and firmware/configuration checks; connections were isolated during diagnosis |
| Telemetry loss under throttle while using a smoke stopper | Voltage drop was discussed during troubleshooting; no blanket claim that every power/radio issue is resolved |
| Hard landing and motor damage | A motor rubbed/caught during inspection; motor/ESC fault isolation followed |
| ESC short and failed MOSFET | Multimeter diagnosis; a similar MOSFET was salvaged from a used GTX 1050 Ti and fitted; operation was reported restored |
| Limited flight experience | Practised in Liftoff before returning to real flight |

The MOSFET markings, compatibility measurements and long-term repair endurance were not recovered. The repair account is not a general component-substitution guide.

## Development stages

| Stage | Status |
| --- | --- |
| Mechanical assembly, wiring and soldering | Carried out; original photographs above document the build |
| Betaflight and FPV setup | Worked on during the build; final configuration export is not included |
| Initial flight | Reported; ended in a hard landing |
| Motor / ESC diagnosis and repair | Carried out; operation was reported restored |
| Simulator practice and further tuning | Part of ongoing development |
| Current condition, repeatable flight performance and complete component register | Still to be documented |

## Current limits

No measured flight time, range, payload or certified flight readiness is claimed. This repository documents the work and its remaining gaps; it is not a completed aircraft release.
