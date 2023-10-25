# ** What is Vulcan firmware? **

Vulcan firmware is LNL3D's special edition firmware based on Marlin 2. We've added custom features that should make 3D printing a joy on any of our platforms. 

** Supported units: **

- [x] Vulcan D3
- [x] TL-D3 Pro
- [x] TL-D5 Pro
- [x] TL-D6 Pro

!!! Example "Requirements"

    - DWIN Display (In printer settings -> about, your UI version number should begin with a 1.3)
    - 8 Bit Tenlog Mainboard

## Features 
*These are notable features compared to the stock Tenlog firmware:*

- Marlin 2 
- Mesh bed leveling (Manual and auto)
- Ability to recognize folders on SD cards
- Individual Extruder E-steps 
- AC bed support
- Linear advance
- Input shaping
- Built in PID tuning
- 3rd party filament runout sensor compatibility

*If you wish to report any bugs, email us at support@lnl3d.com* 

___

## ** Mesh Leveling **

Our Vulcan firmware provides two types of leveling, manual and automatic mesh leveling. Unless you have the hardware to support automatic leveling (IE. BL-touch, Euclid), manual mode is the way to achieve a great printing surface. 

!!! warning "Before You Begin"
    - [x] Verify the firmware you have (Manual or Automatic leveling), as the instructions on how to operate your machine will differ.
    - [x] Tram your bed to ensure your print surface is as flat as it can be prior to applying a mesh. 

___

### ** Automatic Bed-Leveling **

![type:video](https://www.youtube.com/embed/1AeiYWxSwpE)

Automatic Mesh Bed Leveling is a feature that utilizes a probe located near the toolhead to sample points on the bed to create a virtual mesh. This virtual mesh is overlayed onto your g-code to compensate for low and high spots in your first layer. Read more about mesh leveling <a href="https://all3dp.com/2/mesh-bed-leveling-all-you-need-to-know/" target="_blank">here</a>.


** Setting Up Mesh ** 

!!! Abstract "Info"
    *If you have purchased a unit from LNL3D with BL-Touch or a probe preinstalled, your offset settings will be calibrated.*
    
    *If you are purchasing a kit or performing a 3rd party installation, please refer to the "setting offset" section to determine your offset.* 

=== "Step 1."

    !!! info inline end
        1. Begin by navigating to the "leveling menu". 
            * The unit should home when entering the leveling menu.

    ![2209 Driver](assets/2209.png){ align=left, width="400" }


=== "Step 2."

    !!! info inline end
        * Usually comes with a silver heatsink. 

    ![4988 Driver](~/assets/4988.png){ align=left, width="400"}

=== "Step 3."

    !!! info inline end
        * Usually comes with a silver heatsink. 

    ![4988 Driver](~/assets/4988.png){ align=left, width="400"}

___

### ** Manual Mesh Leveling **

___

## ** Recognizing Folders **

___ 

## ** Individual E-steps **

___ 

## ** Built-In PID **

___ 

## ** Linear Advance/Input Shaping **