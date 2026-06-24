# Curious Speaking

Offline English speaking practice web app for curious topics.

## What It Includes

- 40 prebuilt lessons for Season 1
- Random lesson flow that skips completed lessons
- Level filter
- Pattern Training
- Vocabulary with pronunciation symbols
- Automatic Response
- Expansion Challenge
- 30-second Final Speaking timer
- Temporary recording playback without saving audio files

## Files

```text
index.html
lessons.json
```

This app is fully static. It does not use an API key, backend server, database, or build step.

## Run Locally

From this folder:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://127.0.0.1:3000
```

## Deploy With GitHub Pages

1. Create a GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to `Settings` -> `Pages`.
4. Set source to `Deploy from a branch`.
5. Select the `main` branch and `/root`.
6. Save.

GitHub Pages will publish the app at the URL shown in the Pages settings.

## Updating Future Seasons

For a new season, update or extend `lessons.json`. The app reads lesson data from that file.
