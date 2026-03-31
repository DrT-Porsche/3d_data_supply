# 04 – Planning

This folder defines the **project prioritization** and **processing sequence** based on the tasks generated in stage 3.

## Sub-folders

### `prioritization/`
Contains prioritization records that rank epics and tasks by business value, deadline, or dependency. Each file represents a planning cycle or sprint.

Template: `prioritization/template_prioritization.json`

---

### `sequences/`
Defines the processing order for scenes and tasks within a project. Sequences take priorities, processing times, and trade availability into account.

Template: `sequences/template_sequence.json`

## Planning Process

1. Import all open tasks from `03_tasks/`.
2. Evaluate priority criteria (deadline, business value, dependencies).
3. Create or update a prioritization file in `prioritization/`.
4. Based on the prioritization and processing times from `02_basic_data/processing_times/`, define the delivery sequence in `sequences/`.
