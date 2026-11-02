# Gym Progress Tracker

A Python command-line project for CS 19300.

## Project Goal

Help users keep track of their workouts and see when they are ready to increase the weight for an exercise. Users will manually enter their workout information and access their saved history without needing an external app or API.

## MVP Scope

1. Create and select local profiles and set exercise targets, including target sets, a rep range, and weight increments.
2. Log exercises, weights, sets, and reps, and save/load workout data using a local JSON file.
3. View previous workouts and personal records.
4. Suggest increasing an exercise's weight when all target sets reach the top of the rep range at the same weight in two consecutive workouts for that exercise. Otherwise, suggest keeping the current weight or collecting more workout data.

## Future Plans

These features are in the Schedule quadrant and will be considered after the MVP works:

- Recommend personalized workout routines.
- Display graphs showing progress over time.
- Add workout reminders.
- Track weekly workout goals.

## Tech Stack

- Python 3 for application logic.
- `input()` and `print()` for the command-line interface.
- Built-in `json` for local data storage.
- Built-in `datetime` for workout dates.
- Built-in file functions and `os.path` for reading files and checking paths.
- VS Code for development and Git/GitHub for version control.

No external APIs or third-party Python packages are planned for the MVP.

## Folder Structure

| Path | Purpose |
| --- | --- |
| `src/` | Python application code |
| `tests/` | Future tests for storage, input validation, and progression rules |
| `data/` | Local workout JSON files; personal data is excluded from Git |
| `docs/eisenhower-matrix.md` | Feature priorities |
| `docs/system-diagram.md` | Planned application flow |

## Design Documents

- [Original Eisenhower Matrix PDF](Eisenhower%20Matrix.pdf)
- [Eisenhower Matrix (Markdown)](docs/eisenhower-matrix.md)
- [System Diagram](docs/system-diagram.md)

## Current Status

Planning and repository setup. The tracker has not been implemented yet.

## Development Process

Implement and commit each chunk from the Part 2.3 design plan as it is completed. Use descriptive commit messages that identify the actual work completed. Keep setup, feature implementation, testing, and fixes in meaningful commits throughout development.
