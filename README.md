# beepis-case

Beepis case in FreeCAD (actual source files, not STL)

## v1.0 - battery attachment now complete!

A 3D printed case designed to fit a Beepis/Beepy board.

### Top-level parts in the FreeCAD file:

   - `microUSB plug`: cover for the microUSB plug needed to make contact with Pi Zero's microUSB data port.
   - `Lid +wider GPIO cut`: top part
   - `Back shell +cell sep`: bottom part

Designed for 0.4mm printer nozzle width. In our experience, is best printed at 0.1mm layer height. No supports expected, though the microUSB cover and M3 nuts might be a little tricky in that regard; expect to have to clean up these two spots a little after printing.

### Battery support:

    - two 103395 batteries in parallel, with plenty of room for cell padding
    - alternate batteries possible if you mod the case to your liking - can be as simple as tearing out the battery separator, since it's designed to be thin and easy to remove.

### Modification capabilities:

A 46x104mm 4-screw rectangle pattern, expects four M2.5 screw. Currently available parts:

     - A waist clip. See `beepis_waist_1` for v1. More upgrades and accessories for it incoming!
     - A holder base with holes for two countersunk screws. Incompatible with the waist clip, **deprecated**; see `beepis_holder_base` for v0.

### Required parts:

    - 10x10cm 1mm thick foam sheet
    - 10x10cm 2mm thick foam sheet
    - Thin double-sided tape for attaching the foam sheets
    - M3 nuts, metal, 4pcs
    - M3x25 screws, countersunk (conical head), metal, 4pcs
