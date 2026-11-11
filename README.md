# Totem Grader

A Fabric mod for Minecraft 1.21.1.

## Features

- Totem Grader items can be found in End City treasure chests.
- Craft a Semi-Grade Table with a Smithing Table, Blackstone surrounding it, and a Diamond above the center.
- Upgrade a Totem of Undying using one Totem Grader and one Netherite Ingot.
- Graded Totems begin with 2 uses and can be upgraded one use at a time to 10 uses.
- The item name and tooltip show the current uses. At 10 uses, the table reports `You hit the limit!`.
- Higher uses have progressively stronger eye shimmer model predicates for resource packs.

## Build and install

Install Java 21. Run `./gradlew build`; the mod jar is created in `build/libs`.
Install Fabric Loader 0.16.9 for Minecraft 1.21.1 and Fabric API, then put the jar in the instance's `mods` folder.
