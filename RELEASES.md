# Releases

## POKIVA V1 — 1.1.1

**Status:** RELEASED — HOTFIX for 1.1.0

**Supported:** Windows 11 x64

**Distribution:** Portable ZIP

**Artifact:** `POKIVA-V1.1.1-Windows-x64.zip`

**SHA-256:** `4ba89231154aa95d7695d48cbc69c8efe07c3880bce29506f738b2b7c5935494`

### What this hotfix corrects

- View navigation no longer makes the furniture appear to slide together through a stationary room.
- Pan, Orbit and Zoom now move the room, the grid and the objects as one coherent view.
- The view controls are labelled **View** and state that they do not move objects.
- Moving a single object remains isolated to the selected object.
- The selection highlight, the "Selected" status line and the object a command will move are now always the same object.

In 1.1.0 this was a display problem only. Your objects were never moved by the view controls, and your saved projects are not affected. Projects created with 1.1.0 and 1.0.1 open unchanged in 1.1.1.

### Known limitations (not changed by this hotfix)

- Windows 11 x64 only
- Portable ZIP/folder distribution
- No installer
- "Next to" remains intentionally fail-closed: when spatial intent is underspecified, POKIVA asks for a direction and changes nothing
- Placement does not yet keep objects clear of each other: placing several objects on the same side of the same object can stack them on top of one another
- A newly added sofa can start partly outside the visible area
- The included starter project shows a saved date of 1/1/1970
- The Home screen label reads "POKIVA V1"
- In a window about 1000 pixels tall or shorter, the result message for a command can be below the visible area
- The "Try" hint suggests a chair command even in a room that has no chair

### License

Proprietary. The package includes `POKIVA-EULA.txt` and the notices for the third-party software it contains. The license terms are unchanged from 1.1.0.

## POKIVA V1 — 1.1.0

**Status:** RELEASED

**Supported:** Windows 11 x64

**Distribution:** Portable ZIP

**Artifact:** `POKIVA-V1.1.0-Windows-x64.zip`

**SHA-256:** `bd441eee59f3e13a5ea87746383a9c300eeae73ca5ba0607464c291e1fc86c88`

A product upgrade centered on spaces you create yourself.

### Highlights

- Create new projects
- Start from an Empty Room or a Starter Room
- Browse six included assets: chair, table, sofa, bed, storage and door
- Add objects to your own space
- Natural-language placement, for example "put the sofa right of the table"
- Orbit, pan, zoom and camera reset
- Multi-step Undo and Redo
- Save, close and reopen with your work preserved
- Compatible with projects created in POKIVA V1 1.0.1

### Known limitations

- Windows 11 x64 only
- Portable ZIP/folder distribution
- No installer
- "Next to" remains intentionally fail-closed: when spatial intent is underspecified, POKIVA asks for a direction and changes nothing

### License

Proprietary. The package includes `POKIVA-EULA.txt` and the notices for the third-party software it contains.

## POKIVA V1 — 1.0.1

**Status:** RELEASED

**Supported:** Windows 11 x64

**Distribution:** Portable ZIP

### User-facing hotfixes

- Fixed normal Windows launcher startup reliability.
- Fixed relaunch/existing-server handling.
- Added an editable Starter Project for first-time use.
- Updated Quick Start to use the Starter Project.

## POKIVA V1 — 1.0.0

**Status:** PUBLICATION PENDING

**Supported:** Windows 11 x64

**Distribution:** Portable ZIP / local folder

### Known V1 limitations

- Windows 11 x64 only
- No installer
- Local-folder distribution
