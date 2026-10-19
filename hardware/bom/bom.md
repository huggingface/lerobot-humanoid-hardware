# BOM Total

## motors

| name | subassembly | qty_subassembly | qty_robot |
|---|---|---:|---:|
| RobStride O0 | torso | 2 | 2 |
| RobStride O2 | hipz | 1 | 2 |
| RobStride O3 | thigh | 2 | 4 |
| RobStride O5 | shin | 2 | 4 |

## torso

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| electronics_controller | Raspberry Pi 5 | single-board computer | 1 | 1 |
| electronics_imu | IMU | BNO055 or BNO085 | 1 | 1 |
| electronics_canfd_adapter | SAVVYCANFD 2CH CANFD adapter | USB, dual CAN FD, 12 Mbps max | 1 | 1 |
| cable_power | Power cable red | diameter >= 2.5 mm, 5 m | 1 | 1 |
| cable_power | Power cable black | diameter >= 2.5 mm, 5 m | 1 | 1 |
| cable_communication | Communication cable color 1 | 5 m | 1 | 1 |
| cable_communication | Communication cable color 2 | 5 m | 1 | 1 |
| motor | RobStride O0 | actuator | 2 | 2 |
| bearing | Bearing | 35x72x17 | 2 | 2 |
| fastener_screw | M2 screw | M2 x 5 cyl head | 4 | 4 |
| fastener_screw | M2.5 screw | M2.5 x 20 cyl head | 9 | 9 |
| fastener_screw | M3 screw | M3 x 8 cyl head | 12 | 12 |
| fastener_screw | M3 screw | M3 x 35 cyl head | 4 | 4 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 16 | 16 |
| fastener_screw | M5 screw | M5 x 10 cyl head | 5 | 5 |

> Comment: cheaper or better CAN-FD adapters may exist, but this one is currently the only adapter proven in this project to handle the RobStride CAN protocol.

### stl_to_print
| name | quantity |
|---|---:|
| [torso_can_holder.stl](../cad/stl/biped_platform/torso/torso_can_holder.stl) | 1 |
| [torso_can_holder_2.stl](../cad/stl/biped_platform/torso/torso_can_holder_2.stl) | 1 |
| [torso_imu_holder.stl](../cad/stl/biped_platform/torso/torso_imu_holder.stl) | 1 |
| [torso_torso13.stl](../cad/stl/biped_platform/torso/torso_torso13.stl) | 1 |
| [torso_torso23.stl](../cad/stl/biped_platform/torso/torso_torso23.stl) | 1 |
| [torso_torso33.stl](../cad/stl/biped_platform/torso/torso_torso33.stl) | 1 |
| [torso_uper_torso_22.stl](../cad/stl/biped_platform/torso/torso_uper_torso_22.stl) | 1 |
| [torso_upper_torso_12.stl](../cad/stl/biped_platform/torso/torso_upper_torso_12.stl) | 1 |

## hipx

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M3 screw | M3 x 8 cyl head | 3 | 6 |
| fastener_screw | M4 screw | M4 x 8 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 12 cyl head | 6 | 12 |
| fastener_screw | M4 screw | M4 x 40 cyl head | 6 | 12 |
| fastener_screw | M4 screw | M4 x 45 cyl head | 9 | 18 |

