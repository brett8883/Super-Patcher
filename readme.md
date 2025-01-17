<a href="https://github.com/brett8883/DJI_Super-Patcher
" target="_blank"><img src="https://github.com/brett8883/DJI_Super-Patcher/blob/photos/readmephotos/super-Patcher.png"
alt="IMAGE ALT TEXT HERE" width="950" height="180" border="10" /></a>

# DJI Super-Patcher 2.0.3 updates
There was a problem some users reported that the included version of Busybox.exe wasn't working so I added 64 bit and 64 bit ARM versions for the program to try. I also added more error handling during start up to prevent a complete crash. Thank you to Tower669 on MavicPilots for bringing the Busybox issue to my attention and providing the solution. 

Be sure to unzip the Super-Patcher folder and dont run it from with the zip archive. 

There are no new features. If the old version works for you just keep it

-------------------------------------------------------------------------------------------------------------------

# DJI Super-Patcher

Super-Patcher now supports the following aircraft and firmwares:

- Mavic Pro/Mavic Pro Platinum/Mavic Pro Alpine White V01.04.0300

- Spark V01.00.0900

- Phantom 4 Pro V01.05.0600

- Phantom 4 standard V2.00.0700

- Phantom 4 advanced V1.00.0128

- Phantom 4 ProV2 V01.00.1500

- Inspire 2 V01.02.0200

## OBJECTIVE SUMMARY

The purpose of this project is to liberate DJI aircraft from the limitations imposed by DJI. DJI Super-Patcher allows new features/abilities, unlocks arbutrary limitations, and allows DJI aircraft to be customized far beyond what is allowed by the factory firmware.

Super-Patcher works differently than other methods for unlocking firmware. It is not a modification that mixes old firmware with new firmware. Super-Patcher patches the flight controller module that is already installed on your aircraft. This ability to patch the actual firmware itself means that new capabilities are unlocked. Super-Patcher has been tested and verified. You can trust that it has been proven but you still use at your own risk. 

While Super-Patcher removes the default altitude and GeoZone limitations, that does not mean it is safe or legal to do so in your area without proper authorization. DJI Super-Patcher is meant to allow responsible pilots with the correct authorization to fly in areas and to heights that DJI does not offer a reasonable method or any method at all to unlock. It is solely the responsibility of the pilot to ensure local laws and regulations are adhered to and to fly safely just like with any other aircraft. 

PLEASE FLY RESPONSIBLY!

Super-Patcher has been designed to be used by the average joe and much of the design and development has been to make the process as easy as possible. It only requires very basic computer skills, such as clicking buttons and navigating to a folder using the file explorer. Super-Patcher is a batch script that runs natively on all Windows PCs and all dependancies are downloaded automatically by the program. No prior set up is required. Super-Patcher is interactive and walks the user through step-by-step dynamically based on user selections. It doesn't get much easier than this.
***
 *[CLICK] On the photo below to watch @digdat0's turtorial on DJI Super-Patcher :*
<a href="http://www.youtube.com/watch?feature=player_embedded&v=rFrQ52m8bos
" target="_blank"><img src="https://raw.githubusercontent.com/brett8883/DJI_Super-Patcher/photos/sp2.0DigDat0.PNG" 
alt="IMAGE ALT TEXT HERE" width="800" height="500" border="10" /></a>

*(Thanks @digdat0!)*
***************************************************************************************************************************

**BENEFITS SUMMARY**

*(PLEASE READ THE DETAILED LIST THAT FOLLOWS AS WELL)*

- Remove height limitations
- Remove NFZ and GeoZone limits
- Enable Galileo satellite reception
- Customize the Smart Battery settings
  - Customize or disable low battery forced auto-landing.
  - Customize or disable low battery return-to-home
  - Customize or disable low battery warnings
- Motors can be started when aircraft is inverted
- No motors errors on Mavic Pro Platinum
- Does NOT require an internal SD card be installed
- Precision RTH and Precision Landing will work normally
- Optionally enable slower more cinematic panning (yaw) speed
- Optionally enable full time FCC or boost mode with jkson_fcc_mod by jkson5 built in (Mavic, Spark***(NEW!)***, and P4PV2 Only)
- Optionally disable external aircraft LEDS lighting for stealthy night flying. 

