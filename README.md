# Keybind Layouts (Fabric, Minecraft 26.1.2)

Adds `[1] [2] [3]  Save  Load` buttons (top-left) on Options > Controls > Key Binds.
Pick a layout number, press Save to store your current keybinds, Load to restore them.
Layouts are stored in `.minecraft/config/keybind_layouts.json`.

## Build the jar
Needs JDK 25 and Gradle 9.4.1.
    gradle build
Jar: `build/libs/keybind-layouts-1.0.0.jar` (NOT the -sources jar)

Or push this folder to a GitHub repo: Actions tab > build > download the artifact.

## Install
Fabric Loader 0.19.2+, Fabric API 0.155.2+26.1.2, put the jar in `.minecraft/mods/`.
