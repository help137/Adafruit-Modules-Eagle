# Adafruit-Modules-Eagle
Adafruit Modules and Breakouts Eagle Library

In Eagle 7 format

### Don't click on the files! 

[Click here](https://github.com/help137/Adafruit-Modules-Eagle/archive/main.zip) to download this as a zip file.

### Installation

1. Open Eagle and select the `Control Panel` window.
2. Choose `Options` and from the drop down that appears, `Directories`.
3. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:

    > $EAGLEDIR/lbr:$HOME/external_lbrs (for OS X)

    > $EAGLEDIR\lbr;$HOME\external_lbrs (for Windows)

4. Click `OK` to save your changes.
5. Eagle will prompt to create the directory if it does not already exist. Note 
the location and choose `Yes` to create the directory.

    > On OS X, `$HOME/external_lbrs` changes to: /Users/mosfet/external_lbrs/
    
    > On Windows, `$HOME\external_lbrs` changes to: C:\Users\Mosfet\Documents\external_lbrs

6. Find and open the `external_lbrs` folder. Unzip and drag `adafruit.lbr` into the 
   new `external_lbrs` folder.
7. Restart Eagle. The library should be now be usable. 

#Included:

1500 - Original Trinket 3V  
1501 - Original Trinket 5V  
1782 - MCP9808 High Accuracy I2C Temperature Sensor Breakout Board  
1875 - TXB0104 Bi-Directional Level Shifter Breakout  
1895 - I2C Non-Volatile FRAM Breakout - 256Kbit / 32KByte   
1897 - SPI FRAM Breakout 64Kbit (8Kbyte)  
2748 - ALS-PT19 Analog Light Sensor Breakout  
3675 - Itsy-Bitsy 32U4 3V  
3677 - Itsy-Bitsy 32U4 5V  
3727 - Itsy-Bitsy M0 Express  
3727 - Itsy-Bitsy M0 Express No End Pins (Altered layout for easier routing when you don't need end row of pins.)  
3800 - Itsy-Bitsy M4 Express  
3500 - Trinket M0  
2771 - Feather 32u4 Basic Proto  
2772 - Feather M0 Basic Proto  
2796 - Feather M0 Adalogger  
2821 - Feather HUZZAH ESP8266  
2829 - Feather 32u4 Bluefruit LE  
2995 - Feather M0 Bluefruit LE  
3010 - Feather M0 WiFi  
3027 - Feather 32u4 FONA  
3056 - Feather WICED - Warning - Untested: Verify all connections!  
3061 - Feather M0 WiFi with uFL  
3403 - Feather M0 Express  
3405 - Feather HUZZAH32 ESP32  
3406 - Feather nRF52 Bluefruit LE  
3458 - Feather 328P   
3574 - Feather nRF52 Bluefruit LE Pro  
3857 - Feather M4 Express  
4062 - Feather nRF52840 Express  
4516 - Feather nRF52840 Sense  
3076, 3077 - Feather 32u4 RFM69HCW  
3078, 3079 - Feather 32u4 LoRa  
3176, 3177 - Feather M0 RFM69HCW  
3178, 3179 - Feather M0 LoRa  
TEMT6000x01 - SparkFun Ambient Light Sensor Breakout TEMT6000  
