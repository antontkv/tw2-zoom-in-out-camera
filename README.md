# The Witcher 2: Zoom In/Out Camera

This mod allows you to move the camera closer or farther from Geralt. This changes all camera instances: meditation camera, fistfight camera, and combat camera.

## Installation

Copy CookedPC into the Witcher 2 install directory, overwriting existing files.

Add these lines to the `User.ini` file in `Documents\Witcher 2\Config\`:

```
[ZoomCamera]
CameraInOut=0.0
```

Change this value to whatever you like. Negative values move the camera closer, positive - farther. The vanilla value is 0.0.

Since `base_scripts.dzip` is modified you need to merge script files if you use other mods that change this dzip. Use [Gibbed RED Tools With UI](https://www.nexusmods.com/witcher2/mods/1027) to unpack/pack `base_scripts.dzip` and programs like WinMerge to merge files. To see what was changed in which files visit [GitHub repo](https://github.com/antontkv/tw2-zoom-in-out-camera).
