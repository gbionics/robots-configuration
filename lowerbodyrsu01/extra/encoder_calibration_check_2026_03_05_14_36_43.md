# Encoder Calibration Check Report

| | |
|:--|:--|
| **Date** | 2026-03-05 14:36:45 |
| **Reference TOML** | `joint_calibration_2026_03_04_18_54_35.toml` |
| **Slaves checked** | 12 |

---

## Summary

| Slave | Name | Enc1 Adj &Delta; (deg) | Enc2 Adj &Delta; (deg) |
|:-----:|:-----|----------------------:|-----------------------:|
| 1 | SOMANET | -5.009766 | -0.515671 |
| 2 | SOMANET | +9.533730 | +0.354309 |
| 3 | SOMANET | +4.596405 | +0.474472 |
| 4 | SOMANET | -0.540390 | -0.010643 |
| 5 | SOMANET | +0.257492 | +0.041199 |
| 6 | SOMANET | -0.564766 | -0.064201 |
| 7 | SOMANET | -0.064545 | -0.014420 |
| 8 | SOMANET | -0.283585 | -0.015793 |
| 9 | SOMANET | -0.017166 | -0.083771 |
| 10 | SOMANET | -1.052971 | -0.083084 |
| 11 | SOMANET | -3.819809 | -0.407524 |
| 12 | SOMANET | +1.154251 | -0.109520 |

---

