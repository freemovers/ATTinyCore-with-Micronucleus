# ATTinyCore-with-Micronucleus
Boards manager file to add SpenceKonde ATTinyCore with Micronucleus to Arduino

NOTE: Micronucleus must be installed on the board in order to use this bootloader. 
Follow the instructions on https://github.com/micronucleus/micronucleus

This board manager will automatically install the Micronucleus executable for uploading sketches to ATtiny in Arduino. Core is using the ATTinyCore by Spence Konde and must be installed separate.

# Installation:
Add the additional board managers in the Arduino as follows:
Go to File ->Preferences
Add the following boards to "Additional Boards Manager URLs:"  
http://drazzy.com/package_drazzy.com_index.json  
https://californiasteam.tech/californiasteamarduino/package_californiasteam_index.json

Next go to Tools  -> Boards: XXX -> Boards Manager  
Search for **ATtiny** and install the following boards:  
**ATTinyCore** by **Spence Konde**  
**ATtinyCore boards with Micronucleus** by **California STEAM**
