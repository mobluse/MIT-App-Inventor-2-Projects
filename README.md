# MIT App Inventor 2 Projects
Hippocampus Game for MIT App Inventor 2 for Android  
http://ai2.appinventor.mit.edu/?galleryId=5803489607548928  
APK is included, and pictures of the app and the source code.

This app lets the user play a clone of Brain Game (a.k.a. Simon) using text 
on the buttons and by pressing the buttons 1-4. The goal is to emulate the 
Velleman MK112. First press 1 or 2 to start and select sound or mute, 
respectively. Then press one of 1-4 to select level. Higher level gives 
longer maximum sequence to repeat. The Android device plays a sequence. 
Repeat the sequence by pressing the buttons on screen. The sequence, 
increased by one, is then played. Repeat. Eventually you will win, or 
make a mistake or timeout and loose. You will be celebrated or mocked, 
and the game is restarted, and you select sound or mute again.

##Development
It was developed in Chrome on Windows 10 using http://appinventor.mit.edu/
and the included Android emulator. I also used Bash on Ubuntu on Windows
using ADB, e.g. `adb logcat | sed '/System\.err/d'` in order to filter out
unimportartant information from the Android log, and to find files using
`find`. I used the Swedish translation of MIT App Inventor 2. If you
want to remix use the aia-file, and upload it in App Inventor.
