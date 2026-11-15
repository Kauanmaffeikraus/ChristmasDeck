# 🎄 Christmas Deck — SteamOS CSS Loader Theme

![Manifest Version](https://img.shields.io/badge/Manifest_Version-9-c41e3a?style=flat-square)
![Target](https://img.shields.io/badge/Target-System--Wide-0f3d29?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-f5c542?style=flat-square)

**Christmas Deck** is a complete, modular system-wide holiday theme for **SteamOS Gaming Mode** (Steam Deck, Bazzite, and Big Picture Mode), built for [Decky Loader](https://decky.xyz/) and [CSS Loader (DeckThemes)](https://deckthemes.com/).

It transforms the entire Steam Gamepad UI—Home, Library, Main Menu, Quick Access Menu (`...`), Settings, Notifications, and Virtual Keyboard—into a cozy Christmas atmosphere with rich holiday palettes, animated string lights, and GPU-friendly snowfall.

---

## ✨ Key Features

- 🎨 **5 Color Palettes + Live Color Pickers**: Choose between *Traditional Christmas (Pine & Ruby)*, *Santa's Velvet (Crimson & Gold)*, *Frozen Winter (Ice Blue & Silver)*, *Gingerbread (Cinnamon & Gold)*, or create your own using 4 built-in interactive color pickers.
- ❄️ **Adjustable 3D Snowfall**: Pure CSS GPU-accelerated falling snow with selectable intensity (*Off*, *Gentle Snow*, *3D Dual-Layer Blizzard*, or *Magic Golden Snow*).
- 💡 **Animated Christmas String Lights**: Twinkling holiday lights along the top header bar (*Colorful Animated* or *Warm Golden Fairy Lights*).
- 🍬 **Festive Game Card Focus**: Highlight focused games with a warm ruby-and-gold glow or a striped **Candy Cane Border**.
- ⌨️ **Christmas Virtual Keyboard**: Customizes the default SteamOS virtual keyboard with pine green keys, ruby modifiers, and a golden Enter key.
- 🔔 **Full System Coverage**: Styles the Steam Main Menu, Quick Access Menu (`...`), Settings pages, toggle switches, sliders, buttons, tabs, header, footer, and toast notifications.

---

## ⚙️ Customization Options (Patches)

All options can be configured directly inside the **CSS Loader** Quick Access Menu:

| Option | Type | Choices | Default |
| :--- | :--- | :--- | :--- |
| **Color Palette** | `dropdown` + `color-picker` | `Traditional Christmas (Pine & Ruby)`, `Santa's Velvet (Crimson & Gold)`, `Frozen Winter (Ice Blue & Silver)`, `Gingerbread (Cinnamon & Gold)`, `Custom (Color Picker)` | `Traditional Christmas (Pine & Ruby)` |
| **Snowfall Intensity** | `slider` | `Off`, `Gentle Snow`, `Blizzard (3D Dual Layer)`, `Magic Golden Snow` | `Blizzard (3D Dual Layer)` |
| **Header Christmas Lights** | `dropdown` | `Animated Colorful Lights`, `Warm Golden Fairy Lights`, `Off` | `Animated Colorful Lights` |
| **Game Card Focus Style** | `dropdown` | `Festive Glow + Zoom`, `Candy Cane Border`, `Subtle (No Zoom)` | `Festive Glow + Zoom` |
| **Corner Roundness** | `slider` | `Sharp (6px)`, `Default (12px)`, `Rounded (18px)`, `Pill (24px)` | `Default (12px)` |
| **Footer Style** | `dropdown` | `Festive Full Bar`, `Minimal Transparent`, `Hidden` | `Festive Full Bar` |
| **Christmas Virtual Keyboard** | `checkbox` | `Yes`, `No` | `Yes` |

---

## 📦 Installation

### Prerequisites
- [Decky Loader](https://decky.xyz/) installed on your device.
- **CSS Loader** plugin installed via the Decky Plugin Store.

### Manual Installation via Terminal
1. Switch to **Desktop Mode** (or connect via SSH) and clone this repository into your `homebrew/themes` directory:
   ```bash
   cd ~/homebrew/themes
   git clone https://github.com/YOUR_USERNAME/ChristmasDeck.git
   ```
2. Return to **Gaming Mode**.
3. Open the **Quick Access Menu (`...`)** → **CSS Loader**.
4. Click the **Reload (🔄)** button at the top of CSS Loader and enable **Christmas Deck**.

---

## 📁 Repository Structure

```text
ChristmasDeck/
├── theme.json                 # Manifest v9 configuration, patches, and color-picker components
├── christmas.css              # Core system-wide stylesheet and CSS variables
├── README.md                  # Documentation
├── LICENSE                    # MIT License
└── css/
    ├── card-candycane.css     # Diagonal candy-cane border for focused game tiles
    ├── footer-hidden.css      # Option to hide the bottom footer bar
    ├── footer-minimal.css     # Option for a transparent gradient footer
    ├── keyboard.css           # Festive styling for the default SteamOS virtual keyboard
    ├── lights-colorful.css    # Animated multi-color string lights on the header
    ├── lights-gold.css        # Warm golden fairy lights on the header
    ├── snow-blizzard.css      # Secondary parallax snow layer for blizzard mode
    ├── snow-golden.css        # White and golden sparkling snowfall
    └── snow-normal.css        # Base gentle snowfall layer
```

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.
