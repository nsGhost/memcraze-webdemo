# MemCraze — Web Playtest Build

A browser-playable WebGL build of **MemCraze**, a memory/matching card game, published for playtesting.

## ▶ Play

**https://nsghost.github.io/memcraze-webdemo/**

Desktop browser recommended. Click a card to flip it and find the matching pair.

## Notes for playtesters

- **First load is slow.** Compression is disabled so the build works on static hosting without server configuration, which means a larger initial download. Give it a moment on first visit.
- **Audio** may require a click anywhere on the page first — browsers block autoplay until the user interacts.
- **Ads are disabled.** The game's ad integration (LevelPlay) is mobile-only; on web it's a no-op and rewards are granted directly.
- **Progress is saved locally** in browser storage, so clearing site data resets your run.

## What's in this repository

Only the compiled WebGL output — `index.html`, `Build/`, and `TemplateData/`. This is a
build-artifact repository; the game's source lives in a separate private repository.
