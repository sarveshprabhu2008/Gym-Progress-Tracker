# Chunked build plan


1. Set up the Git repository, Python project folders, and README.
2. Create a command-line menu with options to create or select a profile and exit.
3. Add exercise settings for target sets, rep ranges, and preferred weight increments.
4. Implement workout logging for exercise names, dates, weights, and reps completed in each set.
5. Save profiles and workouts to JSON and verify they reload after restarting.
6. Display workout history and personal records for each exercise.
7. Suggest weight increases when all target sets reach the top of the rep range at the same weight in two consecutive workouts for that exercise.
8. Handle invalid input and check the complete workflow, including cases that should and should not trigger a weight increase.

## Checks during implementation

- Saving and restarting preserves records and separates user profiles.
- Missing data files are handled on first use.
- Invalid numeric input does not crash the program.
- One qualifying workout does not trigger an increase.
- Two consecutive qualifying workouts at the same weight do trigger an increase.
- Incomplete sets, missed rep targets, or different weights do not qualify.
