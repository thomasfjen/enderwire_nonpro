# enderwire_nonpro

This is a collection of parts to fit the Gizzle Y-Axis for the Standard Ender with 2040 Y Extrusion on the DarkDog Rev2 Ender_SW.

Based on Gizzles Y-Axis https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Gizzle/ender-3_(pro)_switchwire

And DarkDogs Rev2 https://github.com/boubounokefalos/Ender_SW/tree/Rev.2

There are mounts for the original PSU, the thick non-meanwell one.
It is advisable to not use a lower panel then (or create a cutout), as the psu fan is very close to the panel.


Overview of changes:

- Y-axis extrusion moved forward with replacing the M5 bolts with shorter ones and using t-nuts in the extrusion.
  35mm bolts are bit too long depending on how the extrusions are machined, so use some washers under the bolt head till the bolts 
  does not hit the bottom of the extrusion.
- Modified Skirt to hold PSU, added Parts when using original PSU.
- Modified Rear Grill to have some room (a few Millimeters) for belt tightening.
- Located Pi to the front (there less room because of the vertical stepper).
- Connected front idler mount to grill.
- There is no belt tensioner, use the rear motor mount to tension the belt (same procedure as Switchwire)

Use these STL-Files for the Y-Axis: 
https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Gizzle/ender-3_(pro)_switchwire/STL/Y-ASSEMBLY 

Rest of STL-Files, basically everything except the Y-Axis Folder (Gantry -> Y-Axis Folder) and my files (see table down below)
https://github.com/boubounokefalos/Ender_SW/tree/main/STLS

You can print the drilling guide from this for drilling the bed carriage:
https://www.thingiverse.com/thing:3530419/files

Or use the files of the drill-less carriage adapter, you may have to use shorter bed springs/silicone spacers tho, as the bed is raised about 8mm and can interfere with the lower z rail stops, there are smaller z_endstop files in the folder to reduce the problem as best as possible.



You may want to use the optimized motor mounts: https://github.com/strayr/SWE3-motor-mounts
They add a third screw to the frame to avoid tilting of the assembly.


Watch the Table down below to replace files to make these two repos compatible.


| Part                                       | Original              | Replace with:                                   | Comment:                                                   |
|--------------------------------------------|-----------------------|-------------------------------------------------|------------------------------------------------------------|
| Parts form Y-Axis Gizzle Repo                          |                       |                                                 |                                                            |
| Y-Axis Front Idler                         | Y-Idler-Bottom        | y_idler_lower_part and front_y_grill_connection | Adds a connection to the Front Grill                       |
| Belt Anchor                                | Y-Belt_Anchor_x1      | belt_anchor_m5                             | Uses the original screws and nuts from the wheels to secure the anchor the bed carriage               |
| Parts from DarkDogs (boubounokefalos) Rev2 |                       |                                                 |                                                            |
| Grill                                      | rear_grill_middle     | rear_grill_middle_nonpro                        |                                                            |
| Extension/Side Skirt                       | rear_extention_left_a | rear_extention_left_a_psu                       | Also replaces the PS_4040_Slide_Mount as mount for the psu |
| Deck Upper Side                            | deck_panel_left.dxf and [...] right.dxf| deck_upper_non_pro             | Also available as dxf, Make sure you get it mirrored when getting cut and the material has two surfaces structues                                     |
| Rear Panel                                 | rear_panel            | rear_panel_non_pro                              | Also available as dxf                                      |
| If using the original thick PSU:           |                       |                                                 |                                                            |
| PSU Mount                                  | PS_4040_mount_x2      | 2x orig_psu_mount                               |                                                            |
| Extension:                                 | rear_extention_left_a | extension_left_a_orig_psu                       |                                                            |




![Home](enderwire_nonpro.png)
