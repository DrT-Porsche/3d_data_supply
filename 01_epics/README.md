# 01 – Epics

An **epic** represents a new project. It is the starting point of the 3D data supply process and contains all relevant definitions needed to derive tasks and plan delivery.

## Contents of an Epic

| Field | Description |
|---|---|
| `epic_id` | Unique identifier for the epic |
| `project_name` | Human-readable project name |
| `status` | Current status (`draft`, `active`, `completed`, `on_hold`) |
| `applications` | List of applications used in the project |
| `trades` | List of trades (Gewerke) and the applications each trade uses |
| `scenes` | List of scenes required per trade and application, including scope details |

## How to Use

1. Copy `template_epic.json` and rename it to `<epic_id>_epic.json`.
2. Fill in all fields according to the project requirements.
3. Save the file in this folder.
4. The filled epic is the input for generating basic-data references (stage 2) and tasks (stage 3).

## Files

| File | Description |
|---|---|
| `template_epic.json` | Template for creating a new epic |
