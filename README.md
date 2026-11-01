# FPV Drone — Build and Repair

> **Work in progress.** A personal FPV quadcopter project by **Adam Abu Toamy**.

[العربية](README_AR.md) · [Hardware register](docs/HARDWARE.md) · [Repair log](docs/REPAIR_LOG.md)

## Media gallery

**Gallery: 6 original photos and 3 selected recordings.** Audio tracks have been removed. Each complete recording is provided as one compressed H.264 file without splitting, with all frames retained.

### Photos

| Assembly and wiring | Build details |
| --- | --- |
| <img src="docs/media/20260903_023007.jpg" width="360" alt="Original assembly photo"> | <img src="docs/media/20260903_023031.jpg" width="360" alt="Original wiring photo"> |
| <img src="docs/media/20260917_181246.jpg" width="360" alt="Original repair-bench photo"> | <img src="docs/media/20260917_181249.jpg" width="360" alt="Original ESC photo"> |
| <img src="docs/media/20260917_181548.jpg" width="360" alt="Original donor-board photo"> | <img src="docs/media/20260917_190053.jpg" width="360" alt="Original component-work photo"> |

### Videos — no audio

#### 01 · 20260903_074309.mp4

https://github.com/user-attachments/assets/ecb07d8c-bf21-468a-a1ed-116fed333df2

#### 02 · 20260905_015915.mp4

https://github.com/user-attachments/assets/4fea01d5-7573-4ffe-8d09-32b068560a1e

#### 03 · 20260906_021615.mp4

https://github.com/user-attachments/assets/f38df564-b9a4-4d5c-a8b0-b781beecd3ea

[Media inventory](docs/MEDIA_SOURCES.md)

## Project and my work

I assembled and wired a 5-inch FPV drone, configured it with Betaflight, and worked through setup and electronics faults. After an initial flight ended in a hard landing, I investigated motor and ESC damage and reported the drone working again after an ESC repair. This is a historical milestone; the project remains in development.

My contribution covers assembly, wiring, soldering, configuration and fault diagnosis. Betaflight is third-party firmware, not a flight controller algorithm I wrote.

## Parts

The component list is being updated one part at a time from owner-provided details.

| Component | Specification |
| --- | --- |
| Flight controller | F7 F722 |
| ESC | 60 A 4-in-1 BLHeli_S; 30.5 × 30.5 mm stack mounting |
| Motors | 4 × RS2205 2300KV; two CW/CCW pairs |
| GPS | HGLRC M100-5883 M10; compass, ceramic antenna and LED; 21 × 21 mm |
| Digital FPV system | CADDX Walksnail Ascent Lite VTX Kit; supplied product-title specifications: 1080p/60fps, 35 ms latency, 3 km range; for Ascent FPV goggles |
| FPV goggles | CADDXFPV Walksnail Ascent Goggles; 5.8G, 1920 × 1080 screen resolution at 60 Hz; for the Ascent Lite VTX Kit |
| Radio transmitter | RadioMaster Pocket ELRS; Hall gimbals, foldable antenna and built-in LED light |
| Radio receiver | BETAFPV NANO 2400 RX ExpressLRS, 2.4 GHz; T-type antenna and Wi-Fi upgrade support |
| Battery | 4S LiPo; 14.8 V nominal voltage, 1800 mAh capacity, 45C discharge rating; XT60 connector |

The advertised specifications above come from the owner-supplied product title and are not measurements of this build.

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
