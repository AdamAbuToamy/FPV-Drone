# FPV Drone — Build, Diagnose, Repair

> **Work in progress — active personal project.** Hardware, software and testing are still being developed.

<img src="docs/media/drone-built.jpg" alt="The real assembled FPV drone on the workbench" width="430">

[Watch the bench overview](docs/media/drone-bench-demo.mp4) · [Betaflight orientation check](docs/media/betaflight-orientation-demo.mp4)

A personal 5-inch FPV quadcopter project by **Adam Abu Toamy**, documenting mechanical assembly, electronics integration, Betaflight configuration and hands-on fault diagnosis.

[العربية](README_AR.md) · [Hardware](docs/HARDWARE.md) · [Repair story](docs/REPAIR_LOG.md) · [Evidence and status](docs/EVIDENCE.md)

## The project

I assembled and configured an FPV drone, worked through hardware and firmware problems, and repaired the electronics after a hard landing. This repository records the engineering work behind the build: wiring, soldering, configuration, fault isolation and learning from tests.

**Recorded milestone:** an initial flight and hard landing, followed by motor/ESC troubleshooting and an ESC repair reported working again. That is a historical build milestone, not a claim of current flight readiness or measured performance.

## My contribution

- Mechanical assembly and electronics integration.
- Wiring, soldering and flight-controller configuration with Betaflight.
- Diagnosis of sensor/firmware and radio-link issues during setup.
- Motor and ESC fault isolation after a hard landing.
- Component-level ESC repair and simulator practice in Liftoff.

The flight-controller firmware is third-party software. This repository does not claim authorship of Betaflight or a custom flight-control algorithm.

## Build snapshot

| Part | Recovered information |
| --- | --- |
| Frame | Mark4, 5-inch |
| Battery | 4S LiPo; capacity and C rating not yet recovered |
| ESC | 60 A; exact model/revision to document |
| Flight controller | F722-class in earlier project summaries; exact board identification pending |
| Motors | Brushless; current installed model and KV not yet confirmed |
| Propellers | 5-inch; exact model/pitch pending |
| Radio | ExpressLRS receiver and RadioMaster transmitter; exact models pending |
| FPV system | Earlier project summary names Walksnail digital FPV; exact hardware pending |
| Configuration tool | Betaflight |
| Simulator | Liftoff |

See [hardware evidence](docs/HARDWARE.md) before treating this table as a complete bill of materials.

## A repair worth documenting

A hard landing damaged a motor. Later troubleshooting identified an ESC short and a failed MOSFET. I reported replacing the failed component with a similar MOSFET salvaged from a used GTX 1050 Ti, after which the drone worked again.

This is a record of a specific repair, not a general replacement recommendation. The exact component markings, electrical compatibility and post-repair endurance measurements were not recovered. See the [repair log](docs/REPAIR_LOG.md).

## Media and configuration

Actual assembly and repair photos and two compact bench videos are now bundled. The supplied media shows wiring work, the exposed ESC, the donor graphics card, component rework and the aircraft beside Betaflight. [View the gallery and source register](docs/MEDIA_SOURCES.md). These are real recordings, not a simulated aircraft.

A current Betaflight configuration export, exact wiring diagram and flight footage have not been recovered. There are no invented firmware files, guessed PID settings, flight-time figures or test results in this repository.

## Next documentation milestones

- Add a dated current-status update and any future flight footage.
- Record exact installed components and the wiring as built.
- Archive a reviewed configuration export with the firmware version and target.
- Record dated bench/flight observations and any continuing faults.

## Project status

The historical record covers assembly, setup, an initial flight incident and subsequent repair. Current condition and repeatable flight performance remain to be documented.
