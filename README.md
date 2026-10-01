# Songsterr drums to Moonscraper

Single-page browser app that converts a Songsterr drum MIDI plus the song's MP3 into a Clone Hero-ready package: a pro drums Expert `notes.mid` and a `song.ogg`, both with 2 seconds of lead-in silence.

## Usage
1. Open `index.html` in a recent Chrome or Edge (audio encoding needs WebCodecs).
2. Choose the Songsterr MIDI and the MP3, then click Analyze.
3. Adjust the audio start if needed and preview with clicks.
4. Download the zip, unzip into a song folder, and open `notes.mid` in Moonscraper.

## Status
- Pro drums, Expert only.
- Test song: The Cranberries - Zombie.
- Planned: hybrid mode that keeps the Songsterr MIDI timing and uses a Guitar Pro file for tom, crash and china info (all hi-hats treated as closed).
