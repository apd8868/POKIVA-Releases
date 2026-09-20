# POKIVA

Official public release distribution for POKIVA.

This repository is the public release and distribution surface. The private engineering repositories remain the authoritative source for the qualified product build.

## Current release

**POKIVA V1 — 1.1.0**

- Windows 11 x64
- Portable ZIP distribution

## What you can do

- Create your own projects, starting from an **Empty Room** or a **Starter Room**
- Browse six included assets: chair, table, sofa, bed, storage and door
- Add objects to your own space
- Place objects with plain language, for example **put the sofa right of the table**
- Orbit, pan, zoom and reset the view
- Undo and redo multiple steps
- Save, close and reopen your projects
- Open and keep working on projects created with POKIVA V1 1.0.1

## Quick Start

1. Download `POKIVA-V1.1.0-Windows-x64.zip` from the latest release.
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
