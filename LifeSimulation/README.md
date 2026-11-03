# Life Simulation

A 2D grid-based life simulation built in Unity. You place different cell types on a grid, press Start, and the simulation evolves them over generations.

## Structure

- `Assets/Scripts`: simulation logic (`Manager.cs`, `GridScript.cs`, `Functions.cs`, `PixelDensityCamera.cs`)
- `Runnable.x86_64` and `Runnable_Data/`: a prebuilt Linux binary

## Running

**Prebuilt (Linux):**

```bash
chmod +x Runnable.x86_64
./Runnable.x86_64
```

**From source:** open the folder in **Unity 2019.3.8f1** (or a compatible 2019.3.x version), load the main scene and press **Play**.
