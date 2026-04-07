# WBCD Task Benchmark

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Open-source, reproducible benchmark tasks for real-world bimanual dexterous manipulation.

## Background

The [What Bimanuals Can Do (WBCD) Competition](https://wbcdcompetition.github.io/) advances the state of the art in robotic manipulation through standardized real-world tasks. While simulation benchmarks have driven significant progress, there remains a critical gap in **standardized, reproducible physical-world tasks** that the community can build upon and compare against.

This repository provides complete, open-source task specifications — including task rules, bills of materials with procurement links, 3D-printable fixtures, and scoring criteria — so that anyone can replicate these benchmark tasks in their own lab.

## Tasks

| Track | Task | Description |
|-------|------|-------------|
| 1 | [Logistics Picking](track-1-logistics-picking/) | Transfer items from multi-height shelves to a transport vehicle |
| 2 | [Logistics Packing](track-2-logistics-packing/) | Pick items from a moving conveyor and pack them into containers |
| 3 | [Lab Experiments](track-3-lab-experiments/) | Handle sample racks, interface with instruments, and manage reagent bottles |
| 4 | [Deformable Manipulation](track-4-deformable-manipulation/) | Load, fold, and unload a T-shirt |

Each task page contains the complete specification: rules, bill of materials, and scoring criteria.

## Autonomy Level Multiplier

Task scores are scaled by an **autonomy multiplier** that reflects the level of human involvement during execution. Teams may choose a **different autonomy level for each step** within a task — there is no requirement to use the same level throughout.

| Level | Description | Multiplier |
|-------|-------------|:----------:|
| **On-site Teleoperation** | Human operator is physically present and controls the robot with direct line-of-sight | ×1 |
| **Remote Teleoperation** | Human operator controls the robot remotely via video feed only (no direct view of the scene; network latency applies) | ×2 |
| **Fully Autonomous** | No human control during execution; the robot runs a learned or programmed policy end-to-end | ×4 |

The multiplier is applied **per step**: each step's base score is multiplied by the autonomy level chosen for that step, and the results are summed to produce the final score.

> **Note:** The multipliers above are competition-wide defaults. The optimal multiplier for a given task ultimately depends on its difficulty and content — these presets serve as a balanced starting point and may be adjusted per track in future editions.

## Media

Each task includes reference videos demonstrating the expected workflow:

- **Human demonstrations** — task performed by a human operator
- **Robot demonstrations** — task performed via robot teleoperation, showing the full workflow

## Coming Soon

- **Datasets** — UMI and/or real robot teleoperation datasets for each task
- **Simulation Environments** — digital-twin simulators for each task

## Resources

- **Competition Website**: <https://wbcdcompetition.github.io/>
- **UMI Data Gallery**: <https://wbcdcompetition.github.io/umi-gallery-dist/>
- **Simulation Environments**: <https://wbcdcompetition.github.io/simulation.html>
- **Contact**: [wbcd.competition@gmail.com](mailto:wbcd.competition@gmail.com)

## Contributing

We welcome contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Citation

If you use these task specifications in your research, please cite:

```bibtex
@misc{wbcd2026tasks,
  title   = {WBCD Task Benchmark},
  author  = {WBCD Organizing Committee},
  year    = {2026},
  url     = {https://github.com/wbcdcompetition/wbcd_tasks},
  note    = {Open-source benchmark tasks for bimanual dexterous manipulation}
}
```

## License

This project is licensed under the [MIT License](LICENSE).