***************************************************************************************************************************
**Please carefully read through the through explanation of the benefits below. Directions to get started will follow**
***************************************************************************************************************************

# ***Features of Super-Patcher***

### Remove height limitations by default

- There is nothing additional the user needs to do to enable this feature and it is always enabled.

- As soon as the Super-Patcher process is complete the drone will ignore ALL height limitations even if set by the user in DJI Go 4.

  -Even though the user is able to enter a value in for height limit in DJI Go 4, the drone WILL NOT obey this hight limit command.

    - **Please fly with caution!**

- *This is not optional and is hard-coded into the firmware. There will be no height limit parameters visable in Assistant 2*

- To enable height limits again would require uninstalling Super-Patcher which can be done simply by flashing to a stock firmware version

- Please note that the height limit parameters in Assistant 2 1.1.2 in debug mode will NOT be visable beacuse they are hard-coded to the firmware. These parameters have been modified to disable height limit altogether even though they are not visable.  

     ***It is always the responsibility of the pilot to fly safely and to know local regulations.***

***************************************************************************************************************************

### Remove NFZ and GeoZone limits by default

  There is nothing additional the user needs to do to enable this feature and it is always enabled.

- As soon as the Super-Patcher process is complete the drone will ignore all forced GeoZone and NFZ limitations

  - **This is not an optional and is hard coded into the firmware.**

- Please note:

  - GeoZones will still be marked in the app and the app will still warn you when the drone is close to or in an NFZ,

  however…

    - Your drone will not be prevented from flying

    - Your drone will not be forced to auto-land.

    - You drone will not be preventing from taking off

      - **Please fly with caution!**

- The airport limit parameters are hard-coded and will not be visible in Assistant 2. Airport limits have already been disabled. These parameters have been modified to disable airport limits altogether even though they are not visible.

    **It is always the responsibility of the pilot to fly safely and to know local regulations.**
***************************************************************************************************************************
### Unlocks the max distance limit for waypoint missions

- DJI has limited the length of waypoint missions to 5000 meters on factory firmware. Super-Patcher removes this limit.

*NOTE: A third party app such as Litchi may be needed to upload waypoint missions longer than 5000m. The way the DJI Go 4 app works it may not allow a mission greater than 5000m to be uploaded to the aircraft regardless of the firmware limit being removed.*
***************************************************************************************************************************

### Enable Galileo satellite reception by default

- The drone will now connect to Galileo GPS satellites in addition to the satellites already available. This means you can expect to see a greater satellite count in the app and a stronger, more reliable, and more accurate GPS signal.

- There is nothing additional the user needs to do to enable it and it is always enabled.

- Typically you can expect to see your sat count at between 20-30 satellites once they have all connected

***************************************************************************************************************************

### Does NOT require an internal SD card be installed

- With older methods for unlocking, namely mixed firmware mods, the Mavic Pro Platinum and some more recently manufactured Mavic Pros required that the Mavic be opened and an internal SD card installed for other mods to work. **NOT** with Super-Patcher. Super-Patcher does **NOT** require an internal SD card because it is **NOT** a mixed firmware modification.
***************************************************************************************************************************

### No motors errors on Mavic Pro Platinum

- With older modification techniques, namely mixed firmware mods, the Mavic Pro Platinum will give motor errors due to not having the correct ESC modules for the upgraded MPP ESCs

- Because Super-Patcher modifies the flight controller on v01.04.0300 firmware which has the correct ESC modules for Mavic Pro AND Mavic Pro Platinum there will be no motor errors and ESCs will work as designed

***************************************************************************************************************************

### Precision RTH and Precision Landing are not affected and will work normally**

- With older methods for removing height limits and NFZ limits, namely mixed firmware mods, the precision RTH and precision landing features did not function as expected.

- Because Super-Patcher is not a mixed firmware mod it does **NOT** affect these functions and so they will work as expected.

***************************************************************************************************************************
### Motors can be restarted when aircraft is inverted

- By default the aircraft will allow the motors to be restarted even if the aircraft is inverted. 
 - This parameter is hardcoded and will not be visable in Assistant 2. One can remove the props and hold the aircraft upside down and then arm the motors with a CSC to verify this parameter is working.

- This is primarily to allow pilots that preform a CSC maneuver while in flight(cut the motors while flying either as an emergency maneuver or as a daredevil stunt) to turn the motors back on even if the aircraft flips in flight.

