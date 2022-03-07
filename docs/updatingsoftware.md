# Updating Firmware

## **Introduction** 
???+ info "Before You Begin"
    This page is a guide on how to properly update your TL or LNL printer. This guide is compatible with all TL-D3, H2, D5, and D6 printers. All steps are necessary in-order to complete the process. Please read every section carefully as one missed step can lead to malfunction. Proceed at your own risk.
___

!!! Example "Resources"
    All firmware updates will require Xloader and the CH340 drivers. Please download from the links below.

    [XLoader :octicons-file-16:](https://www.lnl3d.com/FIRMWAREREQUEST){ .md-button .md-button--primary }
    [CH340 Driver :material-hammer-screwdriver:](https://www.lnl3d.com/FIRMWAREREQUEST){ .md-button .md-button--primary }




!!! warning inline-end "Before Proceeding, Power Off Your Printer."
    The motherboard should be updated with 5V power provided by USB.
    
 You will need the following items:

- [x] Windows PC
- [x] Included USB A to USB B Cable
- [x] Firmware suited for your specific unit

!!! notice ""
    If you already have your firmare, you can skip the next section.

___
## **Finding the Right Firmware**

!!! Notice "For BMG Extruders:"
    Firmware above 1.0.29 will autodetect all parameters so there is no need to find a specific file. Just ensure that it matches your printer (IE. D3, H2, D6)

!!! Notice "For Regular Extruders:"
    Firmware version will be between 1.0.0 and 1.0.26 <- being the latest. 

The naming system seperates firmware by three things:

* LCD manufacturer (TJC OR DWN)
* Y Axis Switch Type (Mechanical or Optical)
* Stepper motor driver type (4988 or 2208/2209)

### LCD Type ###

!!! Warning "Troubleshooting"
    If your screen is displaying the "loading..." symbol and not progressing, you most likely have flashed the wrong LCD version.

=== "TJC" 

    !!! Info inline end

        * UI version will begin with 1.2
        * Back of the LCD will have a blue circuit boardhello 


    ![TJC](assets/TJC.png){ align=left, width="400" }



 

=== "DWN"

    !!! info inline end
        * UI version will begin with 1.3
        * Back of the LCD will have a green circuit board  

    ![DWN](assets/DWN.png){ align=left, width="400" }


### Y Axis Sensor Type ###

!!! Warning "Troubleshooting"
    If during homing, your bed moves forward instead of back, you must switch from the Mechanical firmware to Optical.

=== "Optical (-O)" 

    !!! info inline end
        * The switch will be an optical sensor with no moving parts

    ![TJC](assets/optical.png){ align=left, width="400" }



 

=== "Mechanical (-M)"

    !!! info inline end
        * The switch at the back of the bed will have a physical click

    ![Mechanical](assets/mechanical.png){ align=left, width="400" }


### Stepper Driver Type ###

!!! Warning "Troubleshooting"
    If all of your motors are moving in the opposite direction, you are using the wrong stepper driver type and must switch to the opposite.

=== "2209"

    !!! info inline end
        * Comes with a blue heatsink.

    ![2209 Driver](assets/2209.png){ align=left, width="400" }


=== "4988"

    !!! info inline end
        * Usually comes with a silver heatsink. 

    ![4988 Driver](assets/4988.png){ align=left, width="400"}

## Uploading Firmare ##

1. Ensure you have Xloader and the CH340 Driver installed.
2. Plug in the connection between your PC and the printer.

??? notice "Optional Verification"
    To verify that there is communication between your printer and the PC, you can open Device Manager to view your USB connections.

    1. Press the Windows Key.
    2. Type Device Manager.
    


