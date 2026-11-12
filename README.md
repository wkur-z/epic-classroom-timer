# EPIC Classroom Timer

Full-screen classroom timer with objectives, group check-offs, break countdown, and a synced Mentor Day mode.

- Open `index.html` (or the GitHub Pages link) for a normal single-room timer.
- Add `?room=your-room-name` to the link to sync screens. The screen with the room's PIN controls the timer; every other screen on that link follows it.
- Mentor Day: Round 1 with assigned mentors, mentors swap rooms for Round 2, then Open house.

Only business names and mentor names belong in the pairings. Anyone with a viewer link can see them.

## Mentor Day page

`/mentor/` is a separate full-screen page for mentor days: an agenda across the top (Welcome, Round 1, Round 2, Open house, Wrap up), the timer, topics to discuss, the follow-up email note, and a pairing graphic for each room. The screen with the PIN runs every room; `?side=2` opens the partner room's view. Setup edits pairings, topics, times and the follow-up note for every screen.

## Today's plan

Open the timer once with `?teacher=yourname` (for example `?teacher=kurtz`) and that screen remembers it. A **Today's plan** button (or the P key) then lists today's blocks from the `class_plans` table with AM or PM times and 1 to 3 checkpoints each. **Load** puts a block's checkpoints in Objectives, counts down to the block's end, and puts the next block in When time's up, so **Make these the objectives** (N) moves straight to the next block. Break blocks start the break with the right back-by time. `?teacher=off` forgets the teacher. Screens without a teacher never see the button, and the Mentor Day page never reads plans.
