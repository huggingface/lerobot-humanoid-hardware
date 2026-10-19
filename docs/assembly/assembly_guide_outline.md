# Assembly Guide Outline

## Build Sequence
1. Configure all motors before assembly (see `docs/electronics/motor_commissioning.md`).
2. Print all STL parts (`docs/manufacturing/printing_guide.md`).
3. Build torso first.
4. Build upper leg modules in this strict order (same for left and right): `hipx -> hipy (hipz in repo naming) -> thigh`.
5. In parallel, build lower leg modules in this strict order (same for left and right): `foot -> ankle -> knee_mechanism -> shin -> ankle_mechanism`.
6. Assemble upper leg with lower leg for each side.
7. Integrate both legs with torso, then complete wiring checks and first power-on (`docs/electronics/check_wiring.md`, `docs/electronics/first_power_on.md`).

## Build Paradigm
- Default approach: screws are threaded directly into plastic (no insert) for most plastic threads.
- Heat-set insert locations:
  - `shin`: 4 × M3 brass heat-set inserts per shin (`8 total`, recommended `OD 4.2–4.5 mm × L 4–6 mm`) fit the 3.8 mm bores in the 6.0 mm-wide bars of `tibias2_shin_spacer_2.stl` when fastening with M3 screws (alternatively, `M4 x 10` screws can self-tap directly into the 3.8 mm plastic bores).
  - `thigh` (optional reinforcement): 2 × M4 brass heat-set inserts per leg (`4 total`, recommended `OD 5.0 mm × L 4–6 mm`) fit the two 4.0 mm lower clamping holes in `femur_v2_femur_12` if the printed holes are too loose for the two `M4 x 16` screws to self-tap.
- Insert bearings first in each subassembly (press or gentle hammer).
- Place motor goupille/pin during the same phase as bearing insertion.
- For subassembly goupilles: place them during assembly except on `thigh` to keep it demountable.
- Knee and ankle each keep one interface slightly loose, but still movable.
- Some fits are intentionally tight; if needed, gently ream/drill to final diameter with a metal drill bit at low speed.
- Applied reference torque: about `5 Nm` for screws into non-structural plastic.
- For motor threaded holes and structural insert areas, use higher torque appropriate for the thread/material.

## Per-Section Template
- Required printed parts (STL names).
- Required purchased parts from `hardware/bom/bom_buy.csv`.
- Assembly steps with photos and torque notes.
- Quality checks (free rotation, no cable pinch, screw length verification).
