# ZX81 Rev C – KiCad 9 Conversion

This repository contains a KiCad 9 conversion of the **Bluescreen2000 ZX81 Rev C** schematic and PCB. Originally designed in Eagle, this version has been fully migrated to KiCad for improved accessibility, maintainability, and future-proofing.

## 🔧 Project Highlights

- ✅ Full schematic and PCB layout migrated to **KiCad 9**
- 📦 Includes an **interactive BOM (iBOM)** for streamlined assembly and part sourcing
- 🧩 Preserves original routing and component placement for legacy compatibility
- 🛠️ Modular file structure for easy editing and future expansion

## 📁 File Overview

- `zx81-c.kicad_sch` – KiCad 9 schematic
- `zx81-c.kicad_pcb` – KiCad 9 PCB layout
- `zx81-c.kicad_pro` – KiCad project file
- `zx81-c.kicad_prl` – Project local settings
- `zx81-c-eagle-import.kicad_sym` – Symbol library from Eagle import
- `sym-lib-table` – Symbol library table
- `fp-info-cache` – Footprint cache
- `bom/` – iBOM files for interactive part placement and sourcing

## 📦 iBOM Integration

This project includes an iBOM (interactive BOM) generated from the KiCad layout. To view it:

1. Open the `bom/` folder.
2. Launch the HTML file in your browser.
3. Use the interactive interface to identify components, placement, and sourcing info.

For more on iBOM, visit the [iBOM GitHub page](https://github.com/openscopeproject/InteractiveHtmlBom).

## 🧠 Notes

- This conversion retains the original ZX81 Rev C design intent while enabling modern workflows.
- All files are compatible with KiCad 9.x and later.
- Contributions and forks welcome—especially for modular enhancements or enclosure integration.

## 🙌 Credits

- Original design by [bluescreen2000](https://github.com/bluescreen2000)
- KiCad 9 conversion and iBOM integration by [jgratton72](https://github.com/jgratton72)

---

Feel free to open issues or submit pull requests for improvements, documentation, or hardware compatibility overlays.
