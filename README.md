# msla-pcb
Exposing sensitised PCBs with a MSLA printer screen


https://github.com/sn4k3/UVtools

# MSLA

In UVTools open a slicer file from the msla printer, doesn't matter what the content is.

`Tools` > `PCB Expose`

Add `.grb` gerber file for pcb traces 

Export, This will replace the sacrifical slicer files contents

# PCB

1. Remove one side of the flim from the Photosensitive dry film.
2. Place on pcb and laminate, iron, or hot air it on
3. Run the MSLA printer with the file from uvtools
4. Remove the other side of the film
5. Add Sodium Carbonate (Not recommended NaOH 4g/1L water) in water
6. Add PCB with exposed film
7. Stir up the water (1 min NaOH)
8. Gently scrub with brush (Toothbrush)
9. (Optional) Expose to UV light to harden film of the traces
10. Add to etching solution
11. Once bare pcb is visable remove with grabbers
12. Use acetone (Bath is good) to remove the photoresist traces that are left 
