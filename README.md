# ES4D 3DP
![screenshot](https://github.com/Monolithcreative/ES4D/blob/main/ES4D-3DP.png)
![screenshot](https://github.com/Monolithcreative/ES4D/blob/main/ES4D_3DPpics2.png)

The ES4D 3DP is a simple yet powerful, scalable, low-cost, open-source 3D printer solution.

This is an advanced project, and a more detailed build guide for this project is being worked on.

### Workshop tools setup:

- PPE (Goggles & Gloves)
- Disk Saw - with suitable metal cutting disk
- Pillar Drill - with drill bit kit
- Digital calliper
- Tapping drills - M3, M5
- Cutting oil
- Vacuum cleaner
- Two large tables
- A standard 200x200x220 size printer
- Computer or laptop
- 4Gb Micro SD card & USB adaptor

**Good to have:**

- CNC Router - able to drill and cut aluminium extrusions.

### 3DP Assembly

1. Bill of materials and printed brackets: 

    Aquire the components listed in the [bill of materials](https://github.com/Monolithcreative/ES4D/blob/main/ES4D_3DP_V1.1_BOM.pdf), prepare the extrusions as shown here, and print the available [brackets](https://github.com/Monolithcreative/ES4D/tree/3DP-Printable-Parts). Some brackets will need holes drilled for mounting screws, see the drawings for more info, these holes are also marked on the print files as circular protrusions for easy drill alignment.

2. Initial assembly: 

    Follow the 3D CAD plans and each assembly to assemble the frame, X gantry, bed and extruder. Ensure the frame and bed is square and level. We can also adjust all of this later if needed.
    
3. Mount the Z axis: 
    
    Attach the Z stepper motors to the frame using the printed brackets. Lower the bed into the middle of the frame, aligning it with the motors.  Connect the lead screws and adapters to the motors by sliding them through the Z axis nuts mounted on the bed. Push the 8mm ID cogs onto the lead screws, and then mount these to the motors with the spring adaptors. Tighten the printed Z axis brackets where needed, ensuring that the bed is aligned whilst able to move freely.
    
4. Mount the X gantry: 
    
    Mount the extruder hotend and cooling assembly to X gantry, and mount the X gantry onto the frame. It is easier to leave the roller wheels loose on the brackets whilst mounting. Tightening them whilst ensuring that the X gantry is alighned with the printer frame; I suggest taping the gantry to the frame to keep it aligned during this process.
    
5. Install the heated bed:
    
    Mount the heated bed to the underside of the bed, connect the contoller and PSU.

6. Wire the electronics: 
    
    Connect the stepper motors, endstops, extruder, hotend, and heated bed to the controller board. Ensure that all connections are secured to the frame. Ensure that there is enough slack for the bed and extruder to move fully in all directions.
    
7. Configure the firmware: 
    
    Load the firmware onto the BTT Octopus controller board. For firmware formatting, this board specifically accepts a no more than 4GB micro SD, formatted as FAT32. 
    
8. Test and calibrate: 
    
    Power on your 3D printer and perform initial tests to ensure all components are functioning correctly. Calibrate the printer by levelling the bed, setting the correct nozzle height. Since this is a large printer, may need to check and adjust the bed level during initial print tests using the turnwheels mounted on the z axis bolts.
    
9. Start printing: 
    
    Once your printer is calibrated, you're ready to start 3D printing! Use slicing software such as Cura, PrusaSlicer, or Simplify3D to prepare your own models for printing, and load the G-code onto your printer via an SD card or USB. For high speed, I have implimented a 1.75mm nozzle in this design. 
    
10. Fine-tuning: 
    
    Experiment with print settings in your slicing software, such as layer height, print speed, and temperature, to achieve the best possible print quality.
    
11. Performing regular maintenance: 
    
    Keep your 3D printer in top condition by regularly cleaning the nozzle and bed, lubricating the linear motion components, and checking the belt tension and alignment.
