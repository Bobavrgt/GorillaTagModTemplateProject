# GorillaTagModTemplateProject ([ORIGINAL](https://github.com/Graicc/GorillaTagModTemplate))

## Template INFO:
- Plugin.cs: The main class of your mod. Most of your code should go here.
- PluginInfo.cs: This holds information about your plugin in a central location. This is where the plugin name, id, and version are stored.
- HarmonyPatches.cs: This handles the application of harmony patches (such as ExamplePatch). You shouldn't need to modify this class.
- Patches/ExamplePatch.cs: This demonstrates how patches are created, you should remove or modify it as you see fit.
- MakeRelease.ps1: This script generates a MonkeModManager compatible release (named ModName-v.zip). You should use this to create builds that you share with others.
- Directory.Build.props: This file contains information about where dependencies are located. If you are getting CS024 (type could not be found) errors, GamePath is probably wrong.

## CHANGE LOG FROM GRAICC'S
- The only thing I changed is adding Newtilla support instead of utilla and netstandered2.1.

## DO NOT DO ANY OF THE FOLLOWING:
- Do not put spaces in the project name, as it will prevent the mod from loading.
- Do not remove ANY references unless you are replacing it with better ones.

## DISCALMER:
This product is not affiliated with Another Axiom Inc. or its videogames Gorilla Tag and Orion Drift and is not endorsed or otherwise sponsored by Another Axiom. Portions of the materials contained herein are property of Another Axiom. ©2021 Another Axiom Inc.
