![Hexfinity Logo](./assets/hexfinity-logo.svg)
![Hexfinity Hero](./diagrams/roll-hexfinity-hero2.jpg)

# Hexfinity: Modular Hexagonal Grid System

- [Hexfinity Specification](HEXFINITY.md) Just want the specs? Go here!
- [Roll Hexfinity](ROLL_HEXFINITY.md) The ball rolling system specs
- [Stor Hexfinity](STOR_HEXFINITY.md) The hexagonal storage system specs

## Introduction

Hexagons are the bestagons! If you're here, it's because you love modular systems, you appreciate efficient tiling, and you want to build something with infinite creative possibilities. Welcome to **Hexfinity**, an open-source modular system that combines the best aspects of **ball rolling sculptures** and **hexagonal storage solutions**.

### Tribute to Gridfinity

I'm a huge fan of Zach Freedman's Gridfinity [Gridfinity on Thangs](https://thangs.com/designer/ZackFreedman/3d-model/Gridfinity%20Baseplates-60925) and [Gridfinity on YouTube](https://www.youtube.com/watch?v=ra_9zU-mnl8). I was inspired by his work to create Hexfinity. Now only is Hexfinity inspired by Gridfinity, but it is also designed to be compatible with it - at least as compatible as possible given how square grids and hexagonal grids are different.

### Why Hexagons?

- **Maximum Connectivity**: Hexagons connect to **six** neighbors, whereas squares connect to four and triangles to three. This maximizes the number of inputs and outputs, allowing for more flexible and intricate structures.
- **Efficient Space Usage**: Hexagons offer the **best ratio of area to perimeter** for tiling the plane, making them optimal for compact and efficient storage.
- **Aesthetic Appeal**: Hexagons just look better. They form natural patterns that are visually satisfying and structurally strong.
- **Better Ball Rolling**: More connections mean more pathways for balls to roll, enabling **dynamic, customizable marble runs** that are both fun and engaging.

## The Two Components of Hexfinity

Hexfinity is divided into **two major components**, each serving a unique purpose but built on the same core principles:

### 1. [RollHexfinity](ROLL_HEXFINITY.md) (The Ball Rolling System)

RollHexfinity is designed for creating highly customizable **ball rolling sculptures**. Unlike traditional marble mazes that offer limited configurations, RollHexfinity provides:

- **Modular Hexagonal Bricks**: A small set of core bricks enables infinite configurations.
- **Stackability**: Pieces can be layered while still allowing balls to roll through tunnels.
- **Standardized Ball Size**: Uses **8mm steel bearings**, a popular choice included with **Bambu Lab's Maker Kit**.
- **Controlled Slopes**: Ball paths follow structured height increments of **7mm**, ensuring smooth rolling motion.
- **Compatibility with Gridfinity**: Includes **adapter plates** that allow you to integrate RollHexfinity with the popular Gridfinity system.

### 2. [StorHexfinity](STOR_HEXFINITY.md) (The Hexagonal Storage System)

Hexfinity isn't just for rolling balls—it's also a **storage system** optimized for hexagonal layouts. StorHexfinity provides:

- **Hexagonal Containers**: Available in various sizes, maintaining modularity while maximizing storage efficiency.
- **Flexible Grid Compatibility**: Designed to integrate with square-based storage solutions.
- **Efficient Circular Storage**: Ideal for storing spherical objects (e.g., bearings, marbles, beads) more effectively than square containers.
- **Customizable Dividers**: Allows for custom compartment layouts using **60-degree and 120-degree angles**.

## Roll Hexfinity Technical Specifications

- **Roll channel diameter**: 10mm
- **Recommended ball size**: 8mm steel bearings
- **Entry and exit points**: Balls enter and exit bricks at the center of a side, with the center of the 10mm channel positioned at a multiple of 7mm from the base (e.g., 14mm, 21mm, etc.). For example, the 14mm opening starts at 9mm and extends to 19mm from the base.
- **Path grades**: Ball paths are either flat or descend by increments of 7mm, 14mm, or more. For the standard 21mm bricks, the minimum slope is **7mm over 42mm (17% grade)**.

## Building with Hexfinity

### How to Print

- BambuLab A1Mini/A1/X1/P1 Print-ready profiles are available on [MakerWorld.com/en/@Kanjirevilo](https://makerworld.com/en/@Kanjirevilo)
- Or pick the models ala carte from this repo: [models](./models)

More details on printing:

- **Material Estimate**: A full brick (~21mm tall) weighs ~9g.
- **Recommended Filament**: PLA works great. Wood PLA is a little snug at first, but it gets looser with use. PETG works fabulously.
- **Printer Compatibility**: Designed for FDM printers with a 0.4mm nozzle

### Assembly

- **Stackable Design**: Pieces interlock securely for stable constructions.
- **Tunnel-Friendly**: Tunnels are automatically created when stacking bricks with rolling paths.
- **Flexible Configurations**: Can be combined into long paths, drops, turns, and multi-level structures.

## Future Plans

- **More Adapter Plates**: Expand compatibility between Hexfinity and Gridfinity.
- **Additional Hexagonal Storage Modules**: Customizable dividers for better organization.
- **Hex-to-Grid Interchangeability**: Potential for Gridfinity pieces to sit atop Hexfinity bases.

## Contributing

This project is open-source! If you want to contribute:
1 Fork the repository.
2 Print and test the existing models.
3 Suggest improvements, new designs, or additional modular elements.
4 Submit a pull request!

## License

Hexfinity is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0) License**. This means you are free to use, modify, remix, and share the designs **as long as you provide proper attribution** back to:

1. I prefer you link back to my [MakerWorld.com/en/@Kanjirevilo](https://makerworld.com/en/@Kanjirevilo) profile
2. But, you can also link to this github repo: [Hexfinity](https://github.com/shanebdavis/hexfinity)

And I want to hear about your creations! Add comments on one of my MakeWorld Hexfinity models or here under [issues](./issues)

# Get Started

Print, build, experiment, and enjoy! **Hexagons are the bestagons, and now you can prove it with your own hands.**
