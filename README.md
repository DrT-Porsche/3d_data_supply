# 3d_data_supply

Organization of the project structure for 3D data supply, including change management. Setup, tasks, tickets.

## Project Structure

The repository is organized into four stages that map the full lifecycle of a 3D data supply project:

```
01_epics/            # Stage 1 – Epic / project definitions
02_basic_data/       # Stage 2 – General reference and master data
03_tasks/            # Stage 3 – Derived tasks per trade and application
04_planning/         # Stage 4 – Project prioritization and sequencing
```

---

### 01_epics
Stores the definition of each new project (epic). An epic captures:
- Which **applications** are used in the project
- Which **trades** (Gewerke) use which applications
- Which **scenes** are needed per trade and application
- The **scope** of each scene

See [`01_epics/README.md`](01_epics/README.md) for details and the epic template.

---

### 02_basic_data
Holds general master and reference data that is shared across projects:
- **FES codes** – which default data is available and which FES code is assigned to which scene
- **Scene creation steps** – the individual steps required to create a scene
- **Processing times** – how long each scene takes to process (scene-specific)

See [`02_basic_data/README.md`](02_basic_data/README.md) for details and sub-folder contents.

---

### 03_tasks
Contains the tasks derived from the epics and basic data. Tasks are broken down by trade and application and define the concrete work packages to be executed.

See [`03_tasks/README.md`](03_tasks/README.md) for details and the task template.

---

### 04_planning
Defines the project prioritization and the processing sequence. Based on the tasks from stage 3, this stage establishes the order in which scenes and packages are delivered.

See [`04_planning/README.md`](04_planning/README.md) for details and templates.
