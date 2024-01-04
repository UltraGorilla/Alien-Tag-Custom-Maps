# Alien-Tag-Custom-Maps
How to make Alien Tag Custom Maps!



1. Open project with Unity 2023.2.1f
2. If there is no scene open you should open mainscenme (in folder "Scenes")
3. Under hierarchy you should see two gameobjects (Directional Light and map)
4. Import your assets (models, materials etc) under Graphics folder
5. Make sure when putting objects in hierarchy that you put them under "map" object
6. Your objects should be tagged "static" so light can bake.
   You can do this when you select object and there is static checkmark in upper right corner.
7. Select your object and find "mesh renderer" component on your right under inspector.
   Click "add component" and add component called "mesh collider".
8. When ready to export first you have to select "map" gameobject under hierarchy
   You should see "overrides" on your right and apply them all.
9. Then you have to right click Assets then click Bake Prefab Lightmaps
10. After that's done right click Assets/ then click Build Asset Bundles
11. When that's done you should see "Streaming assets" folder under "project"
    Right click on it and "Show in explorer". Select "android" and "windows" folders and zip them together.
12. That zip now can be uploaded to https://mod.io/g/alientag


Vid Tutorial:
https://www.youtube.com/watch?v=nq82uMEairU&t=7s

Google Doc:
https://docs.google.com/document/d/1_ZoIMMyF4NMpwmM6lkO7xpjlvx0k9TZbJlZQdlgT7cA/edit

Mod.io:
https://mod.io/g/alientag

Map Template:
drive.google.com/file/d/1PTNZVFiUDbbt8JZNh_b743F1IR31q1ut/view
