# Screenshots

Drop PNGs here matching these names (case-sensitive):

- `hero.png` — main hero shot, monkey-29-determined-fist on onboarding screen 1 (or Screen 18 paywall page 1)
- `logging.png` — NoteEditor with drag-to-dial visible mid-drag
- `coach.png` — AI chat screen with at least one message exchange
- `monkey.png` — home dashboard showing the monkey companion
- `favicon.png` — 256x256 app icon
- `og-image.png` — 1200x630 social share card (logo + tagline + screenshot)

## How to capture (sim)
1. Open Xcode → Window → Devices and Simulators → boot iPhone 15 Pro Max
2. Run app in sim
3. Reach the screen you want
4. Cmd+S in sim (saves to Desktop) OR Device → Screenshot
5. Trim/rename to filenames above
6. Drop here, `git add screenshots/*.png && git commit && git push`

## Recommended size
- Source: 1290 × 2796 (iPhone 15 Pro Max native)
- Web display: HTML scales to ~320px wide via CSS, so source resolution provides 4× retina sharpness
- No need to resize; ~1.5 MB per PNG is fine
