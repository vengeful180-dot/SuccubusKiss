# Succubus Kiss

An animated succubus, Lilith, who blows a kiss at the camera. It's a single self-contained HTML page with no build step and no dependencies.

Open `index.html` in a browser, tap **Summon**, and turn your sound on.

## What happens

- **0–3 s:** She appears. Glowing eyes open in the dark, a magic circle lights up, and her wings unfurl.
- **3–5.4 s:** She smirks, leans in toward the camera, and closes her eyes.
- **5.4 s:** The kiss. Her lips hit the "glass" and leave a lipstick print, with a flash and a burst of hearts.
- **6.5–10 s:** She pulls back, winks, and blows a glowing heart at you.
- **After 10 s:** She stays in an idle loop. She breathes, blinks and hovers in time with her wing beats, her hair and wings sway, and her eyes follow your cursor. Every few seconds she does a random gesture: a wink, a wing flap, a playful shimmy, a head tilt, a blown heart, or a glance away.

Her bust is driven by a small spring simulation, so it bounces and settles naturally when she moves, flaps or shimmies.

Tap anywhere for another kiss. The buttons in the top right mute the sound or replay from the start.

## Sound

All audio is synthesized at runtime with the Web Audio API. That covers the heartbeat, wing flaps, choir, the kiss, chimes, and the ambient music. There are no audio files to load.

## Previewing a single frame

Add `#t=<seconds>` to the URL to freeze the animation at that moment, for example `index.html#t=5.4`. Audio is off in this mode.
