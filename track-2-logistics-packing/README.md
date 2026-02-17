# Track 2: Logistics Packing

## Overview

This task simulates stationary packing in a logistics environment. The system must pick items from moving bins on a conveyor belt and organize them into a target packing container, demonstrating efficient and precise pick-and-place capability.

## Task Rules

Pick items from 10 moving bins on a conveyor belt and organize them in a target packing bin.

### Picking

- 10 bins move along the conveyor at a controlled speed
- Each bin contains identical items
- Items vary between bins (shape, size, weight)
- Time limit per bin at the picking point

### Packing Options

| Option | Description |
|--------|-------------|
| **Standard** | Rigid plastic container as packing bin |
| **Advanced** | Cardboard box with additional box closure requirement |

## Bill of Materials

<!-- TODO: Add consumables and materials list -->

For detailed procurement links, see [`bom/bom.md`](bom/bom.md).

### 3D-Printed Parts

STL files are in [`stl/`](stl/). Source CAD files are in [`cad/`](cad/).

<!-- TODO: List printed parts if any -->

## Scoring

| Criterion | Description |
|-----------|-------------|
| **Time Efficiency** | Total picking time (cumulative for 10 items); total packing time (cumulative for 10 placements) |
| **Quality Standard** | Items stacked tightly and neatly, not exceeding bin height; for advanced option, cardboard box must be properly sealed |

For the detailed rubric, see [`scoring/scoring.md`](scoring/scoring.md).

## Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | *TODO* |
| Teleop Demo | — | *Coming soon* |
