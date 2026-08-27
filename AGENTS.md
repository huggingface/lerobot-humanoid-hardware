# AGENT.md

## Remote Reference

- Remote repository: <https://github.com/Virgileboat/lerobot-humanoid-hardware>
- Default branch: <https://github.com/Virgileboat/lerobot-humanoid-hardware/tree/main>
- Current tracked upstream branch: `origin/main`

## Full Project Context

This repository is the hardware/build block in the LeRobot humanoid stack:

1. `lerobot-humanoid-design`: co-design assumptions and feasibility
2. `lerobot-humanoid-hardware`: physical build source of truth (this repo)
3. `lerobot-humanoid-model`: software model assets derived from hardware/design
4. `lerobot-humanoid-runtime`: deployment and control on real/sim robot
5. `lerobot-humanoid-identification`: replay-based parameter identification

Hardware choices here constrain all downstream model/runtime/identification behavior.

## Mission Of This Repo

Provide reproducible build assets for the biped platform:

- assembly documentation
- BOM files
- STL exports and printing guidance
- electronics wiring and commissioning procedures

## Scope

- In scope: biped platform hardware
- Out of scope (current repo iteration): upper-body hardware

## Mandatory Build Sequence

Always recommend this order:

1. Order buy parts from `hardware/bom/bom_buy.csv`.
2. Print parts from `docs/manufacturing/printing_guide.md`.
3. Commission/check motors before mechanical assembly:
   - `docs/electronics/motor_commissioning.md`
   - `python hardware/config/commission_motor.py wizard --channel can0`
4. Assemble with `docs/assembly/assembly_guide.md`.
5. Run wiring and first power-on checks:
   - `docs/electronics/check_wiring.md`
   - `docs/electronics/first_power_on.md`

Non-negotiable: do not start full mechanical assembly before motor commissioning and motion checks.

## Source Priority When Answering

1. `docs/assembly/assembly_guide.md`
2. `hardware/bom/bom.csv` and `hardware/bom/bom_buy.csv`
3. `docs/manufacturing/printing_guide.md`
4. `docs/electronics/*.md`
5. `docs/assembly/photos/*`
6. Onshape link in `README.md`

## Answer Rules

- Do not invent quantities, part references, or wiring pins.
- Distinguish `qty_subassembly` vs `qty_robot`.
- For print guidance, include exact STL paths and quantities.
- For orientation questions, reference Onshape and relevant assembly photos.
- If docs conflict, call it out explicitly and identify which file should be updated.

## Escalation

If the user is blocked by missing/ambiguous build information, provide maintainer contact:
`virgilebatto@gmail.com`.
