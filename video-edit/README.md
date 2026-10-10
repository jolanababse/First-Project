# IMG_1380 – edited with HyperFrames

`IMG_1380-edited.mp4` (1080×1920, 13.8 s): the final render.

What was done:
- **Background**: subject cut out with `hyperframes remove-background`, then placed on a new animated set (purple/blue gradient, drifting color glows, breathing key light, light sweeps, perspective floor grid, giant outlined "ICON" behind the subject).
- **Light**: warmer, brighter portrait grade (lifted shadows, softer highlights, +warmth) baked into the cut-out, plus a thin rim light.
- **Motion**: intro push-in, punch-ins on each beat, slow drift zooms, white flash accents on the cuts.
- **Text**: "REAL TALK" hook → "Listen to this" pill → "STAY WITH ME" → "DON'T MISS IT" + FOLLOW button.

`index.html` is the HyperFrames composition. To re-render, put the media next to it
(`voice.m4a` = original audio, `person_graded.webm` = graded cut-out) and run
`npx hyperframes render -o renders/final.mp4`.
