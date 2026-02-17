# Track 1: Logistics Picking

## Overview

This task simulates warehouse logistics picking. The system must transfer items from shelves at multiple heights to a transport vehicle within a fixed time limit, demonstrating speed, reliability, and careful handling across varying reach requirements.

## Task Rules

Transfer items from shelves to a transport vehicle in the unloading area within the time limit.

- **High shelves** — upright-reach transfer
- **Low shelves** — bent-reach transfer
- **Ground shelves** — ground-level transfer

There is no limit on the number of items transferred per operation, but items must not fall to the ground.

## Bill of Materials

<!-- TODO: Add consumables and materials list -->

For detailed procurement links, see [`bom/bom.md`](bom/bom.md).

### 3D-Printed Parts

STL files are in [`stl/`](stl/). Source CAD files are in [`cad/`](cad/).

<!-- TODO: List printed parts if any -->

## Scoring

| Criterion | Description |
|-----------|-------------|
| **Time Efficiency** | Number of items transferred within 10 minutes; minimum time per individual transfer |
| **Quality Standard** | Success rate of picking from shelves; number of drops during transportation |

For the detailed rubric, see [`scoring/scoring.md`](scoring/scoring.md).

## Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | *TODO* |
| Teleop Demo | — | *Coming soon* |
