# Ublox C030 variant for stm32duino

[stm32duino github](https://github.com/stm32duino)  

[stm32duino home page](http://www.stm32duino.com/)

## Install instructions
### Install latest Arduino IDE
[Arduino Software page](https://www.arduino.cc/en/Main/Software)

### Add STM32duino to Boards Manager
Follow all steps accoring to these instructions:  
[STM32duino wiki - Boards Manager](https://github.com/stm32duino/wiki/wiki/Boards-Manager)  

or these...  
Condenced version:  
1 - Launch Arduino IDE. Click on "File" menu and then "Preferences".  
  - Add the following link to the "Additional Boards Managers URLs" field:
  https://github.com/stm32duino/BoardManagerFiles/raw/master/STM32/package_stm_index.json

2 - Click on "Tools" menu and then "Boards > Boards Manager"
  - Select "Contributed" type.
  - Select the "STM32 Cores" and click on install.  

3 - Done.

## Adding the C030 variant.
Navigate to your corresponding STM32duino AppData folder ex.  
C:\Users\\[User_Name]\AppData\Local\Arduino15\packages\STM32\hardware\stm32\2017.11.24\

Clone or Download this project to your computer and copy the files to the STM32duino folder.  
If you already have custom boards added just copy the necessary lines from board.txt.  
If you have a fresh install of STM32duino just overwrite everything.

### Open a sketch and start coding.
