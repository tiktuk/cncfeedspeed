# CNC Feeds & Speeds Calculator

A modern, user-friendly web calculator for determining optimal spindle speed (RPM) and feed rate (mm/min) for CNC machining, based on material, cutter diameter, number of teeth, and machine limits.

## Features
- Select from common materials (aluminium, wood, plastic, brass, steel, etc.)
- Enter cutter diameter and number of teeth
- Specify your machine's maximum spindle speed
- Optional multiplier for fine-tuning
- Instantly calculates spindle speed and feed rate
- "Advanced" toggle for recommended cutting speed and chip load
- Reference table and formula explanations
- Most values sourced from [Sorotec's cutting data PDF](https://www.sorotec.de/webshop/Datenblaetter/fraeser/schnittwerte_en.pdf)
- Clean, responsive UI powered by [Pico.css](https://picocss.com/)

## Usage
1. Open `index.html` in your browser (no installation required).
2. Fill out the form with your material, tool, and machine details.
3. Click **Calculate** to view results.
4. Use **Show Advanced** and **Show Reference** for more info.

## Development
- All logic and UI are in `index.html`.
- No build step or dependencies required.

## License
This project is open source and free to use. See [LICENSE](LICENSE) if present.
