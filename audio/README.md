# Voice clips

Drop recordings here. `.mp3`, `.m4a` or `.wav` all work (a plain phone voice memo is fine):

| File | When it plays |
|---|---|
| `intro1.mp3`, `intro2.mp3` | On the main screen, before the run: right away if the browser allows sound, otherwise right after the "לחצו כדי להתחיל" tap. Tapping the heroine replays it. |
| `start1.mp3`, `start2.mp3` | When a run starts (the Start button, and "play again"). |
| `finish1.mp3` – `finish3.mp3` | On the game-over screen, right after the sad trombone. |
| `new_record1.mp3`, `new_record2.mp3` | Instead of a finish clip when the run set a new high score, after the fanfare. |

- Silence at the start and end is trimmed and the volume is normalized automatically.
- The music ducks under the voice, and the heroine "talks" along with it.
- Each moment takes turns between its versions, remembered between visits.
- A missing file is simply skipped.

To add more clips or a third version, add it to `VOICE_CLIPS` (and `VOICE_GROUPS`) in `index.html`.
