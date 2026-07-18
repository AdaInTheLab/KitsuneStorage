# KitsuneStorage

Bigger storage everywhere, for 7 Days to Die V2.x.

| Container | Vanilla | KitsuneStorage |
|---|---|---|
| Wood writable crate | 48 | 100 (10x10) |
| Iron writable crate | 64 | 120 (10x12) |
| Steel writable crate | 80 | 144 (12x12) |
| Bicycle | 10 | 40 |
| Minibike | 30 | 80 |
| Motorcycle | 40 | 90 |
| 4x4 Truck | 90 | 120 |
| Gyrocopter | 50 | 90 |
| Robotic Drone | 16 | 48 |

Also enlarges the loot window slot pool so the biggest containers display correctly.

Pure XML modlet (XPath patches only), no DLLs.

## Install

Drop the `KitsuneStorage` folder into your `Mods` folder. Needed on **both server and client**: container sizes are pushed by the server, but the loot window layout is client-side UI.

## Notes

- Growing containers is safe on existing saves. Shrinking (removing the mod) can orphan items in slots beyond the smaller size.
- If you run RW SimpleUI with Gears, leave its "Drone Storage Size" setting on Vanilla or it will override the drone size here.
- Part of the Kitsune QoL family: [KitsuneMoreSloots](https://github.com/AdaInTheLab/KitsuneMoreSloots), [KitsuneBackpack](https://github.com/AdaInTheLab/KitsuneBackpack).