### Slave 1 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 370670 | 377956 | +7286 |
| Raw position (deg) | 254.518890 | 259.521790 | +5.002899 |
| Adjusted position (counts) | 153624 | 146328 | -7296 |
| Adjusted position (deg) | 105.485229 | 100.475464 | -5.009766 |
| Counts per revolution | 524288 | 524288 | 0 |
| Raw-to-degrees factor | 0.000687 | 0.000687 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 754130 | 755630 | +1500 |
| Raw position (deg) | 258.909988 | 259.424973 | +0.514984 |
| Adjusted position (counts) | 294448 | 292946 | -1502 |
| Adjusted position (deg) | 101.090698 | 100.575027 | -0.515671 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 2 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 583539 | 555768 | -27771 |
| Raw position (deg) | 200.342216 | 190.807800 | -9.534416 |
| Adjusted position (counts) | 465040 | 492809 | +27769 |
| Adjusted position (deg) | 159.658813 | 169.192543 | +9.533730 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 612204 | 611171 | -1033 |
| Raw position (deg) | 210.183563 | 209.828911 | -0.354652 |
| Adjusted position (counts) | 436374 | 437406 | +1032 |
| Adjusted position (deg) | 149.817123 | 150.171432 | +0.354309 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 3 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 150806 | 137417 | -13389 |
| Raw position (deg) | 51.775131 | 47.178383 | -4.596748 |
| Adjusted position (counts) | 897771 | 911159 | +13388 |
| Adjusted position (deg) | 308.225212 | 312.821617 | +4.596405 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 166322 | 164930 | -1392 |
| Raw position (deg) | 57.102127 | 56.624222 | -0.477905 |
| Adjusted position (counts) | 882260 | 883642 | +1382 |
| Adjusted position (deg) | 302.899933 | 303.374405 | +0.474472 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 4 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 907436 | 909012 | +1576 |
| Raw position (deg) | 311.543427 | 312.084503 | +0.541077 |
| Adjusted position (counts) | 141143 | 139569 | -1574 |
| Adjusted position (deg) | 48.457603 | 47.917213 | -0.540390 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 718281 | 718311 | +30 |
| Raw position (deg) | 246.602211 | 246.612511 | +0.010300 |
| Adjusted position (counts) | 330297 | 330266 | -31 |
| Adjusted position (deg) | 113.398476 | 113.387833 | -0.010643 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 5 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 770003 | 769253 | -750 |
| Raw position (deg) | 264.359550 | 264.102058 | -0.257492 |
| Adjusted position (counts) | 278575 | 279325 | +750 |
| Adjusted position (deg) | 95.641136 | 95.898628 | +0.257492 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 107854 | 107731 | -123 |
| Raw position (deg) | 37.028732 | 36.986504 | -0.042229 |
| Adjusted position (counts) | 940732 | 940852 | +120 |
| Adjusted position (deg) | 322.974701 | 323.015900 | +0.041199 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 6 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 525374 | 527017 | +1643 |
| Raw position (deg) | 180.372849 | 180.936928 | +0.564079 |
| Adjusted position (counts) | 523208 | 521563 | -1645 |
| Adjusted position (deg) | 179.629211 | 179.064445 | -0.564766 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 392558 | 392734 | +176 |
| Raw position (deg) | 134.774094 | 134.834518 | +0.060425 |
| Adjusted position (counts) | 656026 | 655839 | -187 |
| Adjusted position (deg) | 225.228653 | 225.164452 | -0.064201 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 7 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 781990 | 782174 | +184 |
| Raw position (deg) | 268.474960 | 268.538132 | +0.063171 |
| Adjusted position (counts) | 266586 | 266398 | -188 |
| Adjusted position (deg) | 91.525040 | 91.460495 | -0.064545 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 628737 | 628776 | +39 |
| Raw position (deg) | 215.859718 | 215.873108 | +0.013390 |
| Adjusted position (counts) | 419843 | 419801 | -42 |
| Adjusted position (deg) | 144.141655 | 144.127235 | -0.014420 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 8 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 775822 | 776647 | +825 |
| Raw position (deg) | 266.357346 | 266.640587 | +0.283241 |
| Adjusted position (counts) | 272758 | 271932 | -826 |
| Adjusted position (deg) | 93.644028 | 93.360443 | -0.283585 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 197902 | 197954 | +52 |
| Raw position (deg) | 67.944260 | 67.962112 | +0.017853 |
| Adjusted position (counts) | 850678 | 850632 | -46 |
| Adjusted position (deg) | 292.057114 | 292.041321 | -0.015793 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 9 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 331251 | 331307 | +56 |
| Raw position (deg) | 113.726006 | 113.745232 | +0.019226 |
| Adjusted position (counts) | 717322 | 717272 | -50 |
| Adjusted position (deg) | 246.272964 | 246.255798 | -0.017166 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 636334 | 636579 | +245 |
| Raw position (deg) | 218.467941 | 218.552055 | +0.084114 |
| Adjusted position (counts) | 412239 | 411995 | -244 |
| Adjusted position (deg) | 141.531029 | 141.447258 | -0.083771 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 10 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 274031 | 277103 | +3072 |
| Raw position (deg) | 94.081078 | 95.135765 | +1.054688 |
| Adjusted position (counts) | 774540 | 771473 | -3067 |
| Adjusted position (deg) | 265.917206 | 264.864235 | -1.052971 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 396127 | 396369 | +242 |
| Raw position (deg) | 135.999413 | 136.082497 | +0.083084 |
| Adjusted position (counts) | 652453 | 652211 | -242 |
| Adjusted position (deg) | 224.001961 | 223.918877 | -0.083084 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 11 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 152476 | 163598 | +11122 |
| Raw position (deg) | 52.348480 | 56.166916 | +3.818436 |
| Adjusted position (counts) | 896099 | 884973 | -11126 |
| Adjusted position (deg) | 307.651176 | 303.831367 | -3.819809 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 138135 | 139302 | +1167 |
| Raw position (deg) | 47.424889 | 47.825546 | +0.400658 |
| Adjusted position (counts) | 910455 | 909268 | -1187 |
| Adjusted position (deg) | 312.579918 | 312.172394 | -0.407524 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

### Slave 12 — SOMANET

#### Encoder 1 (0x2111)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 38606 | 36928 | -1678 |
| Raw position (deg) | 26.508636 | 25.356445 | -1.152191 |
| Adjusted position (counts) | 485682 | 487363 | +1681 |
| Adjusted position (deg) | 333.491364 | 334.645615 | +1.154251 |
| Counts per revolution | 524288 | 524288 | 0 |
| Raw-to-degrees factor | 0.000687 | 0.000687 | 0.000000 |

#### Encoder 2 (0x2113)

| Metric | Reference (TOML) | Current (Live) | Delta |
|:-------|-----------------:|---------------:|------:|
| Raw position (counts) | 767810 | 768133 | +323 |
| Raw position (deg) | 263.606644 | 263.717537 | +0.110893 |
| Adjusted position (counts) | 280769 | 280450 | -319 |
| Adjusted position (deg) | 96.394386 | 96.284866 | -0.109520 |
| Counts per revolution | 1048576 | 1048576 | 0 |
| Raw-to-degrees factor | 0.000343 | 0.000343 | 0.000000 |

---

*Report generated by `yarp-cia402-check-encoder-calibration`*
