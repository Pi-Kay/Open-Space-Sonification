# Open Space Data Sonification

Translating NASA moon crater data into sound and motion — an exploration of how sonification can enhance perception of scientific data.

## Project Overview

This project maps physical properties of lunar craters to audio and visual parameters, creating an interactive experience that reveals patterns in NASA's crater database through multiple sensory channels.

**Parameter Mapping:**
- Crater diameter → pitch (inverted: larger = lower, 110–330 Hz) + duration
- Latitude/longitude → impact position
- Volume scaled to crater size

## Files

| File | Description |
|------|-------------|
| `open-space-sonification-3.html` | Interactive visualization and case study |
| `OpenSpaceNotebook.ipynb` | Python data processing and MIDI generation |
| `moon_craters_small_20.csv` | Source data from NASA Moon Crater Database |
| `SonProjectMoon2.mid' | MIDI File output |
| `OpenSpaceAudio.mp3` | Logic Pro composition from MIDI output |
| `sketch1.2.png, sketch1.3.png, sketch1.10.png` | Data analysis visualizations |

## Tools & Technologies

- **Data Processing:** Python, NumPy, Pandas, Matplotlib
- **MIDI Generation:** midiutil
- **Audio Production:** Logic Pro
- **Visualization:** JavaScript, Web Audio API, HTML5 Canvas
- **AI Collaboration:** Claude, Grok (code structure, iteration)

## Key Insight: AI-Human Collaboration

During development, I identified pitch values that weren't correctly correlated with crater sizes. AI-generated code required human verification to ensure perceptual accuracy. This iterative process highlighted complementary strengths: AI excels at code structure and math; human perception catches relationship inconsistencies.

## View Live

[Add your hosted URL here]

## Author

Petra Kühnle

## License

MIT
