# GoreLab

> [!WARNING]
> **Content Warning:**
> This software contains intense gore, graphic violence, body horror elements, and disturbing scenes.

[![Latest Release](https://img.shields.io/github/v/release/nknnt/gorelab)](https://github.com/nknnt/gorelab/releases)

### Features:
- Built with C# / .NET 7.0 using Windows Forms (WinForms)
- Dynamic limb interaction
- Bleeding particles
- Customizable body positioning
- Real time gore effects
- Experimental sandbox support
- This project is still under active development and is continuously being updated. (project ASH)

### Asset Requirements

The GoreLab loads character assets from external `.png` files.
Place the following folders in the same directory as the executable:

- `character/`
  - `arm_l.png`
  - `arm_r.png`
  - `foot_l.png`
  - `foot_r.png`
  - `hand_l.png`
  - `hand_r.png`
  - `head.png`
  - `head_hurts.png`
  - `thigh_l.png`
  - `thigh_r.png`
  - `torso.png`

- `wound/`
  - `1.png`
  - `2.png`
  - `3.png`
  - `bruise1.png`
  - `bruise2.png`
  - `bruise3.png`

If the required assets are missing, 
the GoreLab will fall back to a simple block character rendered in C#.
These assets are required for the intended experience.

### Screenshots

<img src="screenshots/GoreLab_Preview.png" width="600">
+ Note: The screenshot has been intentionally blurred.

It uses custom assets created for this project, and those assets are not included in the repository.
