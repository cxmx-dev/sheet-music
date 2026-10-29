# Sheet Practice

Single-file browser page for entering notes on a staff and hearing them back. VexFlow draws the notation. There is no build step.

## Run

Play: https://cxmx-dev.github.io/sheet-music/

Or open `index.html` in a browser. The page loads VexFlow, Bravura, and Academico from a CDN, so it needs a network connection.

## Controls

Click a line or space to enter the armed note or rest. The letter name and octave show beside the pointer and in the status bar.

| Control | What it does |
| --- | --- |
| Sidebar | Clef, key, time, duration, accidental, rest, clear measure, add measure |
| New / Save / Load | Reset the score, or store and restore it as JSON in `localStorage` |
| Play / Stop | Play the score with a simple tone. The current note turns gold |
| ABC | Show the score as ABC text and copy it |
| Learn | Name the note, name an interval, place a scale, or place a chord |
| Name the note | Tap A–G under the question. No typing |
| Controller | On the name or interval question: left/right moves, A confirms, B deals a new question, X hears it. Press one controller button after the page loads so the browser can see it |
| `1`–`5` | Whole, half, quarter, eighth, sixteenth. These still work after a click in the sidebar |
| Arrow keys | Move the selection |
| Shift+arrows | Change the selected note's pitch |
| Ctrl+Z | Undo the last placed note |
| Space | Play or pause |
| Delete | Remove the selected note |

Right-click does not open the browser menu on this page.

The page starts on an empty treble staff in 4/4, C major.

## Version History

2026-10-28
• First page: click entry, playback, learn tools, save/load, and ABC export.
• Ctrl+Z undoes the last placed note. The browser right-click menu is blocked.

2026-10-29
• Name-the-note uses A–G buttons. A controller can move, confirm, deal a new question, and hear the note.
• Interval buttons stay off that question. Sidebar clicks no longer block `1`–`5`, Ctrl+Z, Space, or Delete. The entry staff stays out of the sidebar.
 Keyboard (Enter confirm, N new, H hear) and big touch buttons do what the controller does. Sound unlocks on the first tap or key, including iOS, and notes play as you place them.
