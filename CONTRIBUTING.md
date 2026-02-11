# Contributing to WBCD Tasks

Thank you for contributing to the WBCD 2026 task specifications! This guide explains how to add a new task or improve an existing one.

---

## Adding a New Task

1. **Copy the template**
   ```bash
   cp -r _template/ track-N-your-task-name/
   ```

2. **Fill in every section** of `README.md`. Remove `<!-- TODO -->` markers as you go.

3. **Add your files**
   - `bom/bom.md` — Bill of Materials as a Markdown table.
   - `stl/` — 3D-printable STL files for fixtures or custom parts.
   - `cad/` — Source CAD files (STEP, Fusion 360 `.f3d`, or SolidWorks `.sldprt`).
   - `media/` — Photos, dimension diagrams, and reference videos.
   - `scoring/scoring.md` — Detailed scoring rubric with worked examples.

4. **Update the root `README.md`** to add your track to the table.

5. **Open a Pull Request** with a clear description of the task you are adding.

---

## File Naming Conventions

| Type | Convention | Example |
|------|-----------|---------|
| STL files | `lowercase-with-dashes.stl` | `sample-rack-holder.stl` |
| CAD files | Same base name as STL | `sample-rack-holder.step` |
| Images | `descriptive-name.jpg/png` | `workspace-setup-top-view.jpg` |
| Videos | `descriptive-name.mp4` | `human-demo-step1.mp4` |
| BOM | Always `bom.md` | — |
| Scoring | Always `scoring.md` | — |

---

## Editing an Existing Task

- Keep changes focused — one logical change per PR.
- If you update dimensions or consumables, update both the README and the BOM.
- If you update scoring criteria, update `scoring/scoring.md` **and** the summary in the README.

---

## Large Files

For files larger than 50 MB (e.g., videos, large CAD assemblies), please use [Git LFS](https://git-lfs.com/):

```bash
git lfs track "*.mp4"
git lfs track "*.f3d"
```

---

## Questions?

Open a [GitHub Issue](https://github.com/YOUR_ORG/wbcd_tasks/issues) or email [wbcd.competition@gmail.com](mailto:wbcd.competition@gmail.com).
