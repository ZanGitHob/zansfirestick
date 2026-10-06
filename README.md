# Zan's Firestick

This is a fork of Zan's Campfire, a Minecraft 1.10.2 mod. This mod only adds a fire-stick. Yup, a fire-stick. And it may or may not light up a fire. :P

I had this mod built in mind to play alongside Primalcore, which lacks early-game fire ignition method.

---

## Dependencies

Mod Loader: Forge 1.10.2 (12.18.3.2422).

---

## Content

```
zansfirestick:firestick
```

---

## Firestick

Firestick is crafted with 2 sticks in **2x2 shapeless**.
This thing has a 15% likelihood of setting blocks ablaze.

---

## What is inside the JAR?

Fear not, my friend! Nothing harmful is inside.

```
src/main/
├── java/zansfirestick/
│   ├── ZansFirestick.java
│   ├── item/
│   │   └── ItemFirestick.java
│   ├── proxy/
│   │   ├── ClientProxy.java
│   │   └── CommonProxy.java
│   └── registry/
│       ├── ModItems.java
│       └── ModRecipes.java
└── resources/
    ├── mcmod.info
    └── assets/zansfirestick/
        ├── lang/en_US.lang
        ├── models/item/firestick.json
        └── textures/items/firestick.png
```

---

## Installation Guide

1. Download the `.jar` file.
2. Open any ForgeModLoader-ready launcher (preferably MultiMC or PrismLauncher).
3. Drop the file into `mods/` folder in an instance.
4. Open Minecraft.

---

## License
This project is licensed under the [CC0 1.0 Universal](LICENSE) (Public Domain) license - feel free to bundle this into any modpack, modify it, or share it anywhere you like!
