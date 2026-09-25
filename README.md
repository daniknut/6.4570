# Windward Soundboard

A simple web page that plays sounds from four directions: north (ahead), east (right), south (behind) and west (left). Use headphones.

## Run it

Browsers won't load the sound files if you open the page straight from disk, so start a small local server in this folder:

```
python3 -m http.server
```

Then open http://localhost:8000/soundboard.html.

## Use it

- Each row is a sound, and each column is a direction. Click a button to play that sound from that direction.
- **Wind** keeps playing until you click it again. **Stop wind** turns off every wind.
- The slider sets the volume.

## Files

- `soundboard.html`: the soundboard
- `windward.html`: the original full version (compass, map and quiz)
- `sounds/`: the recordings, all CC0. `sounds/SOURCES.md` lists where each one came from.
