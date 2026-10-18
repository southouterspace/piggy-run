# Piggy Run

An NES-style side-scrolling runner. You play a little pink pig: jump over crates, hay bales, fences, pipes and mud puddles, and grab apples for bonus points.

## Play

Open `index.html` in any modern browser, on a computer or a phone. It's one file with no build step and no dependencies. On phones it fills the screen in either orientation; held upright, the view zooms in and scrolls a little slower so you still have time to react.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Jump (hold to go higher) | Space, Up arrow, W | Tap and hold anywhere |
| Pause | P or Esc | II button |
| Mute | M | ♪ button |

## Rules

- The pig oinks every time it jumps.
- Hitting an obstacle or landing in mud ends the run.
- Every 250 m is a new level. Each level scrolls faster, plays the music faster, and moves to the next time of day: Morning Meadow, Sunny Farm, Sunset Hills, Twilight Woods, Starry Night.
- Score is meters run plus 10 per apple. Your best score is saved in the browser.
