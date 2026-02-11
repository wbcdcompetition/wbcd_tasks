# Track 2: Logistics Packing

> **Robot:** Galaxea R1 · **Sponsor:** Galaxea

## Overview

This track focuses purely on stationary packing. It simulates a clean packing scenario where the robot needs to efficiently transfer items from a moving conveyor system to designated packing containers.

## Robot Platform

| Item | Details |
|------|---------|
| Robot | Galaxea R1 (or similar) |
| End Effectors | <!-- TODO --> |
| Control Method | <!-- TODO --> |

## Task Definition

The robot picks items from 10 moving bins on a conveyor belt and organizes them in a target packing bin.

### Picking Environment

- 10 picking bins move along conveyor at controlled speed
- Each bin contains identical items
- Items vary between bins (shape, size, weight)
- Time limit per bin at picking point

### Packing Options

| Option | Description |
|--------|-------------|
| **Standard** | Rigid plastic container as packing bin |
| **Advanced** | Cardboard box with additional box closure requirement |

## Workspace Setup

<!-- TODO: Add conveyor layout, bin dimensions, and workspace photos to media/ -->

## Consumables & Materials

See [`bom/bom.md`](bom/bom.md) for the full bill of materials.

<!-- TODO: Specify bin dimensions, conveyor specs, item types -->

## 3D-Printed Parts

<!-- TODO: Add any fixture STLs to stl/ -->

## Scoring

See [`scoring/scoring.md`](scoring/scoring.md) for the detailed rubric.

### Summary

| Criterion | Description |
|-----------|-------------|
| **Time Efficiency** | Total picking time (cumulative for 10 items); total packing time (cumulative for 10 placements) |
| **Quality Standards** | Items stacked tightly and neatly, not exceeding bin height; for advanced version, cardboard box must be properly sealed |

## Reference Media

<!-- TODO: Add sample test scene photos/videos to media/ -->

## Awards

| Place | Prize |
|-------|-------|
| 🥇 1st | Professional robot from Galaxea (~$50,000–$60,000 value) |
| 🥈 2nd | $10,000 USD |
| 🥉 3rd | $5,000 USD |
