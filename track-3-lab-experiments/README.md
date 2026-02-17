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

| | Item | Qty | Unit Price (CNY) | Supplier |
|:---:|------|:---:|---:|------|
| <img src="media/2ml_sample_vial.jpg" height="80"> | 2 mL Sample Vial | Per setup | 0.4 | [Taobao](https://item.taobao.com/item.htm?id=17615677498) |
| <img src="media/2ml_sample_vial_rack.jpg" height="80"> | 2 mL Sample Vial Rack | 1 | 120 | [Taobao](https://item.taobao.com/item.htm?id=710110090808) |
| <img src="media/8ml_glass_vial.jpg" height="80"> | 8 mL Glass Vial | Per setup | 1.5 | [Taobao](https://item.taobao.com/item.htm?id=19991893535) |
| <img src="media/8ml_glass_vial_rack.jpg" height="80"> | 8 mL Glass Vial Rack | 1 | — | In-house stock |
| <img src="media/1Lsolvent_bottle_tube_cap.png" height="80"> | 1 L Solvent Bottle | 2 | 20 | [Tmall](https://detail.tmall.com/item.htm?id=869789079507&skuId=5701565429700) |
| | Flexible Tubing + Filter Head | 1 set | 100 | [Tmall](https://detail.tmall.com/item.htm?id=956086151290&skuId=6049729811075) |
| | Spare Bottle Cap | 2 | 8 | [Tmall](https://detail.tmall.com/item.htm?id=869789079507&skuId=5762711841749) |

### 3D-Printed Parts

Printable STL and source CAD files are in [`parts/`](parts/).

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

## Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | *TODO* |
| Teleop Demo | — | *Coming soon* |
