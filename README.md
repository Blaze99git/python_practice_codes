# Daywise Python Practice

**Repository Purpose:**
- Collection of small, day-by-day Python practice exercises. Each `DayX/` folder (for example `Day1/`, `Day2/`) contains standalone scripts and notes used for learning and demonstration.

**Structure:**
- `DayX/` — folder for a single day's exercises (e.g., `Day1/`, `Day2/`).
- Example files: `Day2/1st_solution_age.py`, `Day1/FirstPrint.py`.
- Notes and TODOs live alongside exercises (for example `Day1/ToDO.md`, `Day2/questions.md`).

**How to run**
- The scripts are plain Python files. From the repository root (shell is `sh`) run:

  ```sh
  python3 Day2/1st_solution_age.py
  python3 Day1/FirstPrint.py
  ```

**Conventions for adding new days / files**
- Keep examples small and self-contained. Each file should run with system Python and have a short usage example at the top when helpful.
- Prefer adding new variants instead of editing original student solutions. Example suffixes: `_v2.py`, `_refactor.py` (e.g., `1st_solution_age_v2.py`).
- Preserve original filenames and their casing — do not rename or normalize existing files unless requested.

**Editing / PR guidance**
- Small, focused changes only. When improving a solution, add a new file in the same `DayX/` directory and reference the original in your PR description.
- If you add third-party packages, add a `requirements.txt` at the repository root and include install/run instructions in the PR.

**Dependencies & CI**
- There is currently no virtual environment, dependency file, or CI configured. Do not assume packaging or tests exist.

**Publishing a single Day to GitHub**
- For posting a day's work (for example Day 2), push the `Day2/` folder and include a short `README` or summary in the PR describing what the day contains.

**When in doubt**
- Ask before making bulk refactors, deleting files, or changing folder structure.

**Contact**
- If you want stricter policies (always add tests, autoformat, or a specific branch strategy), say which and I will update this README.