> Comment: the `hipx` M3 screw line is optional and can be removed without issue.

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [hipx_2_hipxy_sym.stl](../cad/stl/biped_platform/left_leg/hipx/hipx_2_hipxy_sym.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [hipx_2_hipxy.stl](../cad/stl/biped_platform/right_leg/hipx/hipx_2_hipxy.stl) | 1 |

## hipz

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| motor | RobStride O2 | actuator | 1 | 2 |
| bearing | Bearing | 35x72x17 | 2 | 4 |
| fastener_screw | M3 screw | M3 x 10 cyl head | 12 | 24 |
| fastener_screw | M4 screw | M4 x 10 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 8 | 16 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [hip_z_hipz12_sym.stl](../cad/stl/biped_platform/left_leg/hipz/hip_z_hipz12_sym.stl) | 1 |
| [hip_z_hipz22_sym.stl](../cad/stl/biped_platform/left_leg/hipz/hip_z_hipz22_sym.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [hip_z_hipz12.stl](../cad/stl/biped_platform/right_leg/hipz/hip_z_hipz12.stl) | 1 |
| [hip_z_hipz22.stl](../cad/stl/biped_platform/right_leg/hipz/hip_z_hipz22.stl) | 1 |

## thigh

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| motor | RobStride O3 | actuator | 2 | 4 |
| bearing | Bearing | 15x21x4 | 1 | 2 |
| bearing | Bearing | 5x16x5 | 2 | 4 |
| fastener_screw | M2.5 screw | M2.5 x 6 cyl head | 3 | 6 |
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 3 | 6 |
| fastener_screw | M4 screw | M4 x 8 cyl head | 10 | 20 |
| fastener_screw | M4 screw | M4 x 10 cyl head | 12 | 24 |
| fastener_screw | M4 screw | M4 x 16 cyl head | 2 | 4 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 6 | 12 |
| fastener_screw | M4 screw | M4 x 23.5 cyl head | 4 | 8 |
| fastener_screw | M4 screw | M4 x 30 cyl head | 4 | 8 |
| fastener_nut | Nut M4 | M4 nut | 1 | 2 |
| fastener_insert | Heat-set insert M4 | brass threaded insert M4 (OD 5 mm, L 4-6 mm for 4.0 mm lower femur holes) | 2 | 4 |
| fastener_axis | Shoulder screw 07534-05X40 | ISO7379, D1=5, L1=40, B=8, M4, SW=2.5, steel 12.9 | 1 | 2 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [femur_hat_small_1.stl](../cad/stl/biped_platform/left_leg/thigh/femur_hat_small_1.stl) | 1 |
| [femur_v2_femur_12_sym_1.stl](../cad/stl/biped_platform/left_leg/thigh/femur_v2_femur_12_sym_1.stl) | 1 |
| [femur_v2_femur_22_sym_1.stl](../cad/stl/biped_platform/left_leg/thigh/femur_v2_femur_22_sym_1.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [femur_hat_small_1.stl](../cad/stl/biped_platform/right_leg/thigh/femur_hat_small_1.stl) | 1 |
| [femur_v2_femur_12_1.stl](../cad/stl/biped_platform/right_leg/thigh/femur_v2_femur_12_1.stl) | 1 |
| [femur_v2_femur_22_1.stl](../cad/stl/biped_platform/right_leg/thigh/femur_v2_femur_22_1.stl) | 1 |

## knee_mechanism

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| bearing | Bearing | 15x21x4 | 2 | 4 |
| fastener_screw | M3 screw | M3 x 12.5 cyl head | 3 | 6 |
| fastener_screw | M3 screw | M3 x 18 cyl head | 3 | 6 |
| fastener_screw | M4 screw | M4 x 16 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 6 | 12 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [femur_v2_knee_actuation_2.stl](../cad/stl/biped_platform/left_leg/knee_mechanism/femur_v2_knee_actuation_2.stl) | 1 |
| [femur_v2_knee_rod12_sym_1.stl](../cad/stl/biped_platform/left_leg/knee_mechanism/femur_v2_knee_rod12_sym_1.stl) | 1 |
| [femur_v2_knee_rod22_sym_1.stl](../cad/stl/biped_platform/left_leg/knee_mechanism/femur_v2_knee_rod22_sym_1.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [femur_v2_knee_actuation_1.stl](../cad/stl/biped_platform/right_leg/knee_mechanism/femur_v2_knee_actuation_1.stl) | 1 |
| [femur_v2_knee_rod12_1.stl](../cad/stl/biped_platform/right_leg/knee_mechanism/femur_v2_knee_rod12_1.stl) | 1 |
| [femur_v2_knee_rod22_1.stl](../cad/stl/biped_platform/right_leg/knee_mechanism/femur_v2_knee_rod22_1.stl) | 1 |

## shin

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| motor | RobStride O5 | actuator | 2 | 4 |
| bearing | Bearing | 15x21x4 | 4 | 8 |
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 9 | 18 |
| fastener_screw | M3 screw | M3 x 17.5 cyl head | 4 | 8 |
| fastener_screw | M3 screw | M3 x 10 cyl head | 24 | 48 |
| fastener_screw | M3 screw | M3 x 50 cyl head | 1 | 2 |
| fastener_screw | M4 screw | M4 x 18 cyl head | 16 | 32 |
| fastener_screw | M4 screw | M4 x 10 cyl head | 16 | 32 |
| fastener_nut | Nut M3 | M3 nut | 1 | 2 |
| fastener_nut | Nut M4 | M4 nut | 4 | 8 |
| fastener_insert | Heat-set insert M3 | brass threaded insert M3 (OD 4.2-4.5 mm, L 4-6 mm for 3.8 mm shin spacer holes) | 4 | 8 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [femur_v2_hat_femur_2.stl](../cad/stl/biped_platform/left_leg/shin/femur_v2_hat_femur_2.stl) | 1 |
| [spacer12_5_9_4_5.stl](../cad/stl/biped_platform/left_leg/shin/spacer12_5_9_4_5.stl) | 1 |
| [spacer22_5_9_4_5.stl](../cad/stl/biped_platform/left_leg/shin/spacer22_5_9_4_5.stl) | 1 |
| [tibias2_hat_big.stl](../cad/stl/biped_platform/left_leg/shin/tibias2_hat_big.stl) | 1 |
| [tibias2_shin_spacer_2.stl](../cad/stl/biped_platform/left_leg/shin/tibias2_shin_spacer_2.stl) | 1 |
| [tibias2_tibias12_sym_4.stl](../cad/stl/biped_platform/left_leg/shin/tibias2_tibias12_sym_4.stl) | 1 |
| [tibias2_tibias22_sym_4.stl](../cad/stl/biped_platform/left_leg/shin/tibias2_tibias22_sym_4.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [femur_v2_hat_femur_2.stl](../cad/stl/biped_platform/right_leg/shin/femur_v2_hat_femur_2.stl) | 1 |
| [spacer12_5_9_4_5.stl](../cad/stl/biped_platform/right_leg/shin/spacer12_5_9_4_5.stl) | 1 |
| [spacer22_5_9_4_5.stl](../cad/stl/biped_platform/right_leg/shin/spacer22_5_9_4_5.stl) | 1 |
| [tibias2_hat_big.stl](../cad/stl/biped_platform/right_leg/shin/tibias2_hat_big.stl) | 1 |
| [tibias2_shin_spacer_2.stl](../cad/stl/biped_platform/right_leg/shin/tibias2_shin_spacer_2.stl) | 1 |
| [tibias2_tibias12.stl](../cad/stl/biped_platform/right_leg/shin/tibias2_tibias12.stl) | 1 |
| [tibias2_tibias22.stl](../cad/stl/biped_platform/right_leg/shin/tibias2_tibias22.stl) | 1 |

## ankle_mechanism

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M4 screw | M4 x 20 cyl head | 12 | 24 |
| fastener_screw | M5 screw | M5 x 15 cyl head | 4 | 8 |
| fastener_nut | Nut M4 | M4 nut | 4 | 8 |
| joint_spherical | Spherical joint 27628-01-05 | Norelem | 4 | 8 |
| fastener_axis | Shoulder screw 07534-05X20 | ISO7379, D1=5, L1=20, B=8, M4, steel 12.9 | 4 | 8 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [bearing_spacer14_5_7_3.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/bearing_spacer14_5_7_3.stl) | 1 |
| [bearing_spacer24_5_7_3.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/bearing_spacer24_5_7_3.stl) | 1 |
| [bearing_spacer34_5_7_3.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/bearing_spacer34_5_7_3.stl) | 1 |
| [bearing_spacer44_5_7_3.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/bearing_spacer44_5_7_3.stl) | 1 |
| [tibias2_rod_long.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/tibias2_rod_long.stl) | 1 |
| [tibias2_rod_small.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/tibias2_rod_small.stl) | 1 |
| [tibias_actuation_ankle_12.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/tibias_actuation_ankle_12.stl) | 1 |
| [tibias_actuation_ankle_22.stl](../cad/stl/biped_platform/left_leg/ankle_mechanism/tibias_actuation_ankle_22.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [bearing_spacer14_5_7_3.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/bearing_spacer14_5_7_3.stl) | 1 |
| [bearing_spacer24_5_7_3.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/bearing_spacer24_5_7_3.stl) | 1 |
| [bearing_spacer34_5_7_3.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/bearing_spacer34_5_7_3.stl) | 1 |
| [bearing_spacer44_5_7_3.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/bearing_spacer44_5_7_3.stl) | 1 |
| [tibias2_rod_long.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/tibias2_rod_long.stl) | 1 |
| [tibias2_rod_small.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/tibias2_rod_small.stl) | 1 |
| [tibias_actuation_ankle_12.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/tibias_actuation_ankle_12.stl) | 1 |
| [tibias_actuation_ankle_22.stl](../cad/stl/biped_platform/right_leg/ankle_mechanism/tibias_actuation_ankle_22.stl) | 1 |

## ankle

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 6 | 12 |
| fastener_axis | Shoulder screw 07534-05X40 | ISO7379, D1=5, L1=40, B=8, M4, SW=2.5, steel 12.9 | 1 | 2 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [ujoint_hat_small_12.stl](../cad/stl/biped_platform/left_leg/ankle/ujoint_hat_small_12.stl) | 1 |
| [ujoint_hat_small_22.stl](../cad/stl/biped_platform/left_leg/ankle/ujoint_hat_small_22.stl) | 1 |
| [ujoint_spacer_12_ujoint.stl](../cad/stl/biped_platform/left_leg/ankle/ujoint_spacer_12_ujoint.stl) | 1 |
| [ujoint_spacer_22_ujoint.stl](../cad/stl/biped_platform/left_leg/ankle/ujoint_spacer_22_ujoint.stl) | 1 |
| [ujoint_ujoint.stl](../cad/stl/biped_platform/left_leg/ankle/ujoint_ujoint.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [ujoint_hat_small_12.stl](../cad/stl/biped_platform/right_leg/ankle/ujoint_hat_small_12.stl) | 1 |
| [ujoint_hat_small_22.stl](../cad/stl/biped_platform/right_leg/ankle/ujoint_hat_small_22.stl) | 1 |
| [ujoint_spacer_12_ujoint.stl](../cad/stl/biped_platform/right_leg/ankle/ujoint_spacer_12_ujoint.stl) | 1 |
| [ujoint_spacer_22_ujoint.stl](../cad/stl/biped_platform/right_leg/ankle/ujoint_spacer_22_ujoint.stl) | 1 |
| [ujoint_ujoint.stl](../cad/stl/biped_platform/right_leg/ankle/ujoint_ujoint.stl) | 1 |

## foot

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| bearing | Bearing | 5x16x5 | 2 | 4 |
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 3 | 6 |
| fastener_nut | Nut M4 | M4 nut | 3 | 6 |
| joint_spherical | Spherical joint 27628-01-05 | Norelem | 2 | 4 |
| fastener_axis | Shoulder screw 07534-05X20 | ISO7379, D1=5, L1=20, B=8, M4, steel 12.9 | 2 | 4 |

### stl_to_print_left_leg
| name | quantity |
|---|---:|
| [bearing_spacer14_5_7_3.stl](../cad/stl/biped_platform/left_leg/foot/bearing_spacer14_5_7_3.stl) | 1 |
| [bearing_spacer24_5_7_3.stl](../cad/stl/biped_platform/left_leg/foot/bearing_spacer24_5_7_3.stl) | 1 |
| [bearing_spacer34_5_7_3.stl](../cad/stl/biped_platform/left_leg/foot/bearing_spacer34_5_7_3.stl) | 1 |
| [bearing_spacer44_5_7_3.stl](../cad/stl/biped_platform/left_leg/foot/bearing_spacer44_5_7_3.stl) | 1 |
| [foot_foot.stl](../cad/stl/biped_platform/left_leg/foot/foot_foot.stl) | 1 |
| [foot_hat_small.stl](../cad/stl/biped_platform/left_leg/foot/foot_hat_small.stl) | 1 |

### stl_to_print_right_leg
| name | quantity |
|---|---:|
| [bearing_spacer14_5_7_3.stl](../cad/stl/biped_platform/right_leg/foot/bearing_spacer14_5_7_3.stl) | 1 |
| [bearing_spacer24_5_7_3.stl](../cad/stl/biped_platform/right_leg/foot/bearing_spacer24_5_7_3.stl) | 1 |
| [bearing_spacer34_5_7_3.stl](../cad/stl/biped_platform/right_leg/foot/bearing_spacer34_5_7_3.stl) | 1 |
| [bearing_spacer44_5_7_3.stl](../cad/stl/biped_platform/right_leg/foot/bearing_spacer44_5_7_3.stl) | 1 |
| [foot_foot.stl](../cad/stl/biped_platform/right_leg/foot/foot_foot.stl) | 1 |
| [foot_hat_small.stl](../cad/stl/biped_platform/right_leg/foot/foot_hat_small.stl) | 1 |

## assembly_pins

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_pin | Pin d3mm | d3 pin (goupille) | 4 | 8 |
| fastener_pin | Pin d4mm | d4 pin (goupille) | 9 | 18 |

## tools

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| tool | Allen key | 2.5 mm | 1 | 1 |
