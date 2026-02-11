# WBCD 2026 – Competition Task Specifications

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

> **Open-source task definitions, 3D-printable fixtures, bills of materials, and scoring rubrics for the [2nd World Bimanual Competitive Dexterous Manipulation (WBCD) Competition](https://wbcdcompetition.github.io/).**

This repository provides everything needed to replicate the official WBCD 2026 benchmark tasks. Whether you are a competing team preparing your setup, a researcher benchmarking your own system, or someone who wants to build on these tasks, you will find standardized specifications here.

---

## Competition Tracks

| Track | Name | Robot | Directory |
|-------|------|-------|-----------|
| 1 | Logistics Picking | Unitree G1 | [`track-1-logistics-picking/`](track-1-logistics-picking/) |
| 2 | Logistics Packing | Galaxea R1 | [`track-2-logistics-packing/`](track-2-logistics-packing/) |
| 3 | Lab Experiments | AgileX Bimanual | [`track-3-lab-experiments/`](track-3-lab-experiments/) |
| 4 | Deformable Manipulation | ARX | [`track-4-deformable-manipulation/`](track-4-deformable-manipulation/) |

Each track directory follows a consistent structure — see [Directory Layout](#directory-layout) below.

---

## Quick Start

### Reading a Task Spec

1. Navigate to the track directory (e.g., `track-3-lab-experiments/`).
2. Read `README.md` for the full task definition, rules, and setup instructions.
3. Check `bom/bom.md` for the bill of materials.
4. Check `scoring/scoring.md` for the detailed scoring rubric.

### Replicating a Task Setup

1. **3D-print fixtures** — Import STL files from `stl/` into your slicer (PLA recommended unless noted otherwise).
2. **Source consumables** — Follow the BOM in `bom/bom.md`; purchase links are provided where available.
3. **Arrange the workspace** — Refer to diagrams and photos in `media/`.

---

## Directory Layout

```
wbcd_tasks/
├── README.md                          ← You are here
├── CONTRIBUTING.md                    ← How to add/edit tasks
├── LICENSE
├── _template/                         ← Blank task template for contributors
│   └── README.md
├── track-1-logistics-picking/
│   ├── README.md
│   ├── bom/
│   ├── stl/
│   ├── cad/
│   ├── media/
│   └── scoring/
├── track-2-logistics-packing/
│   └── ...
├── track-3-lab-experiments/
│   └── ...
└── track-4-deformable-manipulation/
    └── ...
```

---

## Resources

- 🌐 **Competition Website**: <https://wbcdcompetition.github.io/>
- 📊 **UMI Data Gallery**: <https://wbcdcompetition.github.io/umi-gallery-dist/>
- 🤖 **Simulation Environments**: <https://wbcdcompetition.github.io/simulation.html>
- 📧 **Contact**: [wbcd.competition@gmail.com](mailto:wbcd.competition@gmail.com)

---

## Contributing

We welcome contributions! If you are a track owner or want to improve an existing task spec, please see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Citation

If you use these task specifications in your research, please cite:

```bibtex
@misc{wbcd2026tasks,
  title   = {WBCD 2026 Competition Task Specifications},
  author  = {WBCD Organizing Committee},
  year    = {2026},
  url     = {https://github.com/YOUR_ORG/wbcd_tasks},
  note    = {Open-source benchmark tasks for bimanual dexterous manipulation}
}
```

---

## License

This project is licensed under the [MIT License](LICENSE).
