# Universal Room Control for Home Assistant

A comprehensive "Interface Usability Language" for Z-Wave switches (specifically Inovelli). This blueprint standardizes how lights and fans behave across your home.

## 🚀 Recommended: Unified Blueprint

**File:** [`unified_room_control.yaml`](unified_room_control.yaml)

This single blueprint handles both standard switches and combo fan/light switches. It automatically forces `al_sleep_mode` to **OFF** when you turn lights on to prevent accidental "Night Mode" during the day.

**Supported Models:**
1. **Inovelli Red Series On/Off (LZW30-SN)**: Select "Standard" profile.
2. **Inovelli Fan/Light Combo (LZW36)**: Select "LZW36" profile.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint URL pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fkhaosx%2Fhome-assistant%2Fblob%2Fmain%2Funified_room_control.yaml)

---

## ⚠️ Deprecated Blueprints

The following blueprints are deprecated. Logic from these has been merged into the Unified Blueprint above.

- **`universal_room_control_lzw30sn.yaml`**: Legacy Up/Down logic for LZW30-SN.
- **`universal_room_control_lzw36.yaml`**: Legacy logic for LZW36.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
