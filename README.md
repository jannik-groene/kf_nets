# Network for the kf Chess Engine


| Net | Training Data | Architecture    | Elo Gain |
| :-- | :------------ | :-------------- | -------: |
| c4d34f1e | kf-0.0.9.binpack | `(768->32)x2->1` | 300 |
| 8990dfc9 | kf-0.0.9.binpack, kf-0.1.0-c4d34f1e.binpack | `(768->64)x2->1` | 200 |
| 35ad6f7f | kf-0.0.9.binpack, kf-0.1.0-c4d34f1e.binpack, kf-0.1.0-8990dfc9_dedup.binpack | `(768->64)x2->1` | 70 |
| 0cf4cf94 | kf-0.0.9.binpack, kf-0.1.0-c4d34f1e.binpack, kf-0.1.0-8990dfc9_dedup.binpack, kf-0.1.0-35ad6f7f.binpack | `(768->128)x2->1` | 40 |
| **f3f2fd88** | kf-0.0.9.binpack, kf-0.1.0-c4d34f1e.binpack, kf-0.1.0-8990dfc9_dedup.binpack, kf-0.1.0-35ad6f7f.binpack, kf-0.1.7-0cf4cf94.binpack, kf-0.1.7-0cf4cf94_pt2.binpack | `(768->128)x2->1x4` | 37 |