- This setting also can save the aircraft from a catastrophic crash after a colision that turns the aircraft upside down.
 - The aircraft will immediately right itself rather than cutting the motors automatically which is the factory default behavior when being flipped in flight.
  - *NOTE:* **This also means the motors cannot be turned off by turning it upside down when hand catching. When hand catching, use the free hand to push down on the throttle stick (left stick in RC type 2) to turn off the motors when hand catching.**
***************************************************************************************************************************
## OPTIONAL FEATURES

### SMART BATTERY MOD
***Super-Patcher unlocks the DJI Smart Battery to its full potential making it 100% customizable.***
 - Say goodbye to "non-DJI battery mode!"
   - Fully customize the DJI Smart battery behavior and take back ownership of your aircraft
   - Smart battery mod can be custom configured by the user in Assistant 2 1.1.2 in debug mode or be pre-configured by Super-Patcher
    - NOTE: Default parameters for DJI Smart Battery remain factory default unless "YES" is selected by the user during the Super-Patcher process to have the Smart Battery pre-configured by Super-Patcher

   **Super-Patcher pre-configured battery mod option (select [YES] to SMART BATTERY MOD)**
     - Disable Forced Auto-Landing due to Smart Battery low battery
      -*NOTE:A final "emergency auto-landing" will only occur at the emergency low voltage level which is at 3.0v per cell (well below the safe voltage to fly.) This can also be disabled in Assistant 2 1.1.2 in debug mode.*
     - Re-calibrated Smart Battery "Only enough battery remaining to return to the home point" calculation to be more accurate
      - Can be further customized by the user in Assistant 2 1.1.2 in debug mode

    - Disable low battery warning when using DJI Smart Battery
     - Can be reenabled in Assistant 2 or set at any battery percentage level
    - Disabled critical low battery warning when using DJI Smart Battery
     - Can be reenabled in Assistant 2 or set at any battery percentage level

These options can be enabled in Assistant 2 1.1.2 ***OR*** they can be enabled by AUTOMATICALLY by indicating "YES" during the Super-Patcher process.

***NOTE: The Smart Battery modifications can also be disabled or tweaked to user preference in Assistant 2 1.1.2 in debug mode***

***NOTE: The Smart Battery Mod is a modification to how the aircraft responds to input from the Smart Battery. It is not a modification TO the Smart Battery***

***FURTHER DOCUMENTATION FOR SMART BATTERY MOD COMING SOON***

### STEALTH MOD
The new Stealth modification will disable the rear LED lights on the aircraft which will remain OFF during flight for Super Stealthy flight.

- The Stealth modification is optional but it is hard-coded into the firmware and cannot be changed by the user in flight or with Assistant 2 1.1.2 in debug mode
  NOTE: To undo the Stealth mod, simply run Super-Patcher again without the Stealth mod selected or download and flash stock firmware from the MainMenu

   **Optionally customize parameters with Assistant 2 1.1.2 in debug mode**

- Just like any other firmware you can use Assistant 2 1.1.2 in debug mode to turn up the max speed parameters, enable ATTI mode, or virtually endless parameter modifications

