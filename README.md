# Recall – offline spaced-repetition study tracker (PWA)
Static, no build step. Data stays in your browser (IndexedDB via Dexie, vendored).

## Deploy (GitHub Pages)
Repo Settings → Pages → Deploy from branch → `main` / root. Open `https://mavprac.github.io/revise1/` in Android Chrome, wait for it to load once, then menu → Install app / Add to Home screen.

## Verify offline
After installing, enable airplane mode and open the app; add a topic and review one.

## SRS rules
Intervals 1,3,7,14,30 days, then previous × ease. Forgot: reset, 1 day, ease −0.20. Hard: ×1.2, ease −0.15, stage kept. Good: next stage. Easy: next stage ×1.3, ease +0.15. Ease min 1.30. Next review counts from the actual review date. Mastery = min(successful revisions,5)/5.

## Backup
Settings → Export JSON regularly; Import supports replace or merge.
