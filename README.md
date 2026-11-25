# Ahmad Edition - app list

The app list used by the **Install apps** window of *Windows 11 Ahmad Edition*.

- `apps.json` - every app: winget id, category, packs, and a short description in English and Arabic.
- `icons/` - the app icons (`<winget id>.png`).

When the window opens it reads `apps.json` from this repository, so a new app added here shows up on every PC without building a new ISO. With no internet it falls back to the copy inside Windows.
