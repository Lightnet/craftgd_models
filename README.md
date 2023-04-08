
# Status:
 * work in progress.

# Information:
  Prototype characters, props and other models.

  For Godot 4.0.1

  Just for game build.

# Assets:
 * 

# Blender:

 * Version 3.4.1

  Note that blender export to gltf required some set up for materials to get Godot 4 to work. Reason is that set up for toon anime toon material does not work. It either out date or not config for godot only the VRM for export.
  
  It has be use the default blender default set up for shader and material.

## Notes:
 * VRoid does work when export to Godot 4. Missing materials.
 * Rigging IK has some bugs for auto rig pro. Need to disable modifier. Else the model disappear and only face model.
   * Display modifer real time disable all.
 * Animation export does not work on 3.4.1 and 3.5.x for me. Work on 3.6.x build.
  * Use github blender gltf to get the latest version for the plugin.

## Plugins:  
  * VRM blender Plugin Import (Update)
  * Cats Blender Plugin (Outdate)
    * Materials is broken as see black texture when fixed button.
  * Node Wrangler (Disable by default)
    * Need for set up to export to godot 4 to config material and shader settings.
