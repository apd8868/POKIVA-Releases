# POKIVA

Official public release distribution for POKIVA.

This repository is the public release and distribution surface. The private engineering repositories remain the authoritative source for the qualified product build.

## Current release

**POKIVA V1 — 1.1.1** (hotfix for 1.1.0)

- Windows 11 x64
- Portable ZIP distribution

1.1.1 corrects how the view controls are drawn. In 1.1.0, panning, orbiting or zooming made all the furniture appear to slide together across a room that stayed still. Your objects were never actually moved. If you use 1.1.0, update to 1.1.1; your projects open unchanged.

## What you can do

- Create your own projects, starting from an **Empty Room** or a **Starter Room**
- Browse six included assets: chair, table, sofa, bed, storage and door
- Add objects to your own space
- Place objects with plain language, for example **put the sofa right of the table**
- Orbit, pan, zoom and reset the view with the **View** controls, which move the whole room and never move objects
- Undo and redo multiple steps
- Save, close and reopen your projects
- Open and keep working on projects created with POKIVA V1 1.0.1 and 1.1.0

## Quick Start

1. Download `POKIVA-V1.1.1-Windows-x64.zip` from the latest release.
2. Extract the ZIP to an ordinary folder you can write to.
3. Double-click `Launch POKIVA.vbs`.
4. Choose **New project**, give it a name, and pick **Empty Room** or **Starter Room**.
5. Add an object from the asset library, or type **Add a sofa** and choose **Execute**.
6. Select an object and try: **put the sofa right of the table**
7. Use **Undo** and **Redo** as needed, then **Save**.

No Git required. No GitHub account required. No Node.js installation required.

## Verify your download

SHA-256 checksums for every release are in the [`checksums`](checksums) folder.

## License

POKIVA is proprietary software. Your use of a release is governed by the `POKIVA-EULA.txt` included in the package. Third-party software in the package, including the bundled Node.js runtime, is governed by its own terms in the package's `licenses` folder.

## Known limitations

- Windows 11 x64 only
- Portable folder/ZIP distribution
- No installer
- "Next to" is intentionally not guessed: when a placement does not say which side, POKIVA asks for a direction such as `right of`, `left of`, `in front of` or `behind`, and changes nothing
- Placement does not yet keep objects clear of each other: placing several objects on the same side of the same object can stack them on top of one another
- A newly added sofa can start partly outside the visible area
- The included starter project shows a saved date of 1/1/1970
- The Home screen label reads "POKIVA V1"
- In a window about 1000 pixels tall or shorter, the result message for a command can be below the visible area; scroll down to see it
- The "Try" hint suggests a chair command even in a room that has no chair
