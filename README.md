# Weekly hours

Track the hours you work on each project against a weekly goal. Runs in the browser and installs on a phone like an app.

**Live:** https://pedroferramos.github.io/hours_tracker/

## Features

- **Timer per project.** Tap play to start, tap again to stop. Starting one project stops the one that was running.
- **Weekly goals.** Each project has a goal in hours. A progress bar (with a tick per hour) shows how far along you are.
- **Weekly average.** Shown on each project, calculated over finished weeks only. Weeks with no work count as zero.
- **Day-by-day bars.** Seven small bars per project show which days of the week you worked. Today is marked.
- **Sessions.** Open a project, tap *Sessions*, and edit or delete any session for the week you're viewing.
- **Forgotten-timer warning.** After 4 hours of running, the card asks if you forgot to stop it. It only shows while the app is open.
- **Archive and delete.** Archived and deleted projects are kept (with their hours) under *Settings → Archived & deleted*, where you can restore them. There is an Undo button right after archiving or deleting.
- **Reorder.** Press and hold a project card, then drag it up or down. The ▲/▼ buttons in the edit menu do the same.
- **12 project colors.**
- **Light, dark or device theme.**
- **Week starts on Sunday or Monday.** Change it in *Settings*.
- **Works offline** once it has been opened.

## Install on your phone

Open the link in Chrome, then use the menu → **Install app**.

## Updating

Upload the changed files to the repo root. If you change any file, also bump the version name at the top of `sw.js` (e.g. `weekly-hours-v9` → `v10`) so phones drop their old cached copy.

## Your data

Stored only on the device, in the browser's local storage. There is no backup, export or sync, so clearing the app's site data deletes your hours.
