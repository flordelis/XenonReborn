# XenonReborn

The main goal of this project is to offer a basic framework to implement an old school shoot-them-up game. 
Rookies can practice algorithm and basic Java programming to acquire developement skills.

This framework is based on LibGDX and runs only on a desktop computer (Java SE 8) until now.

"XenonReborn" is a classic gradle generated by the LibGdx config tool.

Here is how the v0.1.8 looks like (Youtube) (just click on the image to launch the video)

[![Xenon_Reborn_Capture v0.1.8](http://img.youtube.com/vi/ki39sbk4VKc/0.jpg)](https://youtu.be/ki39sbk4VKc)

## How to build

Clone the project (git clone).

Then enter the directory, then type :

- on linux `$ ./gradlew run`
- on windows `> gradlew run`

## IDE Integration

### Eclipse

- Import project as a gradle project. Let everything as default and click finish.
- Then open the "desktop" project in the project explorer.
- Open the "src" folder, then the "fr.fxjavadevblog.xr" package
- Right-click on the "Launcher.java" class, then "Run as Java Application".

### IntelliJ

- Import project as a gradle project. Let everything as default and click finish.
- Then open the "desktop" project in the project explorer.
- Open the "src" folder, then the "fr.fxjavadevblog.xr" package
- Right-click on the "Launcher.java" class, then "Run Launcher.main()".


## What's technicaly inside ?

- MVC paradigm
- Screen management and fade-in / fade-out transition (coded from scratch)
- Central assets management and loading, through enum
- Smooth random background scrolling on the menu screen
- Object states and polymorphism on every stage of the software design
- Sprite collision oded from scracth based on bounding circles
- Music playing an old format (Amiga and Atari-ST Mod format) which is very tiny compared to MP3
- Parallalax scrolling on the game screen
- Java 8 lambdas and method references.
- etc.

## Code reviews

- 0% issues in Codacy.
- All files rated A in Codefactor.
- Average methods per class : 10 
- Average LoC per class : 4
- Lines of code : 3813
- Nb of classes : 66 (only)
