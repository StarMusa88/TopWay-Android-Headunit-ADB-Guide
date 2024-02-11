# TopWay-Android-Headunit-ADB-Guide
Guide On how to wirelessly Connect Top Way Ts10 Android Head unit using ADB Commands (non-root) and using U.A.D ( Universal Android Debloater) to debloat the Head Unit from unwanted system applications. (((USE AT YOUR OWN RISK)))

1- First we need to connect to WIFI and enable developers option.(7890+current time using 24 hour format) >> use code 7890 plus current time for example if the current time is 8:00 PM you type in 789020 << 

2- Then we need to enable USB Debugging (john@tw-desktop) is the code for Topway TS10 android 10 model. Next we need to install F.Droid application. From F.Droid we need to install Termux and Terminal Emulator. Now that we have all our applications installed (make sure to update each application after install) we will begin with opening Terminal Emulator and typing (setprop service.adb.tcp.port 5555) and press enter.

3- Next we open Termux and install android-tools >>// pkg install android-tools \\<< we then type in the command ( adb ) to see if the adb command is working. 

4- Finally to connect wirelessly to your HeadUnit we will type in the Termux Terminal 
( adb connect 192.xx.xx.xx:5555 )  your HeadUnit IP address. you can find your IP address by going into settings to  >> about phone > status //and your Headunits IP address should be listed.

5- Once you have established a successfull ADB connection with your headunit you can now use Universal Android Debloater from your PC or Laptop by using step 4 in the guide.

Note: Once you Allow the connection the first time you wont need to repeat this process.


link to clone UAD//    gh repo clone 0x192/universal-android-debloater


link to clone F.Droid //   gh repo clone f-droid/fdroid-website
