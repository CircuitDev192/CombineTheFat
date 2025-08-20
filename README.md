# Combine The Fat

A Vintage Story mod that patches the "Cut The Fat" mod to add fat recombining functionality and standardize cutting yields.

## Description

This mod requires "Cut The Fat" and patches the crafting recipes to make two key improvements. If you've played with Cut The Fat, you've probably experienced getting stuck with only cut fat pieces when you need whole fat chunks for certain recipes like fruit presses. This mod solves that problem while also improving the cutting consistency.

### About Cut The Fat (Original Mod)

The "Cut The Fat" mod allows you to use a knife or cleaver to cut chunks of fat into smaller pieces. These pieces can be used for most recipes, including oil lamps, sealing crocks, and oiling hides, though crafting machine parts still requires full chunks. The pieces can be placed on the ground, on tables, and on shelves. While pieces make crock sealing and oil lamps more resource efficient, oiling hides has about the same efficiency but allows you to oil smaller batches without consuming an entire chunk. Originally, using a knife gives 3 pieces while a cleaver gives 4.

## Features

- **Recombine Fat Pieces**: Put 4 fat pieces back in the crafting grid to get a whole fat chunk (shapeless recipe)
- **Standardized Cutting Yields**: Both knife AND cleaver now give 4 pieces (instead of knife=3, cleaver=4)
- **Shapeless Crafting**: The recombining recipe works in any arrangement - no specific pattern required

## Screenshots

![Screenshot 1](pic1.png)

![Screenshot 2](pic2.png)

![Screenshot 3](pic3.png)

![Thumbnail](thumbnail.png)

## Installation

1. Download the mod file
2. Place it in your Vintage Story `Mods` folder
3. Ensure you have the "Cut The Fat" mod installed (required dependency)
4. Launch Vintage Story

## Requirements

- **Vintage Story** (compatible version)
- **Cut The Fat mod** (required dependency)

## Technical Details

This mod uses JSON patches to modify the existing fat cutting recipes from "Cut The Fat":
- Adds a new shapeless recipe to combine 4 `fat-cut` items into 1 `fat` item
- Patches both knife and cleaver cutting recipes to yield 4 pieces each (standardizing the output)

## Author

**CircuitPwne**

## Repository

[GitHub Repository](https://github.com/CircuitDev192/CombineTheFat)

## Version

1.0.0

## License

This mod is created for the Vintage Story community. Please check the repository for license details.