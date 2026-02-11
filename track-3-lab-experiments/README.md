# Track 3: Life Science R&D – Lab Experiments

> **Robot:** AgileX Bimanual Mobile System · **Sponsor:** AgileX Robotics

## Overview

This track simulates a real laboratory automation workflow. The robot handles high-density sample racks, interfaces with an automated analytical instrument, and performs basic solvent/reagent operations (caps + flexible tubing).

The full task is organized into **three steps**. Teams are evaluated on successful execution, precision/safety (no damage, no collisions/spills), and operational efficiency.

## Robot Platform

| Item | Details |
|------|---------|
| Robot | AgileX Robotics mobile bimanual system |
| End Effectors | <!-- TODO: Specify gripper type --> |
| Control Method | <!-- TODO: Specify teleoperation or autonomous --> |

---

## Task Definition

### Step 1: Sample Loading & Seating

**Description:** The robot must pick test samples (e.g., vials or tubes) from a bulk container or an array tray and accurately insert them into a high-density sample rack.

**Success Criteria:**
- All test samples are seated tightly in place
- No samples are damaged or dropped
- Correct positions are populated according to the target layout

### Step 2: Instrument Interfacing

**Description:** Select specified samples from a full sample plate/tray and transfer them into a new tray. This simulates interfacing with an automated analytical instrument (e.g., an autosampler, plate reader, or centrifuge).

**Success Criteria:**
- Correct samples are identified, handled, and placed as required
- Safe and consistent interaction at the instrument interface
- No cross-contamination (samples placed in correct target wells/slots)

### Step 3: Mobile Phase Management

**Description:** Perform loosening and tightening of threaded caps on solvent bottles (Reagent Bottles A & B) and relocate flexible tubing from one bottle to another.

**Success Criteria:**
- Threaded caps are loosened / tightened properly (no stripping, no leaks)
- Flexible tubing is switched to the new target position
- Bottles remain upright; no spills

---

## Workspace Setup

<!-- TODO: Add annotated workspace layout photo/diagram to media/ -->

The workspace consists of:
1. **Sample staging area** — bulk container or array tray with test samples
2. **High-density sample rack** — target rack for Step 1
3. **Instrument interface zone** — plate/tray for Step 2
4. **Reagent station** — Solvent bottles A & B with threaded caps and flexible tubing

---

## Consumables & Materials

See the full Bill of Materials in [`bom/bom.md`](bom/bom.md).

### Reference Dimensions

<!-- TODO: Fill in exact dimensions once provided by the user -->

| Item | Dimensions / Spec | Notes |
|------|-------------------|-------|
| Test sample (vial/tube) | <!-- TODO: e.g., 12 mm × 75 mm --> | <!-- TODO --> |
| High-density sample rack | <!-- TODO: e.g., 96-well format --> | <!-- TODO --> |
| Array tray | <!-- TODO --> | <!-- TODO --> |
| Reagent Bottle A | <!-- TODO: e.g., 500 mL GL45 --> | With threaded cap |
| Reagent Bottle B | <!-- TODO: e.g., 500 mL GL45 --> | With threaded cap |
| Flexible tubing | <!-- TODO: e.g., ID 3 mm, silicone --> | <!-- TODO --> |

---

## 3D-Printed Parts

All printable fixtures are in [`stl/`](stl/). Source CAD files are in [`cad/`](cad/).

| Part | File | Material | Notes |
|------|------|----------|-------|
| <!-- TODO: e.g., rack holder jig --> | `stl/TODO.stl` | PLA | <!-- TODO --> |

---

## Scoring

See the detailed scoring rubric in [`scoring/scoring.md`](scoring/scoring.md).

### Summary

Teams are scored across three dimensions for each step:

| Dimension | Weight | Description |
|-----------|--------|-------------|
| **Task Completion** | High | Were all required actions completed successfully? |
| **Precision & Safety** | High | No damage, no collisions, no spills, no cross-contamination |
| **Efficiency** | Medium | Total time to complete the task |

#### Per-Step Scoring Overview

| Step | Key Metrics |
|------|-------------|
| 1 – Sample Loading | # of samples correctly seated; # of drops; time |
| 2 – Instrument Interfacing | # of correct transfers; accuracy of placement; time |
| 3 – Mobile Phase Management | Cap integrity; tubing repositioned correctly; no spills; time |

---

## Reference Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | <!-- TODO: Add human demonstration video --> |
| Setup Photo | `media/workspace-setup.jpg` | <!-- TODO: Add annotated workspace photo --> |
| Consumables Photo | `media/consumables.jpg` | <!-- TODO: Close-up of vials, rack, bottles --> |

---

## Awards

| Place | Prize |
|-------|-------|
| 🥇 1st | Professional robot from AgileX (~$50,000–$60,000 value) |
| 🥈 2nd | $10,000 USD |
| 🥉 3rd | $5,000 USD |

---

## FAQ

<!-- TODO: Add common questions as they arise during preparation. -->
