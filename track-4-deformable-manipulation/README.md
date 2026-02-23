# Track 4: Deformable Manipulation

## Overview

This task evaluates robotic manipulation of deformable objects in manufacturing scenarios. The robot must pick a T-shirt from a stack and load it onto a printing pallet, demonstrating sophisticated perception and control capabilities for handling flexible materials.

**Objective:** Pick and load a T-shirt onto a printing pallet with proper alignment and surface quality.

**Time Limit:** 15 minutes

![Printing Pallet Setup](media/Picture1.jpg)

## Task Workflow

### Stage 1: Picking

Grasp a single T-shirt from a stack.

- Robot must identify and separate one T-shirt from the stack
- Only one T-shirt should be grasped per attempt

### Stage 2: Loading

Position and load the T-shirt onto the printing pallet.

- T-shirt must be placed on the pallet surface
- T-shirt should cover the pallet appropriately

### Stage 3: Alignment & Surface Quality

Align the T-shirt with pallet edges and ensure flat surface without wrinkles.

- T-shirt edges should align with pallet boundaries
- Surface must be smooth and flat for printing readiness

## Specifications

### T-shirt

| Property | Value |
|----------|-------|
| Weight | 185g |
| Material | 100% cotton |
| Length | ~70cm |
| Chest width | ~50cm |
| Size | 2XL |

### Printing Pallet

| Property | Value |
|----------|-------|
| Dimensions | 55cm × 45cm |
| Effective area | 54cm × 45cm |

## Bill of Materials

| Item | Specification | Supplier |
|------|---------------|----------|
| Printing Pallet | 55×45cm | [Taobao](https://e.tb.cn/h.7w2Qa3LXhcVOGZw?tk=GTA9UmIukJ3) / [Amazon](https://www.amazon.com/VEVOR-Printing-Color-Station-Press/dp/B0BXP1HJ6C/?_encoding=UTF8&pd_rd_w=Mjx1V&content-id=amzn1.sym.4efc43db-939e-4a80-abaf-50c6a6b8c631%3Aamzn1.symc.5a16118f-86f0-44cd-8e3e-6c5f82df43d0&pf_rd_p=4efc43db-939e-4a80-abaf-50c6a6b8c631&pf_rd_r=NAP40A9PB0VT83TT2RVD&pd_rd_wg=AssFP&pd_rd_r=0fbae0b4-d773-4eba-a48e-dddd5057f63f&ref_=pd_hp_d_atf_ci_mcx_mr_ca_hp_atf_d&th=1) |
| White T-shirt | 2XL, 185g, 100% cotton | [Taobao](https://e.tb.cn/h.7D4U7zMW2ydxlRn?tk=66wBUNF8Tsf) |

## Scoring

| Points | Condition |
|--------|-----------|
| +5 | Successfully picks a single T-shirt and loads it onto the pallet |
| +5 | T-shirt loaded without major wrinkles and aligned to pallet edges |
| -5 | Multiple T-shirts picked in a single attempt |
| -5 | T-shirt becomes stuck on the pallet (unable to remove/reposition) |

## Rules

- **Time Limit:** 15 minutes total
- **Human Intervention:** Each human intervention incurs a penalty as defined by competition rules
- **Reset Time:** Time spent resetting the workspace (e.g., restacking T-shirts) is excluded from the 15-minute limit
