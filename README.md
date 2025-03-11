# JS20_Hotswap_Joystick_Socket
Socket For the JS20/JH20 Joystick **UNTESTED

Based off the dimensions for the JS20 TMR Joystick thus all files are Named with JS20, although it should be compatable with the JH20 Hall Effect Joystick.

The socket consists of a PCB, 3D printed clip, and a 3D printed spacer that goes between the PCB and the joystick. The PCB uses short Pogo Pins in order to interface with the Joystick without needing to be too precise, which is important since the datasheet did not specify how deep the holes to the contact plates are.

## PCBs
the "JS20" PCB is for using in your own PCBs. It is not a footprint because it is made of several individual parts. When placing remember that clip will have to go around it so be mindfull of other parts within 5mm of it. you can modify the clip to avoid such parts if need be.
the "JS20PINOUT" is a small pinout board with production files made using the Fabrication Toolkit plugin for KiCad
"JS20_JST4PIN" is similar with but with a JST 4 Pin connector, for a project im working on. The button for pressing down on the joystick is unmapped.

## STLs
"JS20 Over PCB Clip for Remix" is for use when you incorperate the joystick into a larger PCB. It has no way to mount it as it is, and will need to be edited in order to work with your pcb. Do Not change the hight as it is important for its function.
"JS20 Pin Out Clip Standalone" is a ready to print file for use with the PINOUT and JST4PIN PCBs. To assemble insert the PCB, then the spacer, then the joystick.
"JS20 Pin Out Clip for Remix" is the same as the Standalone STL except without the bottom so you can place it on another 3D printing project.
"JS20 Spacer" helps support the joystick.

## Where to get the Joysticks
The joysticks can be found on aliexpress. Search for "Hotswap Joystick" the Joysticks with the teal sticks are the JS20 TMR joysticks while the ones with sticks that match the color of the body are the JH20 Hall Effect. Sometimes the ones that are teal get labeled as JH20, as far as i can tell they are just wrong. The hall effect joysticks are cheaper, but require 5v to operate from my research. The TMR joysticks can run on 3v I think... I havent found a clear answer but its often said that TMR is lower power and doesnt require modding a controller when doing a replacement so I think so. also TMR is in theory more precise but its a joystick so unless you have a large range of motion like a flight stick that prbably doesnt matter. both are contactless, so neither should experience much drift.

### Referenced Data Sheets
 JS20 http://www.k-silver.com/en/index.php/product/detail/44.html
 JH20 (not referenced but relevent) http://www.k-silver.com/en/index.php/product/detail/50.html
 Pogo Pin https://www.lcsc.com/datasheet/lcsc_datasheet_2306191048_Xinyangze-YZR0028-15020-01_C7429439.pdf
