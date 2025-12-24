# DIY Inertial Electrostatic Confinement (IEC) Fusion Reactor Build

## Overview

I've been working on building a demonstration-scale Farnsworth-Hirsch fusion reactor (fusor) in my home workshop. This project explores inertial electrostatic confinement—the same principle used in research labs at MIT, Los Alamos, and elsewhere—scaled down to a benchtop setup that can produce visible plasma discharge and demonstrate the fundamentals of IEC physics.

**⚠️ SAFETY WARNING:** This project involves high voltages at potentially lethal currents, vacuum systems that can implode, and may produce UV and x-ray radiation. Do not attempt unless you have experience with high-voltage and vacuum equipment and fully understand the risks involved.

## The Build

### Vacuum System

I'm using a two-stage rotary vane vacuum pump to evacuate the chamber down to approximately 0.025 mmHg. The chamber itself is constructed from:
- Machined aluminum flanges (top and bottom)
- Borosilicate glass cylinder as the main viewport
- Rubber gaskets with high-vacuum grease for sealing
- Ceramic feedthrough for the high-voltage electrode

The first image shows the plasma glow during operation—that eerie purple-blue discharge is ionized gas molecules (primarily N₂⁺, O₂⁺, Ar⁺, and H₂O⁺) accelerating toward the center grid.

### High Voltage System

The power supply chain:
1. **Variac** — Controls AC input voltage
2. **Neon Sign Transformer (NST)** — Steps up to ~10-12kV AC
3. **Homemade oil-filled rectifier** — Converts to DC using high-voltage diodes

The second image shows my workbench setup with the vacuum pump running. You can see the fusor chamber connected via reinforced vinyl tubing, with a vacuum gauge monitoring chamber pressure.

### Inner Grid

The heart of the fusor is a spherical stainless steel wire grid held at high negative potential. I fabricated mine by:
- Winding stainless steel wire around a 1" PVC pipe jig under tension
- Cutting and soldering three interlocking rings into a spherical cage
- Silver soldering a machine screw attachment point

The chamber walls serve as the grounded outer electrode.

## How It Works

When high voltage is applied across the grids under vacuum:
1. Residual gas molecules ionize (lose electrons, become positive)
2. Electric field accelerates ions toward the negative center grid
3. Ions collide at high velocity in the center
4. Missed ions are re-accelerated for another pass

At demonstration power levels, this produces a beautiful plasma glow discharge. Higher-power fusors running deuterium fuel can achieve actual nuclear fusion, producing helium isotopes and detectable neutron radiation.

## Current Status

The system is operational and producing stable plasma. I'm seeing good vacuum integrity (bright blue-purple glow rather than deep purple, which would indicate leaks). Initial arcing on the grid from debris has subsided after a few short runs.

![BD317333-A5E2-4B64-A390-C40F6563F45C_1_105_c](https://github.com/user-attachments/assets/beb6f875-0f4b-4082-928d-030ff584a349)


## Lessons Learned

- **Patience with vacuum seals** — Cleanliness is critical. Latex gloves and alcohol wipes are mandatory when handling gaskets and glass.
- **Step drilling** — Essential for accurate holes in aluminum without wandering.
- **Epoxy outgassing** — Use 24-hour cure epoxy for vacuum applications; fast-cure epoxies outgas and contaminate the chamber.
- **Never overtighten** — The glass cylinder will crack. Finger-tight on the flange nuts is sufficient.


---

*This is a demonstration device for educational purposes. It produces negligible fusion products at current power levels but effectively illustrates IEC principles and provides hands-on experience with plasma physics, high-voltage systems, and vacuum technology.*
