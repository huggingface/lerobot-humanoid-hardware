# BOM To Buy

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

## hipx

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M3 screw | M3 x 8 cyl head | 3 | 6 |
| fastener_screw | M4 screw | M4 x 8 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 12 cyl head | 6 | 12 |
| fastener_screw | M4 screw | M4 x 40 cyl head | 6 | 12 |
| fastener_screw | M4 screw | M4 x 45 cyl head | 9 | 18 |

> Comment: the `hipx` M3 screw line is optional and can be removed without issue.

## hipz

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| motor | RobStride O2 | actuator | 1 | 2 |
| bearing | Bearing | 35x72x17 | 2 | 4 |
| fastener_screw | M3 screw | M3 x 10 cyl head | 12 | 24 |
| fastener_screw | M4 screw | M4 x 10 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 8 | 16 |

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

## knee_mechanism

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| bearing | Bearing | 15x21x4 | 2 | 4 |
| fastener_screw | M3 screw | M3 x 12.5 cyl head | 3 | 6 |
| fastener_screw | M3 screw | M3 x 18 cyl head | 3 | 6 |
| fastener_screw | M4 screw | M4 x 16 cyl head | 8 | 16 |
| fastener_screw | M4 screw | M4 x 20 cyl head | 6 | 12 |

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

## ankle_mechanism

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M4 screw | M4 x 20 cyl head | 12 | 24 |
| fastener_screw | M5 screw | M5 x 15 cyl head | 4 | 8 |
| fastener_nut | Nut M4 | M4 nut | 4 | 8 |
| joint_spherical | Spherical joint 27628-01-05 | Norelem | 4 | 8 |
| fastener_axis | Shoulder screw 07534-05X20 | ISO7379, D1=5, L1=20, B=8, M4, steel 12.9 | 4 | 8 |

## ankle

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 6 | 12 |
| fastener_axis | Shoulder screw 07534-05X40 | ISO7379, D1=5, L1=40, B=8, M4, SW=2.5, steel 12.9 | 1 | 2 |

## foot

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| bearing | Bearing | 5x16x5 | 2 | 4 |
| fastener_screw | M2.5 screw | M2.5 x 8 cyl head | 3 | 6 |
| fastener_nut | Nut M4 | M4 nut | 3 | 6 |
| joint_spherical | Spherical joint 27628-01-05 | Norelem | 2 | 4 |
| fastener_axis | Shoulder screw 07534-05X20 | ISO7379, D1=5, L1=20, B=8, M4, steel 12.9 | 2 | 4 |

## assembly_pins

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| fastener_pin | Pin d3mm | d3 pin (goupille) | 4 | 8 |
| fastener_pin | Pin d4mm | d4 pin (goupille) | 9 | 18 |

## tools

| category | name | specification | qty_subassembly | qty_robot |
|---|---|---|---:|---:|
| tool | Allen key | 2.5 mm | 1 | 1 |
