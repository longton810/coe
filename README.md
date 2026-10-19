# COE

A standalone copy of all panels and behavior from NPS’s Emergency/Established patient workflow, including history review, radiographs, examinations, limited treatment, charting, and Notes.

Open `index.html` in a browser. Keep `index.html`, `style.css`, and `script.js` together. No installation or build step is required.

COE opens directly in the established-patient emergency workflow. Its browser autosave uses a separate key from NPS so the projects do not overwrite one another. The interface uses Odontogram’s blue theme with no top visit button. Field IDs and clinical chart color meanings are preserved.

The Dentition exam panel copies the chart, Findings, and Suggested treatment controls from Odontogram, integrated with COE autosave and Notes. Limited oral exam was removed from Intra-oral screening.

Summary - Dx/Tx reproduces Odontogram’s editable diagnosis/treatment chart without separate Copy Note or Undo Last buttons. Its contents are included in the clinical Note. Suggested treatment is positioned alongside the summary, stacking below on smaller screens. The separate clinical Note remains available.

The first panel labels its purpose Appointment for and defaults to Comprehensive Oral Evaluation. The Limited treatment panel is retired from the interface and newly generated Notes.

Dental history includes No change/Change review controls, with saved selections and details. The odontogram and Findings section use transparent backgrounds inside Dentition exam.

Dentition exam now uses the full Odontogram chart engine, including on-tooth finding labels and deletion, NSF checks, super-eruption arrows, whole-tooth wear, proximal filling rules, and a last-action notice with Undo. COE retains its separate autosave, Summary/Note synchronization, hidden duplicate diagnosis tags, and transparent chart background.
