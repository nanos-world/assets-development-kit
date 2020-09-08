# nanos world ADK (Assets Development Kit)

nanos world provides an Unreal Engine 4 project which can be used to improve your Assets Creation pipeline, which contains:

* Base Character's **Skeletal Mesh** (based on UE4's Mannequin) which must be used in order to create custom Characters for nanos world.
* Several **Physical Materials** which can be used in your custom Materials to integrate natively with nanos world (Physical Materials are used for determining the kind of a mesh's surface - for example if it's a metal, it'll cause metal sounds on footsteps, on bullet hits and if it's a prop, it's prop's hit sound).
* **Placeholders** for setting Vehicles and Weapons spawn positions. Which can be used together an **Utility Blueprint** to generate a .lua script with all Weapon's and Vehicles spawns commands.
* **Utility Blueprints** to help the workflow:
  * *WBP_NanosEditorUtility* can be used for mass file editing and renaming.
  * *WBP_NanosMapCookEntities* can be used for generating a Lua script with all Props, Weapons and Vehicles spawn locations for your map.
  * *BP_NanosSunLibrary* can be used to determine if it's day or night, which can be used in Light Poles to automatically turn them on/off.
* A customized **Sun Blueprint** (*BP_SunSky*) which is very similar to the one used in-game, which can be used if you want to `World:SpawnDefaultSun()`.