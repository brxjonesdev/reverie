# Reverie 

A Progressive Web App for capturing and organizing musical ideas. Record melodies, write lyrics, and build song structures — all in your browser.

## Features

### Phase 1: Core Capture
- Audio recording with waveform visualization
- Lyrics editor with section markers (Verse, Chorus, Bridge)
- Speech-to-text transcription for lyrics
- Real-time pitch detection for melody capture
- Tag songs with emojis
- Search by keywords and tags

### Phase 2: Creative Tools
- Chord progression generator (presets + custom)
- BPM detection
- Song structure builder (drag-and-drop sections)
- Time-stamped comments on recordings

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Styling:** Tailwind CSS
- **Audio:** Web Audio API, Tone.js
- **Pitch Detection:** Pitchy
- **Waveforms:** Wavesurfer.js
- **Storage:** IndexedDB (via idb)
- **PWA:** next-pwa

## Recording Modes

**Lyrics Mode:** Captures spoken/sung words and transcribes to text
- Uses Web Speech API for real-time transcription
- Perfect for capturing lyrical ideas on the fly

**Melody Mode:** Detects pitch and converts humming/singing to MIDI notes
- Real-time pitch detection shows current note
- Captures note sequences with timing and duration
- Monophonic (one note at a time)

**Both Mode:** Records audio while simultaneously transcribing lyrics AND detecting melody

## Roadmap

### Phase 3 (Future)
- Multi-track recording
- Custom rhythm builder
- In-app mixing (levels, EQ, reverb)
- Export to MIDI/audio files
- Cloud sync

## Contributing

Contributions welcome! Please open an issue first to discuss what you'd like to change.

## License

MIT
