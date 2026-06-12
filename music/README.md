# Hexagon Music

Drop your track files in this folder. File names must match exactly what is listed in `tracks.json`.

## Preferred format
- **OGG Vorbis at 96 kbps** -- best size/quality ratio
- MP3 at 128 kbps as fallback

## Adding a new track
1. Encode your file as `.ogg` (96 kbps recommended)
2. Place it here: `music/your-track-name.ogg`
3. Add an entry to `tracks.json`:

```json
{
  "id":     "your-track-name",
  "title":  "TRACK TITLE",
  "artist": "Artist Name",
  "bpm":    140,
  "vibe":   "Phonk",
  "file":   "music/your-track-name.ogg"
}
```

## Vibe tags
| Tag | Description |
|-----|-------------|
| `Phonk` | Dark phonk, trap-influenced, heavy 808s |
| `Dubstep` | Heavy bass, drops, aggressive |
| `Synthwave` | Darksynth, cinematic, synth-heavy |

## Note on placeholder tracks
The `.ogg` files listed in `tracks.json` do not exist yet -- this is intentional.
The app skips tracks whose files are missing. Replace with real files when ready.