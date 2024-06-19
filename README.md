# Fanstel BC805M Based nRF52805 Development Board

## Software Requirements
KiCad 8.0

jsreynaud's KiCad Via Stitching Plugin (https://github.com/jsreynaud/kicad-action-scripts)

## Purpose and Background

Currently, the only widely available BC805M evaluation board is Fanstel's EV-BC805M, but this comes at a cost of $60. I have a couple of ideas for personal projects where I'd like to use the BC805M, but I couldn't stomach paying $60 for the evaluation board when I knew I could design one in a more convenient shape and size that would cost much less. 

## Physical Size

This evaluation board is designed to be the same dimensions as Adafruit's Feather platform, but without the rounded corners or the screw holes. The physical size is where the similarities end though, as the through-hole header pin placement and order does not match that of Adafruit's standards. It simply was not practical to try to make it pin-compatible for this design.

## Board Design

As previously mentioned, Adafruit's Feather dimensions were used as a convenient size for this board. Below you will find screenshots of the PCB Layout for both the Top, Bottom, and Top Silkscreen Layers, a 3D View of the Top and Bottom of the Board (Coming Soon), and images of the Top and Bottom of the physical PCB and PCBA (Coming Soon).

![PCB_Top](/img/revA_PCB_Top.PNG)
PCB Top Layer

![PCB_Bottom](/img/revA_PCB_Bottom.PNG)
PCB Bottom Layer

![PCB_Top_Silkscreenm](/img/revA_PCB_Top_Silkscreen.PNG)
PCB Top Silkscreen Layer

## Design References

This design is heavily based on Fanstel's EV-BC805M reference design, but with a few exceptions. The main differences stem from the lack of switches that connect/disconnect parts of the circuit for current measuring. Unfortunately, Fanstel's documentation for the BC805M module doesn't contain much information related to layout guidelines/suggestions, so I applied general PCB layout best practices. 

## Designer

Matthew T. Toplack - 2024