# WERSI Drum Composer CX 5 – English User Manual

An English translation of the original German user manual for the WERSI Drum Composer CX 5 drum machine, presented as an interactive web documentation using Docsify.

## Online Documentation
Visit here - [WERSI CX-5 MANUAL](https://danielmroczek.github.io/wersi-cx5-manual/)

## About This Project

The WERSI Drum Composer CX 5 is a sophisticated drum machine from the 1980s with comprehensive programming capabilities, MIDI support, and expandable rhythm libraries. This project provides a modern, searchable English translation of the original manual (BA 392), making this classic instrument's documentation accessible to English-speaking users.

### Key Features Documented

- **128 programmable rhythms** (64 factory + 64 user-programmable)
- **27 percussion instruments** (26 digital + 1 analog Synthedrum)
- **Full MIDI integration** (clock sync, note transmission, program change)
- **8 drum pads** with velocity dynamics and preset management
- **Sequencer** with up to 16 sequences (432 bars total)
- **Data archiving** via cassette tape and RAM cartridge
- **Multi-track synchronization** with tape-based recording systems

## Getting Started

### Viewing Online

The manual is published as an interactive web documentation site. Open `index.html` in your browser or visit the hosted version.

### Local Development

This project uses [Docsify](https://docsify.js.org/) for documentation rendering.

**Requirements:**
- A modern web browser
- Optional: A local web server (for best results)

**Setup:**

```bash
# Clone or download this repository
cd wersi-cx5-manual

# Serve locally (Python)
python -m http.server 8000

# Or using Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Project Structure

```
wersi-cx5-manual/
├── manual.md              # Complete English translation of the manual
├── index.html             # Docsify configuration and entry point
├── README.md              # This file
├── back.png               # Rear panel diagram
├── buttons.png            # Front panel button reference
├── screen.png             # Display and pad layout reference
└── favicon.svg            # Project favicon
```

## Documentation Contents

The manual covers:

- **Preface & Capabilities** – Overview of rhythm storage, instruments, and key features
- **Preparations** – Power connections and audio setup
- **Basic Configuration** – Essential operations (rhythm selection, tempomat, effects)
- **Full Configuration** – Advanced features including:
  - Programming rhythms with custom time signatures
  - Creating sequences
  - Cartridge management
  - Drum pads and pad presets
- **Cassette Tape I/O** – Data backup and restoration
- **Synchronization** – Tape sync and MIDI integration
- **MIDI Reference** – Complete MIDI implementation guide
- **Button Reference** – Interactive cheatsheet for all 35 control panel buttons

## Features

✓ **Searchable content** – Quickly find information with full-text search  
✓ **Mobile-friendly** – Responsive design works on phones and tablets  
✓ **Dark mode support** – Easy on the eyes with built-in theme switching  
✓ **Structured navigation** – Organized sections with cross-references  
✓ **Tables and diagrams** – Instrument listings, MIDI note mappings, and panel layouts  

## Translation Notes

- This is an English translation of the original German manual (Manual No. BA 392)
- The translation preserves technical accuracy while adapting terminology for English speakers
- All instrument names, MIDI mappings, and technical specifications match the original
- Software version references (V2.0, V2.2) are from the original documentation

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- IE11: Not supported

## Known Limitations

- This documentation is based on the original CX 5 specification
- Software versions may vary slightly from the hardware versions
- Some vintage references (e.g., Commodore 64) reflect the original manual's era
- MIDI implementation follows the standard as defined in the original manual

## Attribution

- **Original Manual:** WERSI-electronic GmbH & Co. KG
- **English Translation:** Community project
- **Documentation Platform:** [Docsify](https://docsify.js.org/)
- **Theme:** Docsify Dark Light Theme

## Resources

- **Instrument Specifications:** See "Instruments and Sounds" section
- **Control Panel Reference:** See "Cheatsheet – Button Reference" with all 35 buttons documented
- **MIDI Implementation:** Complete mapping in "M.I.D.I." section including:
  - MIDI note numbers (36–64) for all percussion sounds
  - Clock synchronization modes
  - Program change message formats

## Support

For questions about:
- **WERSI CX 5 operation:** Refer to the manual sections in this documentation
- **Translation accuracy:** Check the original German manual (if available)
- **Docsify platform:** Visit [Docsify documentation](https://docsify.js.org/)

---

**Original Manual No.:** BA 392  
**Last Updated:** February 2, 2026

