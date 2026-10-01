# NEXUS OS

NEXUS OS is a lightweight local-first productivity dashboard designed for daily planning, focus tracking, habit building, note-taking, and personal goal management.

## Features

- Task manager with filtering and completion tracking
- Daily planner with time blocks
- Study Center with focus timer and subject progress tracking
- Notes and journal for reflection and planning
- Habit tracking with streaks
- Goals and progress monitoring
- Bookmarks manager
- Calculator and text counter utilities
- Monthly calendar view
- Dark/light mode with accent color options
- Local backup export/import with JSON persistence

## Project structure

- `index.html` — main app UI and logic
- `assets/logo/` — logo and favicon assets
- `assets/images/` — supporting artwork and dashboard visuals

## How to run

Because this is a static front-end application, you can serve it locally with a simple web server:

```bash
cd path/to/nexus-os
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Data persistence

The app stores its data in the browser using `localStorage` under the key `NEXUS_ENGINE_STORE_V2`.

You can also export/import JSON backups from the Settings section.

## Notes

- No backend or external service is required.
- The project is intentionally lightweight and works as a static website.
- Assets are stored locally to avoid broken external dependencies.
- Workspace backups and editor settings are local-only and are not included in the public repository.
