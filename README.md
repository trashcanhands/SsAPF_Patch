If you use the original ModShardLauncher: 
Download Autopathfinder_Patch.zip, install the mod as usual using the .sml file.
If you use ModShardLauncher-Enhanced: 
Download Autopathfinder_Standalone.zip. 
You can either install normally using the .sml file, or you can compile the mod yourself using the Autopathfinder_Standalone folder in the .zip file.

ModShardLauncher-Enhanced: The pathfind key is F3 by default, but compiling the mod yourself allows you to choose the hotkey by editing the line in AutopathfinderStandalone.cs and building the project.
(C# editor/compiler required. Just use Visual Studio).

1. Place Autopathfinder_Standalone folder in the ModSources folder in your ModShardLauncher-Enhanced directory.
2. Launch ModShardLauncher-Enhanced, and click the <C#> button.
3. Click COMPILE on Autopathfinder_Standalone
4. Click the Anvil button and install the new mod as you normally would.

Note: One caveat with MSL-E that I could not get around is getting continuous pathfinding to work, so you will have to hit your pathfind hotkey again each time you transition to a new tile. 
