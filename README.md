# SolidWorks Commercial Aircraft — Full Assembly with Jet Engines & Landing Gear

> MEng Mechanical Engineering · University of Sussex

## Overview

Full SolidWorks assembly of a commercial passenger aircraft, modelled with functional mechanical systems including jet engines and retractable landing gear. The aircraft is fully articulated — landing gear deploys and retracts as a mechanism, and engine assemblies are fully detailed sub-components.

## Highlights

- **Full aircraft assembly** — fuselage, wings, tail surfaces, fairings, and nacelles all modelled as individual parts and assembled
- **Jet engines** — detailed turbofan engine assemblies (fan, nacelle, pylon) mounted under wing
- **Retractable landing gear** — main gear and nose gear modelled as mechanisms with realistic retraction geometry
- **Motion / articulation** — SolidWorks Motion or Mate controller used to animate gear deployment

## Project Structure

```
my-project/
├── README.md
├── src/
│   ├── Aircraft_Assembly.SLDASM      ← top-level assembly
│   ├── Fuselage.SLDPRT
│   ├── Wing_LH.SLDPRT / Wing_RH.SLDPRT
│   ├── Engine_Assembly.SLDASM        ← engine sub-assembly
│   ├── LandingGear_Main.SLDASM       ← gear sub-assembly
│   ├── LandingGear_Nose.SLDASM
│   └── [other parts]
├── results/                          ← renders, screenshots, animation exports (.avi / .mp4)
├── requirements.txt                  ← SolidWorks version
└── docs/                             ← design notes, part tree, assembly instructions
```

## Tools & Methods

- **SolidWorks** — Part modelling, top-down assembly design
- **SolidWorks Motion** — mechanism simulation for landing gear retraction
- **Mates** — concentric, coincident, and angle mates used to define gear kinematics
- **Rendering** — PhotoView 360 / Visualize for presentation renders

## Requirements

- SolidWorks 20[XX] or later (version used: [fill in])
- SolidWorks Motion add-in (for gear animation)

## Notes

Open `Aircraft_Assembly.SLDASM` as the top-level entry point. All sub-assemblies and parts are referenced relative to this file — keep the folder structure intact. Animation files (.avi / .mp4) in results/ demonstrate the landing gear deployment sequence.
