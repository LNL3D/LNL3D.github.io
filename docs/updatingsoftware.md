# Updating Firmware

## **Introduction** 
???+ info "Before You Begin"
    This page is a guide on how to properly update your TL or LNL printer. All steps are necessary in-order to complete the process. Please read every section carefully as one missed step can lead to malfunction. Proceed at your own risk.
___

!!! Example "Resources"
    All firmware updates will require Xloader and the CH340 drivers. Please download from the links below.

    [XLoader :octicons-file-16:](https://www.google.com){ .md-button }
    [CH340 Driver :material-hammer-screwdriver:](https://www.google.com){ .md-button }




!!! warning inline-end "Before Proceeding, Power Off Your Printer."
    
 You will need the following items:

- [x] Windows PC
- [x] Included USB A to USB B Cable
- [x] Firmware suited for your specific unit

!!! notice ""
    If you already have your firmare, you can skip the next section.

___
## **Finding the Right Firmware**

!!! Notice "For Regular Extruders:"
    Firmware version will be between 1.0.0 and 1.0.26 <- being the latest. 

The naming system seperates firmware by three things:

* LCD manufacturer (TJC OR DWN)
* Y Axis Switch Type (Mechanical or Optical)
* Stepper motor driver type (4988 or 2208/2209)

### LCD Type ###

=== "TJC" 
    ![TJC](assets/TJC.png){ align=left, width="300" }
    ___
    * UI version will begin with 1.2
    * Back of the LCD will have a blue circuit board


 

=== "DWN"
    
    ![DWN](assets/DWN.png){ align=left, width="300" }
    ___
    * UI version will begin with 1.3
    * Back of the LCD will have a green circuit board

### Y Axis Sensor Type ###

=== "Optical (-O)" 
    ![TJC](assets/TJC.png){ align=left, width="300" }
    ___
    * The switch will be an optical sensor with no moving parts


 

=== "Mechanical (-M)"
    
    ![Mechanical](assets/mechanical.png){ align=left, width="300" }
    ___
    * The switch at the back of the bed will have a physical click

### Stepper Driver Type ###
