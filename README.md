# hsa

Static audio hosting for the human study.

## GitHub Pages setup

1. Push this repository to GitHub.
2. Open `Settings -> Pages`.
3. Set:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/docs`
4. Wait for the Pages URL to appear.

## Published structure

- `docs/index.html`: quick manual playback page
- `docs/audio/A01.wav` to `docs/audio/A15.wav`: direct audio assets
- `docs/audio_mapping.csv`: local mapping table

## Questionnaire usage

Use direct audio URLs like:

`https://WhiskerSage.github.io/hsa/audio/A01.wav`

Do not send participants to `index.html` unless you explicitly want a manual check page.
