# Nuclear Fusor

A benchtop Farnsworth-Hirsch fusion reactor built in my home workshop. Yes, really. No, it's not going to power anything — but it does produce visible plasma discharge and demonstrates the same inertial electrostatic confinement (IEC) principles used in research labs at MIT and Los Alamos, just scaled down to something that fits on a workbench and won't get me on a government list.

> ⚠️ **SAFETY WARNING:** This project involves high voltages at potentially lethal currents, vacuum systems that can implode, and may produce UV and x-ray radiation. Do not attempt unless you have experience with high-voltage and vacuum equipment and fully understand the risks involved. I learned very quickly why safety procedures exist.

## The Build

### Vacuum System

A two-stage rotary vane vacuum pump evacuates the chamber down to approximately 0.025 mmHg. The chamber is constructed from machined aluminum flanges (top and bottom), a borosilicate glass cylinder as the main viewport, rubber gaskets with high-vacuum grease for sealing, and a ceramic feedthrough for the high-voltage electrode. Getting the seals right took more patience than any other part of the build — cleanliness is non-negotiable, and I went through a lot of alcohol wipes to prove it.

The plasma glow during operation — that eerie purple-blue discharge — is ionized gas molecules (primarily N₂⁺, O₂⁺, Ar⁺, and H₂O⁺) accelerating toward the center grid. A bright blue-purple glow means good vacuum integrity. Deep purple means you have a leak, which you then get to spend an evening finding.

### High Voltage System

The power supply chain is a Variac controlling AC input voltage, fed into a neon sign transformer that steps up to ~10–12kV AC, then through a homemade oil-filled rectifier using high-voltage diodes to convert to DC. Building your own rectifier is one of those things that sounds straightforward until you're actually submerging diodes in transformer oil and wondering about your life choices.

### Inner Grid

The heart of the fusor is a spherical stainless steel wire grid held at high negative potential. I fabricated it by winding stainless steel wire around a 1" PVC pipe jig under tension, cutting and soldering three interlocking rings into a spherical cage, and silver soldering a machine screw attachment point. The chamber walls serve as the grounded outer electrode.

## How It Works

When high voltage is applied across the grids under vacuum, residual gas molecules ionize and become positive. The electric field accelerates those ions toward the negative center grid, where they collide at high velocity. Ions that miss are re-accelerated for another pass — the system is essentially a particle accelerator in a jar.

At demonstration power levels, this produces a stable plasma glow discharge. Higher-power fusors running deuterium fuel can achieve actual nuclear fusion, producing helium isotopes and detectable neutron radiation. This one is firmly in the "pretty plasma" category, not the "detectable neutrons" category.

## Lessons Learned

- **Patience with vacuum seals** — latex gloves and alcohol wipes are mandatory when handling gaskets and glass. One fingerprint can ruin your seal.
- **Step drilling** — essential for accurate holes in aluminum without the bit wandering off into places you didn't want it
- **Epoxy outgassing** — use 24-hour cure epoxy for vacuum applications. Fast-cure epoxies outgas and contaminate the chamber, which you discover at the worst possible time.
- **Never overtighten** — the glass cylinder will crack. Finger-tight on the flange nuts is sufficient. I did not learn this from reading the manual.

![BD317333-A5E2-4B64-A390-C40F6563F45C_1_105_c](https://github.com/user-attachments/assets/beb6f875-0f4b-4082-928d-030ff584a349)


## Current Status

The system is operational and producing stable plasma. Vacuum integrity looks good (bright blue-purple glow), and initial arcing on the grid from debris has subsided after a few short runs.

If you're in the Bay Area and want to see it in person, happy to give a demo.

## Credits

- [Farnsworth–Hirsch Fusor](https://en.wikipedia.org/wiki/Fusor)
- [Inertial Electrostatic Confinement](https://en.wikipedia.org/wiki/Inertial_electrostatic_confinement)
- [Fusor.net Community](https://fusor.net/)



*This is a demonstration device for educational purposes. It produces negligible fusion products at current power levels but effectively illustrates IEC principles and provides hands-on experience with plasma physics, high-voltage systems, and vacuum technology.*
