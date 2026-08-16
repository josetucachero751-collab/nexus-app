Place real onboarding audio and SFX files here if you prefer real files over the built-in synth fallback.

Recommended files and paths (relative to the project root):
- assets/audio/onboarding.mp3    --> background music/ambience (looping)
- assets/audio/scene-next.mp3    --> short next-scene SFX (0.15-0.4s)
- assets/audio/scene-back.mp3    --> short back SFX (0.15-0.4s)

Notes:
- Update the ONBOARDING_AUDIO.src and ONBOARDING_SFX.next/ back values in index.html to point to these files.
- Browsers may block autoplay; playback will be attempted after a user gesture (e.g., clicking "Entrar al laboratorio").
- Prefer compressed formats (mp3, webm, ogg) for smaller size.
