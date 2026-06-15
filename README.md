# flexytrack
# FlexyTrack  FlexyTrack is a Blender extension that automatically applies chained Damped Track constraints from the active bone through its descendants.  It is designed for simple bone chains and physics-free motion control.
## Features

- Automatic Damped Track chain generation.
- Influence falloff across the full chain.
- Linear, Exponential, and Constant modes.
- Built-in presets for common rig behaviors.
- One-click cleanup of generated constraints.

## Requirements

- Blender 4.2 or later.

## Installation

1. Download the `.zip` file from Blender Extensions or GitHub.
2. In Blender, go to **Edit > Preferences > Extensions**.
3. Click **Install from Disk**.
4. Select the FlexyTrack `.zip` file.
5. Enable the extension.

## Usage

1. Select your armature.
2. Go to **Pose Mode**.
3. Select the root bone of the chain.
4. Make sure it is the active bone.
5. Open **View3D > Sidebar > FlexyTrack**.
6. Choose a falloff mode or preset.
7. Click **Apply Damped Track**.

## Presets

- **Fish**: good for fish-like or tail motion.
- **Octopode**: softer progressive motion.
- **Rope**: constant influence across the chain.

## Support

If you find a bug or need help, please open an issue here:

(https://github.com/Meltingman-melting3d/flexytrack/issues) 

## Website

https://melting3D.org

## License

GPL-3.0-or-later
