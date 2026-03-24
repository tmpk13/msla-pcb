# msla-pcb
Exposing sensitised PCBs with a MSLA printer screen


https://github.com/sn4k3/UVtools


`inkscape sx1262-break-F_Cu.svg --export-dpi=855.22 -o sx1262-break-F_Cu.png`

In UVTools open a slicer file from the msla printer, doesn't matter what the content is.

`Tools` > `PCB Expose`

Add `.grb` file for pcb traces 

Export, This will replace the sacrifical slicer files contents
