# EPIC Classroom Timer

Full-screen classroom timer with objectives, group check-offs, break countdown, and a synced Mentor Day mode.

- Open `index.html` (or the GitHub Pages link) for a normal single-room timer.
- Add `?room=your-room-name` to the link to sync screens. The screen with the room's PIN controls the timer; every other screen on that link follows it.
- Mentor Day: Round 1 with assigned mentors, mentors swap rooms for Round 2, then Open house.

Only business names and mentor names belong in the pairings. Anyone with a viewer link can see them.

## Mentor Day page

`/mentor/` is a separate full-screen page for mentor days: an agenda across the top (Welcome, Round 1, Round 2, Open house, Wrap up), the timer, topics to discuss, the follow-up email note, and a pairing graphic for each room. The screen with the PIN runs every room; `?side=2` opens the partner room's view. Setup edits pairings, topics, times and the follow-up note for every screen.
