# Sixth Station Flow — Pomodoro Web App

> [!NOTE]
> A minimal, fast, and friendly Pomodoro timer built with plain HTML, CSS, and JavaScript.

---

## About

`Sixth Station Flow` is a lightweight Pomodoro-style productivity web app designed to help you focus with a simple work/break timer. It is implemented with zero build tools — just static files that run in any modern browser.

## Features

- **Minimal UI:** Clean, distraction-free timer interface.
- **No Build Required:** Works by opening `index.html` or serving the folder over a local HTTP server.
- **Easy to Customize:** Styles and behavior are in `styles.css` and `script.js` for quick tweaks.
- **Static & Portable:** Perfect for quick self-hosting or embedding into a larger site.

## Demo / Quick Start

- Open the project folder and double-click `index.html` to run in your default browser.
- Or run a simple local HTTP server (recommended) and open `http://localhost:8000`.

PowerShell (Windows) example using Python's built-in server:

```powershell
# From the `project` folder
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

If you don't have Python, you can use other simple servers (Node, VS Code Live Server extension, etc.).

## Usage

- Click the start button to begin a focus session.
- The interface will show remaining time and notify when a session ends.
- Use the pause/reset controls (if provided) or refresh the page to restart.

Check `script.js` to see how the timer logic is implemented and `styles.css` for visual adjustments.

## Customization

- Change session durations in `script.js` (look for variables like `WORK_MINUTES`, `BREAK_MINUTES`).
- Tweak colors, spacing, and typography in `styles.css` to match your brand or preference.
- Add sound or desktop notifications by extending the existing JavaScript logic.

## Development

This project has no build step. Recommended workflow:

1. Open the project folder in your editor (VS Code recommended).
2. Edit `script.js` and `styles.css` as needed.
3. Reload `index.html` in the browser to see changes.

For a smoother development experience, install the VS Code Live Server extension and click "Go Live".

## File Structure

- `index.html` — Application entry point and markup.
- `styles.css` — Styling and layout rules.
- `script.js` — Timer logic and interactions.
- `assets/` — Images, icons, and other static assets.


## License

MIT License is used here.

