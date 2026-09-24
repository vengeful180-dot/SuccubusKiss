# Succubus Kiss

An animated succubus, Lilith, who blows a kiss at the camera. It's a single self-contained HTML page with no build step and no dependencies.

Open `index.html` in a browser, tap **Summon**, and turn your sound on.

## What happens

- **0–3 s:** She appears. Glowing eyes open in the dark, a magic circle lights up, and her wings unfurl.
- **3–5.4 s:** She smirks, leans in toward the camera, and closes her eyes.
- **5.4 s:** The kiss. Her lips hit the "glass" and leave a lipstick print, with a flash and a burst of hearts.
- **6.5–10 s:** She pulls back, winks, and blows a glowing heart at you.
- **After 10 s:** She stays in an idle loop. She breathes and blinks, her hair and wings sway, and her eyes follow your cursor. Every few seconds she does a random gesture: a wink, a wing flap, a playful shimmy, a head tilt, a blown heart, a glance away, licking her lips, sticking her tongue out with a wink, or a sultry look with a teasing line in a speech bubble.
- **Every so often:** She leans in for another kiss on her own.
- **After 2–3 kisses:** She puts her bare feet up toward the camera, and the camera pulls back to show her sitting on a velvet sofa in a short dress, leaning back on her hands, with candles around her. She holds that pose, wiggles her toes and gives the camera a couple of playful boops. Then the camera returns to the close-up and the loop starts again.

Her bust and skirt are driven by small spring simulations, so they bounce and sway naturally when she moves, flaps her wings, or shimmies.

## Interaction

- **Tap anywhere** for another kiss.
- **Tap her ears** to make them twitch, or **press and drag** to tug on one. She blushes, giggles, and answers with a flirty line.
- The buttons in the top right mute the sound or replay from the start.

## Sound

All audio is synthesized at runtime with the Web Audio API. That covers the heartbeat, wing flaps, choir, the kiss, giggles, chimes, and the ambient music. There are no audio files to load.

## Previewing a single frame

Add `#t=<seconds>` to the URL to freeze the animation at that moment, for example `index.html#t=5.4`. Add `&g=feet&gt=<seconds>` to also freeze the sofa scene at that point, for example `index.html#t=14&g=feet&gt=5.5`. Audio is off in these modes.
