# 02 – Basic Data

This folder contains general master and reference data that is valid across projects. It provides the foundation for deriving tasks (stage 3) and planning (stage 4).

## Sub-folders

### `fes_codes/`
Maps FES codes (Functional Equipment Specification) to scenes. Contains:
- Which default data (Basisdaten) is available for each scene
- The FES code assigned to each scene

Template: `fes_codes/template_fes_mapping.json`

---

### `scene_creation_steps/`
Defines the individual process steps required to create a scene. Each scene type can have its own step definition. Contains:
- A list of ordered steps (e.g., modelling, texturing, lighting, rendering, QA)
- Dependencies between steps
- Responsible role per step

Template: `scene_creation_steps/template_scene_steps.json`

---

### `processing_times/`
Records the estimated processing time for each scene. Processing times are scene-specific and used for planning. Contains:
- Scene identifier
- Estimated processing time per step (in hours)
- Total estimated time

Template: `processing_times/template_processing_times.json`
