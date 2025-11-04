# grblHAL_Fusion360_Post_Processor
Experimental grblHAL post processor with canned cycles and 4th axis support for use with Autodesk Fusion 360

Added features and modifications:

12.08.2025

Added the ability to enable/disable arc generation in outputted code to prevent the following error in IOsender when using Gcode Rotate. This option is heavily affected by (Built-in) Tolerance value

<img width="539" height="220" alt="image" src="https://github.com/user-attachments/assets/df7246e3-9822-4d4c-b5c3-72af9e2280f6" />

<img width="632" height="684" alt="image" src="https://github.com/user-attachments/assets/2056372d-bb84-4958-ba4f-4994440c6e3b" />

18.02.25
1. Improved return position behaviour and code generation
2. Added initial positioning move option
   
![image](https://github.com/Dietz0r/grblHAL_Fusion360_Post_Processor/blob/main/PPOptions.png)

30.09.24
1. Added sanitycheck for Air while Misting
2. Improved SpindleDelay code

25.09.2024
1. Added optional after job return position
2. enabled all circular planes by default

12.01.2024
Added initial retract to clearance height for SafePosition:Clearance height method.

23.06.2023
1. Added option to change Airblast behaviour while mistcooling
2. Added Flood&Mist Cooling Support

01.06.2023
1. Added toolchange message support
2. Updated grblHAL repositroy reference link

11.09.2022 
Fork of Mainbranch (last update 14.05.21) created
1. Cleaned up user PP properties
2. Added coolant mapping to Userproperties


![image](https://github.com/Dietz0r/grblHAL_Fusion360_Post_Processor/blob/main/PPOptions2.png)
