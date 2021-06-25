# Cherryblossom

The Cherry Blossom is a South African based SBC with its origin on the Beaglebone Black. It is a low-cost, high-expansion SBC focusing on industrial use cases. 
Cherry Blossom using a low cost Sitara X AM3359AZCZ100 Cortex A8 ARM processor from Texas Instruments. 
Cherry Blossom comes with onboard memory 4GB (older models have 2GB EMMC) and a SD card slot for memory expansion 

 It has lot of I/O pins, including analog-to-digital converter (ADC) and pulse-width-modulation (PWM) pins. 
 It also has an HDMI output(via stacker board), a USB plug (for a camera, keyboard/mouse, etc. via stacker board) and another USB for connection to a computer, ethernet(via stacker board), on-board LEDs, and a 5V input jack.
 
Terms of Use
UPDATED INFORMATION

You may use the Cherry Blossom design materials as you choose. 
In addition, we will make revisions to the board as we find necessary . 

When used in a product, the end customer is responsible for its use in their product. 
Changes in components used in the production of these boards such as memory devices, may affect operation of the board.

Accessories and Stackers
For a list of the confirmed working accessories please see documents inside for anything that can be added to the Cherry Blossom.

eMMC: All Cherry Blossom Variants with eMMC

This image can be written to a 4GB (or larger) microSD card, via 'dd' on Linux or on Windows/Mac/Linux: https://etcher.io First press and hold the boot select button (next to the microSD card), then apply power. On boot-up the board should indicate it has started the flashing procedure visually via a Cylon Sweep pattern shown on the 4 LED's . Progress is reported on both the serial debug connectors, once completed all 4 LED's should be full ON or OFF. Simply remove power, remove the microSD card and Cherry Blossom will now boot directly from eMMC. If a error occur during flashing , all 4 LED's will flash.

For the Cherry Blossom Linux image please visit the following link
There are a few images in this repository , Lightwheigt EMMC image and a full Cherry image. The Cherry image Already contains a few programs including Midnight Commander and Mosquitto MQTT Broker and Client for a quick IOT implementation

https://drive.google.com/drive/folders/1j5dsH3DSFfHHZwSp7D7rXoTJVxT-0lyx?usp=sharing

For more information please contact Arrow South Africa , +27119239600 , info@arrow.altech.co.za


Extra resources:

General Projects and Cumunity support

https://forum.beagleboard.org/

https://beagleboard.org/p

https://beagleboard.org/Videos


<tr><td>UBUNTU:</td></tr>

https://elinux.org/BeagleBoardUbuntu#eMMC:_All_BeagleBone_Variants_with_eMMC

Android:

https://elinux.org/Beagleboard:Android

http://bbbandroid.sourceforge.net/

https://beagleboard.org/p/hendersa/android-on-the-beaglebone-black-with-the-3-8-linux-kernel-341710

https://2net.co.uk/tutorial/android-4.4-beaglebone-update





