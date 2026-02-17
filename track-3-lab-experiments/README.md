# Track 3: Lab Experiments

## Overview

This task simulates a laboratory automation workflow. The system handles high-density sample racks, interfaces with analytical instruments, and performs reagent bottle operations (threaded caps and flexible tubing). The full task consists of three sequential steps performed in rounds.

## Task Rules

Teams perform **Steps 1 → 2 → 3 in order** as one round. After completing a round, the workspace is reset and the next round begins. All three steps are **mandatory per round** — you cannot skip a step or reorder them. The goal is to complete as many rounds as possible within the time limit.

---

### Step 1: Sample Loading

Place vials into partially filled racks (dense packing). The racks already contain vials in most positions — the operator must seat the remaining vials into the correct empty slots.

| Action | Description |
|--------|-------------|
| 1a | Seat a 2 mL vial into the 2 mL sample vial rack |
| 1b | Seat a 2 mL vial into the 2 mL sample vial rack |
| 1c | Seat an 8 mL vial into the 8 mL glass vial rack |
| 1d | Seat an 8 mL vial into the 8 mL glass vial rack |

**Success Criteria:** All 4 vials fully inserted, upright, and in the correct positions. No vials damaged or dropped.

---

### Step 2: Instrument Interfacing

Load a sample rack into an analytical instrument by operating its drawer mechanism.

| Action | Description |
|--------|-------------|
| 2a | Open the instrument drawer |
| 2b | Place the sample rack into the drawer in the correct position and orientation |
| 2c | Close the instrument drawer |

**Success Criteria:** Drawer opened and closed cleanly without excessive force. Rack placed in the correct position inside the instrument.

---

### Step 3: Mobile Phase Management

Switch the solvent supply line from bottle A to bottle B by operating threaded caps and relocating the flexible tubing.

| Action | Description |
|--------|-------------|
| 3a | Loosen and remove the cap from the source bottle |
| 3b | Remove the tubing from the source bottle |
| 3c | Insert the tubing into the target bottle |
| 3d | Replace and tighten the cap on the source bottle |

**Success Criteria:** Caps handled without stripping or damage. Tubing correctly relocated. All bottles remain upright with no spills.

---

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

Printable STL and source CAD files are in [`parts/`](parts/). Click any file on GitHub to open the interactive 3D viewer.

| File | Part | Used In |
|------|------|---------|
| [`2ml-sample-vial.stl`](parts/2ml-sample-vial.stl) | 2 mL Sample Vial | Step 1 |
| [`2ml-sample-vial-rack.stl`](parts/2ml-sample-vial-rack.stl) | 2 mL Sample Vial Rack | Step 1, 2 |
| [`8ml-glass-vial.stl`](parts/8ml-glass-vial.stl) | 8 mL Glass Vial | Step 1 |
| [`8ml-glass-vial-rack.stl`](parts/8ml-glass-vial-rack.stl) | 8 mL Glass Vial Rack | Step 1, 2 |
| [`1l-solvent-bottle.stl`](parts/1l-solvent-bottle.stl) | 1 L Solvent Bottle | Step 3 |

## Scoring

### Competition Rules

- **Time limit:** Fixed per match (defined by the organizer).
- **Rounds:** Each round = Step 1 → Step 2 → Step 3, performed in order.
- **Mandatory sequence:** All three steps must be attempted per round. A new round cannot begin until the current round's Step 3 is completed or attempted.
- **Cumulative scoring:** Total score = sum of all points earned across all rounds within the time limit. Points earned in a partially completed round (when time expires) still count.

### Point Breakdown

Each step is worth **20 points per round** (60 points per complete round). The three steps are balanced to ensure no step is worth skipping.

#### Step 1 — Sample Loading (20 pts)

| Action | Points | Criteria |
|--------|:------:|----------|
| 1a – Seat 2 mL vial | 5 | Vial fully inserted, upright, correct position |
| 1b – Seat 2 mL vial | 5 | Same |
| 1c – Seat 8 mL vial | 5 | Vial fully inserted, upright, correct position |
| 1d – Seat 8 mL vial | 5 | Same |

#### Step 2 — Instrument Interfacing (20 pts)

| Action | Points | Criteria |
|--------|:------:|----------|
| 2a – Open drawer | 5 | Drawer fully extended without excessive force |
| 2b – Place rack | 10 | Rack in correct position and orientation |
| 2c – Close drawer | 5 | Drawer fully closed |

#### Step 3 — Mobile Phase Management (20 pts)

| Action | Points | Criteria |
|--------|:------:|----------|
| 3a – Remove cap | 5 | Cap unscrewed without stripping or spilling |
| 3b – Remove tubing | 5 | Tubing cleanly removed from source bottle |
| 3c – Insert tubing | 5 | Tubing inserted into target bottle |
| 3d – Replace cap | 5 | Cap re-secured on source bottle |

### Penalties

| Violation | Penalty |
|-----------|---------|
| Dropped vial | 0 pts for that action (no partial credit) |
| Spilled liquid | 0 pts for that action |
| Damaged equipment (stripped cap, broken vial) | 0 pts for that action |
| Skipped step | Remaining steps in that round score 0 |

### Example

> A team completes 3 full rounds and is mid-way through round 4 when time expires:
>
> | Round | Step 1 | Step 2 | Step 3 | Subtotal |
> |:-----:|:------:|:------:|:------:|:--------:|
> | 1 | 20 | 20 | 20 | 60 |
> | 2 | 15 | 20 | 15 | 50 |
> | 3 | 20 | 15 | 20 | 55 |
> | 4 | 20 | 10 | — | 30 |
> | | | | **Total** | **195** |

## Media

| Type | File | Description |
|------|------|-------------|
| Human Demo | `media/human-demo.mp4` | *TODO* |
| Teleop Demo | — | *Coming soon* |
