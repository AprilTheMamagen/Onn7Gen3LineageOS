Onn 7 inch Gen 3 LineageOS and Bootloader Unlock

**WINDOWS ONLY** (for now :3)

This puts so much more usability into this tablet

Credits to the LineageOS team and Andy Yans GSI. 

Downloads Provided for the project:
https://drive.google.com/file/d/1oZdV-iTmwDtbMvVDjsFte2edj4PGvQnc/view?usp=sharing

IF YOUR DEVICE ISNT RECOGNIZED INSTALL GOOGLE USB DRIVER
https://dl.google.com/android/repository/usb_driver_r13-windows.zip






**Step 1:**
Install required drivers, and unzip the ONN.zip file.

**Step 2:**
Go to Settings on your tablet and go to About tablet, and scroll down until you see Build Number. Tap it until you see "You've enabled development settings".

**Step 3:** 
Go back to main settings page and hit system, and open developer settings. Now, tap Enable OEM unlocking, and USB Debugging. 

**Step 4:**
Open the Android Utility folder in the zip file i told you to extract, and scroll down and run AndroidUtility.exe

**Step 5:**
On the program, click mediatek at the top where Samsung, Qualcomm, Xiaomi, etc are, then click reboot fastboot mode

**Step 6:** 
Plug your device in, and power it off. Trust me I know it sounds silly but it works. 
(Once the Android Utility app sees your device, your device should reboot and show a screen that says this at the bottom "=>FASTBOOT MODE" It may be different, but not much.)

**Step 7:** 
Now, Go back to file explorer to the folder you downloaded and go to platform tools. Then click the address bar and type in "cmd".

**Step 8:** 
Type in the command prompt, "fastboot flashing unlock" and then go back to your device and press volume up. 

**Step 9:**
Go back to the command prompt and type in "fastboot reboot fastboot" (This is needed! Wont flash if you dont run this.)

**Step 10:** 
Now, Type in the command prompt "fastboot flash system " (make sure to have a space at the end) Then drag the System.img file in the root of the folder to the command prompt.

You should be done :)
