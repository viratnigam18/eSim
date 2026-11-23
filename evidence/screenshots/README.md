# Evidence: Runtime Screenshots

This directory is designated for live graphical environment verification screenshots captured during runtime execution on Ubuntu 25.04.

## Current Audit Status: BLOCKED
As documented in `docs/REPORT.md` and `docs/TEST_MATRIX.md` (Scenario T08), full end-to-end GUI launch testing requires an active X11/Wayland display server and an isolated Ubuntu 25.04 VM with root privileges.

In accordance with strict forensic engineering standards, no fabricated or simulated screenshots are committed. Once live VM testing is performed by mentors or evaluators, actual display captures of:
1. `esim` main application window
2. KiCad 8 schematic editor with eSim custom symbol libraries loaded
3. NGHDL simulation output
can be archived directly into this directory.
