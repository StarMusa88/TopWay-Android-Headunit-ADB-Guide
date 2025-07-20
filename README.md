# TopWay-Android-Headunit-ADB-Guide
2 Options Guide On how to wirelessly Connect Top Way Ts10 Android Head unit using ADB Commands (non-root) and using U.A.D ( Universal Android Debloater) to debloat the Head Unit from unwanted system applications. (((USE AT YOUR OWN RISK)))

Option: 1

1- First we need to connect to WIFI and enable developers option.(7890+current time using 24 hour format) >> use code 7890 plus current time for example if the current time is 8:00 PM you type in 789020 << 

2- Then we need to enable USB Debugging (john@tw-desktop) is the code for Topway TS10 android 10 model. Next we need to install F.Droid application. From F.Droid we need to install Termux and Terminal Emulator. Now that we have all our applications installed (make sure to update each application after install) we will begin with opening Terminal Emulator and typing (setprop service.adb.tcp.port 5555) and press enter.

3- Next we open Termux and install android-tools >>// pkg install android-tools \\<< we then type in the command ( adb ) to see if the adb command is working. 

4- Finally to connect wirelessly to your HeadUnit we will type in the Termux Terminal (adb devices) and you should see a pop-up screen asking you to Allow from this computer press on (Allow). 

5- To connect from your PC or Laptop using powershell enter ( adb connect 192.xx.xx.xx:5555 )  your HeadUnit IP address. you can find your IP address by going into settings to  >> about phone > status //and your Headunits IP address should be listed.

6- Once you have established a successfull ADB connection with your headunit you can now use Universal Android Debloater from your PC or Laptop by using step 5 in the guide.

Note: If you restart the HeadUnit you must repeat this process.

Option: 2

1- Go to Factory settings enter the Passcode (123456)

<img width="1280" height="720" alt="unnamed" src="https://github.com/user-attachments/assets/a9cc5f4e-d59e-46a3-962b-587b4937bf1d" />

2- Go to Engineer Mode


3- Go to Debug&Log go to ADB shell 

<img width="1280" height="720" alt="unnamed (5)" src="https://github.com/user-attachments/assets/a1eed0aa-fbfe-44fa-9d9e-b48274a23445" />


4- Type "setprop service.adb.tcp.port 5555" and Press Start.

<img width="1280" height="720" alt="unnamed (4)" src="https://github.com/user-attachments/assets/007ae2b5-39e9-4879-baad-e2c9966c6203" />


5- Go  and Turn on USB Debugging

<img width="1280" height="720" alt="unnamed (6)" src="https://github.com/user-attachments/assets/10d4c4d9-8b40-4116-902e-02c58478c6f0" />



6- Go to Termux terminal and enter adb devices -l.

<img width="1280" height="720" alt="unnamed (2)" src="https://github.com/user-attachments/assets/a80c97bd-2e90-44a0-a67d-22605244d4c2" />

7- You should see your headunit listed.

<img width="1280" height="720" alt="unnamed (1)" src="https://github.com/user-attachments/assets/825df2a4-5b93-4990-bc26-39be28fed800" />






link to UAD//   https://github.com/0x192/universal-android-debloater.git  or Newer version https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation.git


link to F.Droid //   https://github.com/f-droid/fdroidclient/releases/download/1.18.0/org.fdroid.fdroid_1018050.apk


