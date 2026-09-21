# Average Clicking Game

A tiny browser game built with plain HTML, CSS, and JavaScript. The goal is to click the big button enough times to keep your average clicks-per-second close to the target value while the round timer counts down.

## How to play

1. Open `index.html` in a modern web browser.
2. Press the Start round button.
3. Click the big button as steadily as you can for 15 seconds.
4. Try to keep your average close to `6.00 clicks/sec`.
5. Review your final score and restart when ready.

## Project layout

- `index.html` — page structure and game layout
- `styles.css` — all visual design and responsive styling
- `app.js` — game logic, timing, scoring, and click handling

## Local run instructions

You can either:

- double-click `index.html` in a file explorer, or
- run a simple local server from this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Notes

This is a fully static web app, so there is no backend or package installation required. It is playable immediately in any browser that supports standard HTML5 and JavaScript.