- For more information on some of the available parameter mods see [howto:parameterhacks](https://dji.retroroms.info/howto/parameterhacks)
These are optional

***************************************************************************************************************************

## Optionally enable slower more cinematic panning motions for more cinematic video.**

- Enables setting yaw speed to as low as 1 degree per second in any mode using Assistant 2 1.1.2 in debug mode or directly in DJI Go 4 for P-GPS mode to get much smoother and slower cinematic pans.

  - By default yaw speeds are factory default

- Each flight mode has its own yaw speed parameter that can be changed in Assistant 2 1.1.2 in debug mode. The value these parameters is in degrees per second

     ***The parameters for yaw speed for each mode are:***

    - **P-GPS** *mode with front OA sensors ON*

          g_config_avoid_cfg_avoid_tors_rate_range

    - **P-GPS** *mode with front sensors OFF*

          g_config_mode_normal_cfg_tors_gyro_range


    - **Sport Mode**

          g_config_mode_sport_cfg_tors_gyro_range

    - **Tripod mode**

          g_config_mode_tripod_cfg_tors_gyro_range

    - **Cinematic Mode**

           CM_tors_range

    **These are optional**

***

## Optionally enable full time FCC or FCC boost mode with jkson_fcc_mod by jkson5**

- You will be asked if you'd like to enable jkson_fcc_mod if your aircraft supports it. Jkson_fcc_mod is only availible for Mavic Pro, Mavic Pro Platinum, Mavic Pro Artic White, and P4Pv2

- Jkson mod also allows you to choose between "Auto frequency" (2.4 GHz), fixed 2.3 GHz, and fixed 2.5 GHz.
	- I highly recommend choosing "Auto-frequency"
		- 2.3 GHz and 2.5 GHz might be better in 1% of cases but it is very rare and even if they do work better they are more likely to cut video feed without warning because they are fixed to a single channel.

- You can learn more about jkson fcc mod by jkson5 at https://github.com/jkson5/jkson_fcc_mod

- I am not the developer of this mod so questions about it are better directed to jkson5

- It is included in Super-Patcher because it is a widely used mod and it shares dependancies with Super-Patcher so it made sense to include it for convenience 	

    **This is optional**
***************************************************************************************************************************
***************************************************************************************************************************

# PREREQUISITES

- ***Mavic Pro***; ***Mavic Pro Platinum***; or ***Mavic Pro Alpine White*** has to be running STOCK ***V01.04.0300*** fw for all modules

or

- ***Spark*** has to be running STOCK ***V01.00.0900*** fw for all modules

or

- ***Phantom 4 Professional*** has to be running on STOCK ***V1.05.0600*** fw for all modules

or

- ***Phantom 4 Standard*** has to be running on ***V02.00.0700***  fw for all modules

or

- ***Phantom 4 Advanced*** has to be running on ***V01.00.0128*** fw for all modules

or

***Phantom 4 ProV2*** running a 100% stock version of the ***V01.00.1500*** firmware for all modules

or

***Inspire 2*** running a 100% stock version of the ***V01.02.0200*** firmware for all modules

  - *This means if your firmware is mixed with the flight controller of another firmware, even though it says you are on the correct firmware, you will need to flash a stock version of the correct firmware for you aircraft listed above TWICE to ensure all modules get flashed.*

    - When in doubt flash the correct stock firmware **TWICE** with DUMLdore
	
**Super Patcher 2.0 and above includes a utility to automatically download and install the correct stock firmware. Use this for best results**

or

- Get correct stock firmware versions with [DankDroneDownloader Tool](https://github.com/cs2000/DankDroneDownloader) :

- Get DUMLdore from here:

    https://github.com/jezzab/DUMLdore/releases/tag/v3.20
***

- **Super-Patcher only runs on Windows**
  - *Works best on Windows 10*
	- Mileage may vary on other versions of Windows

 - Mac users can run Windows 10 in bootcamp mode on their Mac for best results. With Virtual Machines such as Virtual Box, mileage may vary.

***************************************************************************************************************************
***************************************************************************************************************************

## DIRECTIONS

1. Ensure the prerequisites above are met

2. Download or clone the entire repository
  - Be sure to keep all files in original folders

3. Double click the DJI_Super-PatcherV2.0.1.cmd file to start the program

4. Super-Patcher will check internet connection to GitHub which is required and the Windows version of the PC and then download the files it needs to run.

5. At the Super-Patcher MainMenu you get several options and it allows you to use the utilities included in the program independantly of the Super-Patcher process

- Choose option #1 with your keyboard if you already have the correct stock firmware installed for your aircraft. IF you do not have the correct firmware installed you can instead choose option #2 to download and install the correct firmware.

6. After choosing option #1 the program will ask you the optional mods you'd like to install and then will prompt you to turn on your aircraft and connect it to the PC

7. Super-Patcher will guide you through the process from here.

  - **Please do what it says when it says to do it**

    - Follow all the steps even if you think you don't need to do them... **YOU DO!**

    - Don't try to outsmart the process or do anything extra "for good measure"

      - these are the main reasons for Super-Patcher not being successful


8. You will be prompted to verify the firmware version with the DJI Go 4 app. If Super-Patcher was successful DJI Go 4 will show the firmware version as 00.00.0000. This is normal and a good thing.

9. You may optionally use the simulator in Assistant 2 or DJI Go 4 to verify working order before testing outside.

- If there are issues with flight in the simulator there will be issues with flight in real life.

  - Re-flash stock firmware and then redo ENTIRE Super-Patcher process in case of an issue.

    - *Please Note: To date there has never been an issue with flight after installing Super-Patcher. This recommendation is only a matter of good practice whenever modifying or flashing firmware*

Done!

  - Process takes maybe 5 minutes

***************************************************************************************************************************    
**DO NOT PROCEED IF YOU DONT UNDERSTAND**
***************************************************************************************************************************
***************************************************************************************************************************

## **FAQ**

*Q: Do I need a specific version of the DJI Go 4 app to get the benefits of this mod?*

**A: No, Super-Patcher is not dependent on an app so you can use any one you’d like.**

*Q: Do I need to do anything with the controller? Like upgrade/downgrade the controller?*

**A: No, Super-Patcher doesn’t do anything with the controller and it makes no difference which controller firmware you are using.**

*Q: There is a parameter called g_config_fw_cfg_max_speed=10 that increased the max flight speed and I was told to increase this to 20 so I can fly faster but when I try to adjust this parameter in Assistant 2 it reverts back to 10 when I reboot the aircraft. How to I change this parameter so I can increase flight speed?*

**A. The parameter** g_config_fw_cfg_max_speed=10 **does not affect flight speed. The parameters that control max flight speed end with** "_cfg_tilt_atti_range" **and** "_cfg_rc_scale"**each mode has a parameter like this that will adjust the max speed in each mode. g_config_fw_cfg_max_speed=10 was misidentified and some point in the past as a max flight speed parameter but it is not. I do not know what it does but I know it does not affect max flight speed. On the newer firmware this parameter is hardcoded but still visible in Assistant 2 1.1.2 so it will seemingly change in Assistant 2 1.1.2 but in reality it will not let you change it. As far as I am concerned nobody knows what this parameters does.**   

*Q: Is it worth trying this in my Mavic 2? Any idea when Mavic 2 will be available?*

**A: Super-Patcher has zero chance of working on the Mavic 2 at this time. We need a decryption key for Mavic 2’s firmware and a way to gain adb access. Both of those things are above my pay grade**

***************************************************************************************************************************
***************************************************************************************************************************

## Donations are very welcome and very much appreciated via [paypal.me/brett8883](https://www.paypal.com/paypalme2/brett8883)
- Note that donating here does not donate to the other repos that make Super-Patcher possible. 

***************************************************************************************************************************
## Acknowledgments

While I brought everything together into a single easy to use project and maintain this repo, Super-Patcher is the culmination of work of many various other projects, contributors, and beta testers.

A special thanks to Henfri and lukasx for taking the plunge to test this with their birds before knowing what would happen and their continued contributions throughout development.

Thanks to D95GAS, frank2006, and Kilrah for consulting during initial conceptual development.

A special thanks to @BorisPlintovic for the FCC + Boost mod for Spark.

A special thanks to mstoozler for providing the 0306.unsig for Inspire 2 flight controller and testing the Inspire 2 patch.

A special thanks to Matioupi and the OG’s [/o-gs/DJI_FC_Patcher](https://github.com/o-gs/DJI_FC_Patcher) project and all its contributors of which Super-Patcher can be considered as a branch of and very much dependent on. DJI_FC_Patcher is the engine that drives this project. Super-Patcher serves as an easy to use deployment of the DJI_FC_Patcher that anyone can use with almost no technical ability.

A special thanks to jezzab and the [jezzab/DUMLdore](https://github.com/jezzab/DUMLdore) application  a full copy of which is included in Super-Patcher and without it Super-Patcher would not be possible.

Thanks to Mefistotelis for his [dji-firmware-tools](https://github.com/o-gs/dji-firmware-tools) and tutoring me on how to use them.

Thanks to DigDat0 for helping with the 1.3 upgrades which were influenced by his [fcchooser](https://github.com/digdat0/fcchooser) project and for teaching me various programming techniques.

Thanks to jkson5 who is the author of the jkson fcc mod which I have barrowed and intregrated into Super-Patcher 1.3 and above

Thanks to the other OGs who have contributed to the dependencies required for Super-Patche and who have, by making their work open, helped me liberate my drone from the limits imposed on it by DJI and inspired me to help others liberate theirs.

There are many whos names I do not know that contributed to the dependencies required for this project. I apologize for not having all of their names acknowledged but I will update this list as I discover them.
