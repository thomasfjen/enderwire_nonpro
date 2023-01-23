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
- Located of Pi to the front.
- Connected front idler mount to frame.
- There is no belt tensioner, use the rear motor mount to tension the belt (Same as Switchwire)

Use these STL-Files for the Y-Axis: 
https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Gizzle/ender-3_(pro)_switchwire/STL/Y-ASSEMBLY 

Rest of STL-Files, basically everything except the Y-Axis:
https://github.com/boubounokefalos/Ender_SW/tree/Rev.2/STLS

Watch the Table down below to replace files to make these two repos compatible.


| Part                                       | Original              | Replace with:                                   | Comment:                                                   |
|--------------------------------------------|-----------------------|-------------------------------------------------|------------------------------------------------------------|
| Parts form Y-Axis Gizzle Repo                          |                       |                                                 |                                                            |
| Y-Axis Front Idler                         | Y-Idler-Bottom        | y_idler_lower_part and front_y_grill_connection | Adds a connection to the Front Grill                       |
| Parts from DarkDogs (boubounokefalos) Rev2 |                       |                                                 |                                                            |
| Grill                                      | rear_grill_middle     | rear_grill_middle_nonpro                        |                                                            |
| Extension/Side Skirt                       | rear_extention_left_a | rear_extention_left_a_psu                       | Also replaces the PS_4040_Slide_Mount as mount for the psu |
| Deck Upper Side                            | deck_panel_left.dxf and [...] right.dxf| deck_upper_non_pro                              | Also available as dxf                                      |
| Rear Panel                                 | rear_panel            | rear_panel_non_pro                              | Also available as dxf                                      |
| If using the original thick PSU:           |                       |                                                 |                                                            |
| PSU Mount                                  | PS_4040_mount_x2      | 2x orig_psu_mount                               |                                                            |
| Extension:                                 | rear_extention_left_a | extension_left_a_orig_psu                       |                                                            |




![Home](enderwire_non_pro_0.2.png)
![Home](enderwire_Housing.png)
