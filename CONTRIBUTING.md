# Contributing

We welcome contributions to improve task specifications. Here's how:

## Editing an Existing Task

1. Keep changes focused — one logical change per PR.
2. If you update materials, update both the README and `bom/bom.md`.
3. If you update scoring criteria, update both the README and `scoring/scoring.md`.

## Adding a New Task

1. Copy `_template/` to a new `track-N-task-name/` directory.
2. Fill in every section of `README.md`.
3. Add files to `bom/`, `stl/`, `cad/`, `media/`, and `scoring/` as needed.
4. Update the root `README.md` to add your task to the table.
5. Open a Pull Request.

## File Naming

| Type | Convention | Example |
|------|-----------|---------|
| STL files | `lowercase-with-dashes.stl` | `sample-rack-holder.stl` |
| CAD files | Same base name as STL | `sample-rack-holder.step` |
| Images | `descriptive-name.jpg/png` | `workspace-setup.jpg` |
| Videos | `descriptive-name.mp4` | `human-demo.mp4` |

## Large Files

For files larger than 50 MB (e.g., videos, large CAD assemblies), use [Git LFS](https://git-lfs.com/):

```bash
git lfs track "*.mp4"
```

## Questions?

Open a [GitHub Issue](https://github.com/wbcdcompetition/wbcd_tasks/issues) or email [wbcd.competition@gmail.com](mailto:wbcd.competition@gmail.com).
