# justcodebro

A lightweight personal developer dashboard for tracking habits, coding time, ideas, and progress.

justcodebro is a static HTML app designed for developers who want a simple place to stay consistent with their workflow. It combines a landing page, habit tracker, idea generator, and a devlog to help you build momentum without installing a heavy app or setting up a backend.

## Features

- Habit tracking with daily check-ins
- Developer-focused landing page and navigation
- Idea generator for creative coding prompts
- Devlog for notes, wins, bugs, and lessons learned
- Clean dark UI built with HTML and CSS
- No build step or dependencies required

## Project structure

- `index.html` — landing page and feature overview
- `dashboard.html` — main dashboard shell and navigation
- `habits.html` — interactive habit tracker powered by local storage
- `ideas.html` — random idea generator for projects and coding inspiration
- `devlog.html` — personal development journal
- `images/` — brand and UI assets

## Run locally

Because this is a static site, you can open the pages directly in a browser:

1. Clone the repository
2. Open `index.html` in your browser

Or use a local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Notes

This project is intentionally simple and beginner-friendly. It is a great foundation for a personal productivity app and can be extended with analytics, timeline tracking, project management, or authentication later on.

## License

This project is available for personal use and modification.

## Author

Amin Rabhi
