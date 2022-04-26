# Augmed_AR
AR Mobile app to facilitate learning. Created with Unity (C#) and Vuforia Engine.

Immediate improvements to current project: 
- Better image targets, enhance reliability
- Import packages that allow touch manipulation (scaling, rotating, transforming) of models (eg: LeanTouch Unity package)

[Video Demo Link](https://youtu.be/-fiORR8tJZE)

1. Clone project (1 missing file: Packages/com.ptc.vuforia.engine-10.6.3.tgz - I will add when GitLFS is installed.)
2. Open project in Unity editor
3. Change build settings to whichever mobile platform you want to build on. (I have built on iOS)
4. (for iOS): build and run on xcode, ensure apple developer account is set up to build app on iOS device.
5. Enable trust of 'this' developer in general settings on apple device, then app can run
6. Ensure to click ‘yes’ for all permissions the app requests upon launch.
7. Point camera and the respective image targets in the digital textbook. 
8. Enjoy! :D
