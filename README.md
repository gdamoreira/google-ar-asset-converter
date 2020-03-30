Google ARCore Asset Converter
=====================

## Future from this repo
After Google [released the 1.16.0 version](//github.com/google-ar/sceneform-android-sdk/releases/tag/v1.16.0%C2%A0) of the Sceneform they deprecated SFB and SFB Android Studio Plugin. They are adopting the use of GLTF format instead of the SFB.

`Deprecates support for SFB & the SFB Sceneform Android Studio plugin (glTF can be used instead).`

Facing this new reality I'm going to not do any update in this repo anymore.

## License

Sceneform SDK for Android
=====================
Copyright (c) 2018 Google Inc.  All rights reserved.

Sceneform is a 3D framework, with a physically based renderer, that's optimized for mobile, and that makes it easy for Java developers to build augmented reality apps.

Please note, we do not accept pull requests.


## Getting Started

This repository contains Sceneform binaries to generate .SFA and .SFB files to import on any ARCore projects.

## Generating assets

    $ ./sceneform_sdk/linux/converter -a -d --mat ./sceneform_sdk/default_materials/obj_material.sfm --outdir ./output/ ./input/andy.obj


## API Reference

See the [Sceneform API Reference](//developers.google.com/ar/reference/java/com/google/ar/sceneform/package-summary).


## Terms & Conditions

By downloading the Sceneform SDK for Android, you agree that the [Google APIs Terms of Service](//developers.google.com/terms/) governs your use thereof.

## Converter and Matc Arguments

To see the single available arguments call

```
./converter -h
```
or
```
./matc -h
```
repectively.
