# Printing Guide

Generic recommendation:
- Printer baseline: `Bambu Lab H2D`
- Material baseline: `PLA+` for all robot printed parts
- Infill: `30%`
- Wall count: `4`
- Layer height: `0.15 mm`
- Infill pattern: `gyroid`
- Nozzle: `0.2 mm`

Anti-delamination and orientation rule:
- For structural parts, orient prints so layer lines do not take the main tensile load.
- If orientation is ambiguous, check Onshape assembly orientation first, then compare with mounted reference photos in `docs/assembly/photos/`.
- Orientation reference photos to inspect line direction and final part pose:
  - `docs/assembly/photos/thigh_detail.jpg`
  - `docs/assembly/photos/knee_detail.jpg`
  - `docs/assembly/photos/knee_mechanism_view_1.jpg`
  - `docs/assembly/photos/knee_mechanism_view_2.jpg`
  - `docs/assembly/photos/knee_mechanism_view_3.jpg`

H2D reference project files (critical parts):
- `docs/manufacturing/h2d_profiles/shin_tibias_example.3mf` + `docs/manufacturing/h2d_profiles/shin_tibias_print_example.png`
- `docs/manufacturing/h2d_profiles/thigh_femur_example.3mf` + `docs/manufacturing/h2d_profiles/thigh_print_example.png`
- `docs/manufacturing/h2d_profiles/hip_example.3mf` + `docs/manufacturing/h2d_profiles/hip_print_example.png`
- Other parts are more straightforward and usually do not require dedicated `.3mf` guidance.
- See `docs/manufacturing/h2d_profiles/README.md` for quick mapping.

Intentional documentation scope:
- Detailed slicing/orientation help is provided only for critical structural parts (`shin`, `thigh`, `hip`).
- For other parts, there is usually one obvious safe orientation; if not, verify with Onshape and mounted assembly photos.


## torso

| stl | quantity |
|---|---:|
| torso/torso_can_holder.stl | 1 |
| torso/torso_can_holder_2.stl | 1 |
| torso/torso_imu_holder.stl | 1 |
| torso/torso_torso13.stl | 1 |
| torso/torso_torso23.stl | 1 |
| torso/torso_torso33.stl | 1 |
| torso/torso_uper_torso_22.stl | 1 |
| torso/torso_upper_torso_12.stl | 1 |


## hipz

| stl | quantity |
|---|---:|
| left_leg/hipz/hip_z_hipz12_sym.stl | 1 |
| left_leg/hipz/hip_z_hipz22_sym.stl | 1 |
| right_leg/hipz/hip_z_hipz12.stl | 1 |
| right_leg/hipz/hip_z_hipz22.stl | 1 |

Special recommendation: use `100%` infill for this subassembly.
Reference project:
- `docs/manufacturing/h2d_profiles/hip_example.3mf`
- `docs/manufacturing/h2d_profiles/hip_print_example.png`

## hipx

| stl | quantity |
|---|---:|
| left_leg/hipx/hipx_2_hipxy_sym.stl | 1 |
| right_leg/hipx/hipx_2_hipxy.stl | 1 |


Special recommendation: use `100%` infill for this subassembly.

## thigh

| stl | quantity |
|---|---:|
| left_leg/thigh/femur_v2_femur_12_sym_1.stl | 1 |
| left_leg/thigh/femur_v2_femur_22_sym_1.stl | 1 |
| left_leg/thigh/femur_hat_small_1.stl | 1 |
| right_leg/thigh/femur_v2_femur_12_1.stl | 1 |
| right_leg/thigh/femur_v2_femur_22_1.stl | 1 |
| right_leg/thigh/femur_hat_small_1.stl | 1 |

Special recommendation: for the large thigh part, print it on its side (not on its front face).
Reference project:
- `docs/manufacturing/h2d_profiles/thigh_femur_example.3mf`
- `docs/manufacturing/h2d_profiles/thigh_print_example.png`

## knee_mechanism

| stl | quantity |
|---|---:|
| left_leg/knee_mechanism/femur_v2_knee_actuation_2.stl | 1 |
| left_leg/knee_mechanism/femur_v2_knee_rod12_sym_1.stl | 1 |
| left_leg/knee_mechanism/femur_v2_knee_rod22_sym_1.stl | 1 |
| right_leg/knee_mechanism/femur_v2_knee_actuation_1.stl | 1 |
| right_leg/knee_mechanism/femur_v2_knee_rod12_1.stl | 1 |
| right_leg/knee_mechanism/femur_v2_knee_rod22_1.stl | 1 |

## shin

