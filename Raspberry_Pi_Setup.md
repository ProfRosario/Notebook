
Setup Raspberry Pi with NOOBS
========
Using NOOBS to setup Raspberry Pi  (http://elinux.org/RPi_Easy_SD_Card_Setup)

The Raspberry Pi Foundation has released an easy to use software tool to setup the Raspberry SD card. The tool is called NOOBS, 
which means New Out Of Box Software. It's a simple tool, with very little hassle or pain, to install various Raspberry Pi 
distribution from one simple menu selection. The original software is around 1 GB download, however you can download a compressed
version from from Raspberry Pi organization, which is less than 500 MB. 

To install the Raspberry distribution on the SD card:

1) Download NOOBS from the raspberrypi.org downloads page

2) Insert a (4 GB+) SD Card into your computer
        - If you want to save space on the SD Card, you can delete some of the images inside the OS folder in the NOOBS zip file that you don't want to use.

3) Format the disk. The easies SD card format tool is SD Associate

For Windows
======

	a.  Download and install the SD Association's Formatting tool from [https://www.sdcard.org/downloads/formatter_4/eula_windows/](https://www.sdcard.org/downloads/formatter_4/eula_windows/)
        Open the Application you have just installed
        b. Set "FORMAT SIZE ADJUSTMENT" to ON in the Options menu.
        c. Make sure you have selected the Drive your SD Card is inserted in
        Click "Format"
        
For Mac
==========
        a. Download and install the SD Association's Formatting tools from [https://www.sdcard.org/downloads/formatter_4/eula_mac/](https://www.sdcard.org/downloads/formatter_4/eula_mac/)
        b. Select "Overwrite format"
        c. Make sure you have selected your SD Card, and not something else
        d. Click "Format"
For Linux
======
        a. Use gparted (or the command-line version parted if you prefer), if you don't have it, install it as you usually would.
        b. Format the entire disk as FAT32 (FAT16 will not work! Make sure you select the correct disk!)

4) Extract the file you downloaded in Step 1

5) Copy the files you just extracted to your SD Card (see below on flashing your SD card)

Note: Not all monitors work well with NOOBS straight away. If your monitor is one of those that doesn't work, press the Number buttons 1-4 until you see what you want.

    a. Default HDMI Mode
    b. HDMI Safe Mode - Use this if Default (1) doesn't work and you cannot see anything
    c. Composite PAL Mode - Use this or 4. if you are using the yellow and black outputs on the opposite side to the HDMI output
    d. Composite NTSC Mode
