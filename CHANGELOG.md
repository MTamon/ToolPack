# Change Log
## [0.0.0] - 2023-11-28
### Init

## [0.0.2] - 2023-12-01
### Add
- parallel.parallel_launcher() for multi-processing

## [0.0.4] - 2023-12-01
### Fix
- Fix module import bugs
## [0.0.6] - 2026-06-12
### Add
- `parallel_launcher`: correctly spelled public API name. `parallel_luncher` is kept as a deprecated alias (emits `DeprecationWarning`).

## [0.0.7] - 2026-06-14
### Fix
- Declare the `typing_extensions` runtime dependency (used by `parallel.py`). It was missing from requirements, so a clean install failed to `import toolpack`.