| stl | quantity |
|---|---:|
| left_leg/shin/femur_v2_hat_femur_2.stl | 1 |
| left_leg/shin/spacer12_5_9_4_5.stl | 1 |
| left_leg/shin/spacer22_5_9_4_5.stl | 1 |
| left_leg/shin/tibias2_hat_big.stl | 1 |
| left_leg/shin/tibias2_shin_spacer_2.stl | 1 |
| left_leg/shin/tibias2_tibias12_sym_4.stl | 1 |
| left_leg/shin/tibias2_tibias22_sym_4.stl | 1 |
| right_leg/shin/femur_v2_hat_femur_2.stl | 1 |
| right_leg/shin/spacer12_5_9_4_5.stl | 1 |
| right_leg/shin/spacer22_5_9_4_5.stl | 1 |
| right_leg/shin/tibias2_hat_big.stl | 1 |
| right_leg/shin/tibias2_shin_spacer_2.stl | 1 |
| right_leg/shin/tibias2_tibias12.stl | 1 |
| right_leg/shin/tibias2_tibias22.stl | 1 |

Reference project:
- `docs/manufacturing/h2d_profiles/shin_tibias_example.3mf`
- `docs/manufacturing/h2d_profiles/shin_tibias_print_example.png`

## ankle_mechanism

| stl | quantity |
|---|---:|
| left_leg/ankle_mechanism/bearing_spacer14_5_7_3.stl | 1 |
| left_leg/ankle_mechanism/bearing_spacer24_5_7_3.stl | 1 |
| left_leg/ankle_mechanism/bearing_spacer34_5_7_3.stl | 1 |
| left_leg/ankle_mechanism/bearing_spacer44_5_7_3.stl | 1 |
| left_leg/ankle_mechanism/tibias2_rod_long.stl | 1 |
| left_leg/ankle_mechanism/tibias2_rod_small.stl | 1 |
| left_leg/ankle_mechanism/tibias_actuation_ankle_12.stl | 1 |
| left_leg/ankle_mechanism/tibias_actuation_ankle_22.stl | 1 |
| right_leg/ankle_mechanism/bearing_spacer14_5_7_3.stl | 1 |
| right_leg/ankle_mechanism/bearing_spacer24_5_7_3.stl | 1 |
| right_leg/ankle_mechanism/bearing_spacer34_5_7_3.stl | 1 |
| right_leg/ankle_mechanism/bearing_spacer44_5_7_3.stl | 1 |
| right_leg/ankle_mechanism/tibias2_rod_long.stl | 1 |
| right_leg/ankle_mechanism/tibias2_rod_small.stl | 1 |
| right_leg/ankle_mechanism/tibias_actuation_ankle_12.stl | 1 |
| right_leg/ankle_mechanism/tibias_actuation_ankle_22.stl | 1 |

## ankle

| stl | quantity |
|---|---:|
| left_leg/ankle/ujoint_hat_small_12.stl | 1 |
| left_leg/ankle/ujoint_hat_small_22.stl | 1 |
| left_leg/ankle/ujoint_spacer_12_ujoint.stl | 1 |
| left_leg/ankle/ujoint_spacer_22_ujoint.stl | 1 |
| left_leg/ankle/ujoint_ujoint.stl | 1 |
| right_leg/ankle/ujoint_hat_small_12.stl | 1 |
| right_leg/ankle/ujoint_hat_small_22.stl | 1 |
| right_leg/ankle/ujoint_spacer_12_ujoint.stl | 1 |
| right_leg/ankle/ujoint_spacer_22_ujoint.stl | 1 |
| right_leg/ankle/ujoint_ujoint.stl | 1 |

## foot

| stl | quantity |
|---|---:|
| left_leg/foot/bearing_spacer14_5_7_3.stl | 1 |
| left_leg/foot/bearing_spacer24_5_7_3.stl | 1 |
| left_leg/foot/bearing_spacer34_5_7_3.stl | 1 |
| left_leg/foot/bearing_spacer44_5_7_3.stl | 1 |
| left_leg/foot/foot_foot.stl | 1 |
| left_leg/foot/foot_hat_small.stl | 1 |
| right_leg/foot/bearing_spacer14_5_7_3.stl | 1 |
| right_leg/foot/bearing_spacer24_5_7_3.stl | 1 |
| right_leg/foot/bearing_spacer34_5_7_3.stl | 1 |
| right_leg/foot/bearing_spacer44_5_7_3.stl | 1 |
| right_leg/foot/foot_foot.stl | 1 |
| right_leg/foot/foot_hat_small.stl | 1 |
