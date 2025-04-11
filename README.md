# Fujifilm Recipes

This repository contains various Fujifilm Recipes.

The file format is an `XML` with version ending `FP1`. This is Fujifilms own file format for recipes (at-least for the X-T50).

The recipes are separated for each camera and also weakly grouped together based on arbitrary topics / schemes. Sometimes the topics are explained in a `README.md` file in the main recipe directory.

The Recipes have to be modified (Serial Number, etc.) before copying to the camera (see below).

## Directory Structure

- Camera
  - Category / Group
    - Recipe.FP1
    - \[Readme.md\]

## Importing to a Camera

1. Change `device`, `version` in `PropertyGroup`, also change `SerialNumber` and `TetherRAWConditonCode`
1. _Maybe_ also change `StructVer` and `IOPCode` _(not tested)_
1. Copy all recipes to the corresponding folder in **FUJIFILM X RAW STUDIO** (`C:\Users\??\AppData\Local\com.fujifilm.denji\X_RAW_STUDIO` on Windows)
1. Copy them inside the studio to the camera

## Licensing

Everything without any License Information or Reference to another Author is released under the [MIT License](./LICENSE).

Because a lot of Recipes are from [Fuji X Weekly](https://fujixweekly.com), check the License files thoroughly in each directory before releasing elsewhere.

Because all recipes are publicly available on, I hope that this repo won't cause any problems, but I will remove any recipes if the original authors wish so.

## Guarantees

As I can only test the files on my camera (X-T50), I can't give any guarantees if they also work on other cameras, other versions or just in general any different setup than mine.

If someone has a similar setup and experiences some problems, they are free to create an Issue and I try to help as much as possible.
