# ObvrWidgetLibrary

*Collection of remakes of Oblivion Remastered's UI prefab widgets for mod UIs.*  

---

This repository contains recreations of the original UI widget prefabs with asset dummy's (the original textures and materials load only in game).
Someone may eventually figure out how to create functional dummy's of the original navigable prefabs, till then having an alternative is nice!

⚠️ **Note:** *No original game assets (textures, meshes, or code) are included in this repository.*

This project is **NOT** associated with Bethesda, Zenimax, Virtuos or any of their subsidiaries!

---

## Library Preview
![Widget Library Showcase](/Docs/Library.png "Widget Library Preview")

---

## 🛠️ Usage Instructions

1. **Clone/Download** the repository.
2. In Unreal Engine:
   - Right-click the desired widget(s) in the Content Browser.
   - Select **"Migrate"** and choose your project's Content folder.
3. **Move the migrated widgets** to your mod's directory in engine, and include them in your pak chunk.
5. ⚠️**Do not include the dummy textures or materials in your pak chunk, or they wont render properly in game**!

**Example:**
`Content/Mods/YourMod/WidgetsGoHere`✅ | `Content/Mods/YourMod/LibaryStuff`✅ 
**include the library stuff folder in your chunk** as well (can be renamed to whatever directory you want)

⚠️ All the other textures and folders must retain their original directories ie Art/UI/etc...
In game the original textures will automatically take their place as long as you **don't** include the ms-paint versions in your pak chunk!

Migrating a widget to your project will only take the required textures and materials with it

---

### If you would like to contribute to this library
- **Option 1:** DM **@pumpkinbites** on Discord.
- **Option 2:** Create a pull request with your widget prefabs added to the project.
