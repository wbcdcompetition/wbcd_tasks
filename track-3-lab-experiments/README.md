# Track 3: Lab Experiments

## Overview

This task simulates a laboratory automation workflow. The system handles high-density sample racks, interfaces with analytical instruments, and performs reagent bottle operations (threaded caps and flexible tubing). The full task consists of three steps.

## Task Rules

### Step 1: Sample Loading

Pick test samples (e.g., vials or tubes) from a bulk container or array tray and insert them into a high-density sample rack.

- All samples must be seated tightly in place
- No samples damaged or dropped
- Correct positions populated according to the target layout

### Step 2: Instrument Interfacing

Select specified samples from a full sample plate/tray and transfer them into a new tray, simulating interaction with an automated analytical instrument.

- Correct samples identified and placed as required
- Safe, consistent interaction at the instrument interface
- No cross-contamination

### Step 3: Mobile Phase Management

Loosen and tighten threaded caps on solvent bottles (A & B) and relocate flexible tubing from one bottle to another.

- Caps loosened/tightened properly (no stripping, no leaks)
- Tubing switched to the new target position
- Bottles remain upright; no spills

## Bill of Materials

| # | Item | Qty | Specification | Notes |
|---|------|-----|---------------|-------|
| 1 | 2 mL sample vial | Per setup | 2 mL sample vial | Step 1 & 2 |
| 2 | 2 mL sample vial rack | 1 | Rack for 2 mL vials | Step 1 target rack |
| 3 | 8 mL glass vial | Per setup | 8 mL glass vial | Instrument interface |
| 4 | 8 mL glass vial rack | 1 | Rack for 8 mL vials | Source/target tray |
| 5 | Solvent bottle A | 1 | 1 L bottle with threaded cap | Step 3 |
| 6 | Solvent bottle B | 1 | 1 L bottle with threaded cap | Step 3 |
| 7 | Flexible tubing + filter head | 1 set | Tubing assembly | Step 3 tubing switch |
| 8 | Spare bottle cap | 2 | Replacement cap for 1 L bottle | Recommended spare |

For detailed procurement links and pricing, see [`bom/bom.md`](bom/bom.md).

### 3D-Printed Parts

STL files are in [`stl/`](stl/). Source CAD files are in [`cad/`](cad/).

<!-- TODO: List printed fixtures -->

## Scoring

Teams are scored across three dimensions:

| Dimension | Description |
|-----------|-------------|
| **Task Completion** | Were all required actions completed successfully? |
| **Precision & Safety** | No damage, collisions, spills, or cross-contamination |
| **Efficiency** | Total time to complete the task |

### Per-Step Metrics

| Step | Key Metrics |
|------|-------------|
| 1 — Sample Loading | Samples correctly seated; drops; time |
| 2 — Instrument Interfacing | Correct transfers; placement accuracy; time |
| 3 — Mobile Phase Management | Cap integrity; tubing repositioned; no spills; time |

For the detailed rubric, see [`scoring/scoring.md`](scoring/scoring.md).

## Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | *TODO* |
| Teleop Demo | — | *Coming soon* |
