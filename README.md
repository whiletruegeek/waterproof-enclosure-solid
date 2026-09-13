# Solid waterproof enclosure experiments

Can a 3D-printed capsule keep electronics dry underwater? This WhileTrueGeek project explores a closed PLA enclosure with rounded ends and no removable lid, tested first in a bucket and then in the ocean.

For the leak tests, I paused printing to insert paper and colour-changing silica gel, then resumed printing to seal them inside. A final comparison capsule was printed without a pause or indicators. Opening these prototypes requires cutting or breaking the shell.

## STL files

| Model | Use |
| --- | --- |
| [Solid capsule.stl](Models/Solid%20capsule.stl) | The model used for the capsule-only prototypes, and the capsule body used in the handle prototypes. |
| [mount.stl](Models/mount.stl) | The separate handle/mount model. For the handle prototypes, I combined the capsule and mount models in **Creality Print** before slicing and printed them together. |
| [solid capsule with mount.stl](Models/solid%20capsule%20with%20mount.stl) | A pre-combined model provided for viewers' convenience. **I did not use this STL in the experiments.** |

Open a model link to preview it on GitHub, then use **Download raw file** to save the STL.

## Main print settings

These are the main settings recorded for the experiments, rather than a complete slicer profile.

| Setting | Value |
| --- | --- |
| Printer | Creality K1C |
| Slicer | Creality Print |
| Filament | PLA — Creality Hyper PLA |
| Nozzle diameter | 0.4 mm |
| Nozzle / bed temperature | 220 °C / 50 °C |
| Orientation | Vertical |
| Model wall thickness | 4 mm, unchanged between the final two capsules |
| Sparse infill | 0% |
| Internal solid infill pattern | Concentric |
| Top / bottom shell settings | 4 mm minimum thickness; 16 layers |
| Top / bottom surface pattern | Concentric |

| Test version | Layer height | Wall loops | Pause to insert indicators |
| --- | --- | --- | --- |
| Earlier prototypes and final indicator capsule | 0.2 mm | 10 | Yes |
| Final capsule without indicators | 0.16 mm | 6 | No |

The final handle-free prints used support threshold angles of 30° for the indicator capsule and 40° for the uninterrupted print.

**0% sparse infill does not mean leaving gaps in the shell.** Check the sliced toolpaths to make sure the capsule walls are filled continuously, especially where the mount meets the body. For a capsule containing indicators, add a pause while the opening is still large enough to insert them, before the top closes.

## What the tests showed

The bucket-test capsule stayed dry. The handle version leaked in the ocean. Both final handle-free capsules appeared dry when opened, although the silica gel changed colour; a separate room-air test showed that humidity could also cause that colour change. These are experimental designs, with more controlled testing needed before trusting electronics inside.
