# 03 – Tasks

This folder contains the tasks derived from the epics (stage 1) and the basic data (stage 2). Tasks define the concrete work packages to be executed per trade and application.

## How Tasks Are Derived

For each combination of **trade × application × scene** defined in an epic:
1. The applicable scene creation steps are looked up from `02_basic_data/scene_creation_steps/`.
2. The processing times are looked up from `02_basic_data/processing_times/`.
3. A task record is created capturing the scope, responsible trade, application, and estimated effort.

## Task Naming Convention

Task files should be named:

```
<epic_id>_<trade>_<application>_<scene_id>_task.json
```

Example: `EP001_body_catia_scene_42_task.json`

## Files

| File | Description |
|---|---|
| `template_task.json` | Template for creating a new task |
