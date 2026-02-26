# Track 4: Deformable Manipulation

## Overview

This task evaluates robotic manipulation of deformable objects in manufacturing scenarios. The robot must pick a T-shirt from a stack and load it onto a printing pallet, demonstrating sophisticated perception and control capabilities for handling flexible materials.

## Task Rules

The competition time limit is **15 minutes**. The goal is to pick and load a T-shirt onto a printing pallet with proper alignment and surface quality.

**Operational Constraints (Setup & Reset):**
- **Human Intervention:** Each human intervention incurs a penalty as defined by competition rules.
- **Reset Time:** Time spent resetting the workspace (e.g., restacking T-shirts) is excluded from the 15-minute limit.

### Step 1: Picking

<table>
<tr><td width="280" valign="top">

<img src="media/robot_demo.gif" width="280">

</td><td valign="top">

Grasp a single T-shirt from a stack. The robot must identify and separate one T-shirt from the pile.

| Action | Description |
|--------|-------------|
| 1a | Identify the topmost T-shirt on the stack |
| 1b | Grasp and separate a single T-shirt |

**Success Criteria:** Exactly one T-shirt securely grasped without disturbing the rest of the stack.

</td></tr>
</table>

### Step 2: Loading

<table>
<tr><td width="280" valign="top">

<img src="media/robot_demo.gif" width="280">

</td><td valign="top">

Position and load the T-shirt onto the printing pallet.

| Action | Description |
|--------|-------------|
| 2a | Transport T-shirt to the printing pallet |
| 2b | Place T-shirt onto the pallet surface |

**Success Criteria:** T-shirt placed on the pallet, covering the effective area appropriately.

</td></tr>
</table>

### Step 3: Alignment & Surface Quality

<table>
<tr><td width="280" valign="top">

<img src="media/robot_demo.gif" width="280">

</td><td valign="top">

Align the T-shirt with pallet edges and ensure a flat surface without wrinkles.

| Action | Description |
|--------|-------------|
| 3a | Align T-shirt edges with pallet boundaries |
| 3b | Smooth the surface to remove wrinkles |

**Success Criteria:** T-shirt edges aligned to pallet edges, surface smooth and flat for printing readiness.

</td></tr>
</table>

## Bill of Materials

| Image | Item | Qty | Price (CNY) | Supplier link |
|---|---|---:|---|---|
| <img src="media/printing_pallet.jpg" height="80"> | Printing Pallet (55×45cm, effective area: 54×45cm) | 1 | 378 | [Taobao](https://e.tb.cn/h.7w2Qa3LXhcVOGZw?tk=GTA9UmIukJ3) / [Amazon](https://www.amazon.com/VEVOR-Printing-Color-Station-Press/dp/B0BXP1HJ6C/?_encoding=UTF8&pd_rd_w=Mjx1V&content-id=amzn1.sym.4efc43db-939e-4a80-abaf-50c6a6b8c631%3Aamzn1.symc.5a16118f-86f0-44cd-8e3e-6c5f82df43d0&pf_rd_p=4efc43db-939e-4a80-abaf-50c6a6b8c631&pf_rd_r=NAP40A9PB0VT83TT2RVD&pd_rd_wg=AssFP&pd_rd_r=0fbae0b4-d773-4eba-a48e-dddd5057f63f&ref_=pd_hp_d_atf_ci_mcx_mr_ca_hp_atf_d&th=1) |
| <img src="media/White_T-shirt.png" height="80"> | White T-shirt (2XL, 185g, 100% cotton, ~70cm length, ~50cm chest width) | 1 | 8.9 | [Taobao](https://e.tb.cn/h.7D4U7zMW2ydxlRn?tk=66wBUNF8Tsf) |


## Scoring

### Competition Rules

- **Time limit:** 15 minutes per team.
- **Objective:** Pick, load, and align a T-shirt on the printing pallet.
- **Intervention:** Human intervention incurs a penalty as defined by competition rules.

### Point Breakdown

| Action | Points | Criteria |
|--------|:------:|----------|
| Pick + Load | +5 | Successfully picks a single T-shirt and loads it onto the pallet |
| Alignment + Surface | +5 | T-shirt loaded without major wrinkles and aligned to pallet edges |
| Multiple T-shirts picked | -5 | More than one T-shirt grasped in a single attempt |
| T-shirt stuck on pallet | -5 | Unable to remove or reposition the T-shirt |

### Example

> A robot completes two rounds of T-shirt loading:
>
> | Round | Action | Result | Score |
> |:-----:|--------|--------|:-----:|
> | 1 | Pick + Load | Success | +5 |
> | 1 | Alignment + Surface | Minor wrinkles, partial alignment | +0 |
> | 2 | Pick + Load | Picked two T-shirts (-5), reloaded one | +5 -5 |
> | 2 | Alignment + Surface | Good alignment, smooth surface | +5 |
> | | | **Total** | **+10** |

## Coming Soon

- **Datasets** — UMI and/or real robot teleoperation datasets for this task
- **Simulation Environment** — digital-twin simulator for this task
