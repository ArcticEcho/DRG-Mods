# Mod Frameworks/Managers
Mods that act as an underlying base of some kind for other mods.

<!-- mod list -->

## BP Mod Manager - v4.3
**Authors:** ArcticEcho  
**DRG Version:** Update 33, Hotfix 9  
**Download Link:** [Download](https://github.com/ArcticEcho/DRG-Mods/raw/440b16704a5e2e627bb93009c9afc73e29841bad/Framework/BP%20Mod%20Manager%20-%20V4.3%20_P.pak)  

**Description:**  
Loads BluePrint mods into the game and provides a simple UI for managing them. Previously known as the mod loader.

**Update v4.3 Changelog:**  
- Fixed a bug that would prevent clients from opening the manager menu after returning to the spacerig. This same bug is also responsible for preventing some mods (Better Post Processing/Dynamic Resolution) from working when joining an already started mission.  
 - Fixed a bug that would cause the escape menu to open if the escape key was pressed while the manager menu was open.  
 - Fixed a bug that would cause the startup notification to silently linger and overlap with other UIs.  
 - Fixed a bug that would reset the scroll position everytime you open the menu.

## Music Control - v1.1
**Authors:** Demellion Dismal  
**DRG Version:** U34+  
**Download Link:** [Download](https://github.com/ArcticEcho/DRG-Mods/raw/9f8b234d7a2b796bbec62bcdad1ac384f2241010/Framework/Music%20Control%20-%20V1.1.zip)  

**Description:**  
A re-created base class tree of sound classes and submixes used by music mods.

**Update v1.1 Changelog:**  
Fixed EndWave music overlapping due to U34 changes.

## Soundclass Heirarchy for Audio Modding - v1.1
**Authors:** Buckminsterfullerene  
**DRG Version:** U34+  
**Download Link:** [Download](https://github.com/ArcticEcho/DRG-Mods/raw/39ffdf728869cfdb3c506ef7c08248a90621b4e0/Framework/Soundclass%20Heirarchy%20For%20Audio%20Modding%20-%20V1.1.zip)  

**Description:**  
The soundclass heirachy for all the sounds in the game. **Do not use if you are _only_ making a music replacement mod. If you are, use SoundClass Heirarchy for Music Modding**. *Note: I am still in the process of automating the process of the soundmix files creation. Mod will be updated when they are ready*.

**Update v1.1 Changelog:**  
Re-added the SoundMixes folder.

## Soundclass Heirarchy for Music Modding - v1.0
**Authors:** Buckminsterfullerene  
**DRG Version:** U34+  
**Download Link:** [Download](https://github.com/ArcticEcho/DRG-Mods/raw/71c6e882ddad8f05bf5b3da2124a808b31985969/Framework/Soundclass%20Heirarchy%20For%20Music%20Modding%20-%20V1.0.zip)  

**Description:**  
The soundclass heirarchy for all music audio in the game. **Do not use at the same time as Soundclass Heirarchy for Audio Modding as it will cause issues in your music mod**. If you are using Music Control framework then replace that, as this is a more up-to-date version.