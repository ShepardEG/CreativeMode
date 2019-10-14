Creative Mode (edited by Sarah and Cynthia)
=============


### Features

- Spawn Vehicles, Defences, Characters, Weapons
- God mode, fly mode, walk mode, destroy defences, promote
- CLI commands: respawn defences, toggle player spawn

## How to build
- Extract Creative Mode files into SDK root. 
- Navigate to the SDK's /UDKGame/Config/ directory, and open DefaultEngineUDK.ini. Navigate to the UnrealEd.EditorEngine section in the file, and at the bottom of the section add: ` +ModEditPackages=MyPackage`
- Now you need to compile your mutator. Simply create a compile.bat file, then write and save the following contents to it: ` start /Binaries/Win32/UDK.exe make`
- Resultate of compilation will be on `UDKGame/Script/Rx_CreativeMode.u`

## How to install 
- Copy directory `UDKGame` into RenegadeX root folder, agree with replacement files. 
- Copy builded Rx_CreativeMode.u in `UDKGame/CookedPC`
- Run local server or skirmish map with loading mutator. Example: `open CNC-Field?mutator=MyPackage.MyMutator`

[Original repo show on the link](http://https://github.com/sevans045/CreativeMode/ "Original repo show on the link")

