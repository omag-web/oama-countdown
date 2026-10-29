# OAMA Roundtable Timer

Full-screen countdown timer for OAMA Conference roundtable sessions. Open `index.html` in Chrome on the presentation laptop (or serve it with GitHub Pages).

## Controls

| Key | Action |
| --- | --- |
| Clicker, Space, Enter, arrows, Page Up/Down | Start or restart the selected timer |
| `3` | Switch to 30 minutes |
| `1` | Switch to 10 minutes |
| `B` | Switch to the break timer (15 minutes) |
| `+` / `-` | Add or remove 1 minute (see below) |
| `F` | Toggle fullscreen |

- `+` / `-` while a timer runs changes the time left. When stopped, it changes that timer's length. Pressing `3`, `1`, or `B` stops the timer and puts every length back to its default (30 / 10 / 15). After time is up, `+` adds an extra minute without counting a new session.
- The timer buttons are hidden and fade in only while the mouse moves.
- Alerts flash at 5:00, 1:00, and 0:00.
- "Roundtable Session #N" counts each 30-minute start and is saved in the browser. The faint Reset count button in the bottom-left corner clears it.
- The OAMA logo loads from Squarespace; offline, an "OAMA" wordmark shows instead.
