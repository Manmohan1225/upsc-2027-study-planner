# UPSC CSE 2027 Planner — V30

V30 keeps the V22-style side-menu Command Centre and restores the dated preparation roadmap. It fixes the daily checklist progress synchronisation by adding the missing central `renderAll()` refresh routine and immediately updating the Home daily hours/tasks, weekly and monthly completion after a routine checkbox is ticked or unticked.

## Install
1. Back up your planner from the Backup section first.
2. Extract this ZIP.
3. Replace `index.html` and `sw.js` in the root of your GitHub Pages repository.
4. Commit both files to `main` and wait for Pages deployment.
5. Reopen the site. The top banner should say **V30 PROGRESS SYNC + ROADMAP**.

Progress remains in the same browser-local `upsc27v2_` storage namespace. It does not sync between devices.
