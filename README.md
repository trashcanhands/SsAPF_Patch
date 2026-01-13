If you use the original ModShardLauncher: <br>
Download Autopathfinder_Patch.zip, install the mod as usual using the .sml file. <br>
If you use ModShardLauncher-Enhanced: <br>
Download Autopathfinder_Standalone.zip. <br>
You can either install normally using the .sml file, or you can compile the mod yourself using the Autopathfinder_Standalone folder in the .zip file. <br>
<br>
ModShardLauncher-Enhanced: The pathfind key is F3 by default, but compiling the mod yourself allows you to choose the hotkey by editing the line in AutopathfinderStandalone.cs and building the project. <br>
(C# editor/compiler required. Just use Visual Studio). <br>

1. Place Autopathfinder_Standalone folder in the ModSources folder in your ModShardLauncher-Enhanced directory. <br>
2. Launch ModShardLauncher-Enhanced, and click the <C#> button. <br>
3. Click COMPILE on Autopathfinder_Standalone <br>
4. Click the Anvil button and install the new mod as you normally would. <br>
<br>
Note: One caveat with MSL-E that I could not get around is getting continuous pathfinding to work, so you will have to hit your pathfind hotkey again each time you transition to a new tile. 
