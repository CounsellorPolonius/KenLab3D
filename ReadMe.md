Ken's Labyrinth (with invisible touchscreen controls)
=============

Ken's Labyrinth is a first-person shooter DOS game, released in 1993 by Epic MegaGames (now called Epic Games). It was mostly coded by Ken Silverman, who went on to design the Build engine that was used for rendering a first-person viewpoint in Apogee Software's Duke Nukem 3D. It consists of three episodes, the first of which was released as shareware - [Wikipedia](https://en.wikipedia.org/wiki/Ken%27s_Labyrinth).

## What is this fork? 

I found the on-screen controls to be too distracting. I modified it so that they are invisible. I intend to use this with a gamepad mapper anyways so having the controls invisible works for me.  

You can download APK from the Releases section. 

You can also open this project in Android Studio and build the APK there. You will need to follow these steps however.

## Import to Android Studio
 1. Git clone or download the project and import to Android Studio (used version 2021.3.1 / Dolphin).
 2. Ensure gradle version is correct (build.gradle = 7.3.0). File > Project Structure > Project had the plugin version at 7.3.0 and general version at 7.4.
 2. Download NDK version 21.0.6113669. Versions after this changed the structure so using a more recent version may not work correct. I downloaded it via the SDK Manager but since you'll be manually pointing to it how you download it does not matter. 
 3. Add line to local.properties: ndk.dir=(path/to/NDK/21.0.6113669).
  - For my project the NDK was located in the C:/users/myuser/AppData/Local/Android/NDK folder. 
 4. Build the project. It should now work. 

## Main Changes
 - (XCF, coming soon)
