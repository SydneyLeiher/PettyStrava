# Petty Strava

Every runner has that one friend or foe whose watch conveniently "glitches" right before the hill. Petty Strava puts a stop to the mystery. Petty Strava is all about transparency. See a killer session with 45 minutes of stoppage time? Find out the truth!

Upload a TCX export of a run and it digs through the raw timestamps to find every moment the watch actually stopped recording — not just slowed down, but genuinely went dark. Each pause gets called out with exactly when it happened, how long it lasted, and which mile marker it fell on.

**[Try it →](#)** *https://sydneyleiher.github.io/PettyStrava/*

## What it does

- **Finds real pauses.** It looks for gaps in the timestamp sequence itself — the difference between "ran a slow mile" and "watch stopped recording for 40 seconds"
- **Pins each pause to a mile marker.** If the file includes distance data, every flagged pause shows exactly where on the route it happened, not just the elapsed time.
- **Plots the whole run.** A speed-by-mile chart shows the shape of the effort, with each pause shaded right on the graph so you can see it in context.
- **Gives you a verdict.** Clean runs get stamped CLEAN. Runs with gaps get stamped PAUSED, with a running count of how many pauses turned up.

## Getting a file to upload

1. Install the **[Sauce for Strava](https://www.sauce.llc/)** browser extension (Chrome/Firefox) and sign in to Strava as usual.
2. Open the activity you're curious about — yours, or anyone's public activity.
3. Click the **Analysis** tab in the left sidebar.
4. Scroll to the **Data** section and click the **TCX** link next to "View: raw · graphs".
5. Drop that file into Petty Strava.

The app expects a standard TCX export with timestamped trackpoints.

## Privacy

Everything happens in your browser. The TCX file never leaves your machine or gets uploaded anywhere.
