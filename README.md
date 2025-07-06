# 🚲 BikeGrabber - LSPDFR Plugin

**BikeGrabber** is a lightweight plugin for [LSPDFR](https://www.lcpdfr.com/lspdfr/) using RagePluginHook that allows officers to grab a bicycle from specific vehicles during patrol, and return it when done.

---

## 🎯 Features

- ✅ Press a configurable key (default: `E`) to grab a bike from a nearby vehicle.
- ✅ Spawn a custom bike model behind your character (default: `bmx`).
- ✅ Return near the bike and press the same key to "put it back" (deletes it).
- ✅ Fully configurable via an `.ini` file.
- ✅ Designed for immersion, utility, and simplicity.

---

## 🛠️ Installation

1. Download and extract the `.zip`.
2. Place the following files into your `GTA V/Plugins/LSPDFR/` directory:
   - `BikeGrabber.dll`
   - `BikeGrabber.ini`

3. Launch your game via **RagePluginHook**.

---

## ⚙️ Configuration (`BikeGrabber.ini`)


[Settings]
GrabKey=E           ; Key used to grab/return bike
BikeModel=bmx       ; Model to spawn (e.g., bmx, scorcher, cruiser)

[BikeVehicles]
Models=sultan,baller4,landstalker2  ; Vehicle models that allow bike interaction
