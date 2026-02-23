# Qaz Personal Terminal

> A modern homage to the TRS-80 Model 100 — reimagined as a 33-key portable hacking terminal powered by the Raspberry Pi Compute Module 4.

---

## 🔧 What is this?

The **Qaz Personal Terminal** is a minimalist, portable hacking machine inspired by retro terminals like the Tandy Model 100. It's built around the **Raspberry Pi CM4**, exposing full GPIO access, USB, Wi-Fi, Bluetooth, and a compact 33-key mechanical keyboard layout based on the [Qaz](https://qmk.fm/keyboards/qaz/) form factor.

Perfect for:
- On-the-go terminal work
- Hardware hacking
- Tethered field ops
- Writing code in a ditch (probably)

---

## 📁 Repository Structure

```text
qaz-terminal/
├── 3d/                  # Fusion360 / STEP / STL files for enclosure
├── pcb/                 # KiCad schematics, layout, and fabrication files
├── renders/             # Product renders and screenshots
├── firmware/            # (optional) Firmware config for keyboard
├── docs/                # Assembly instructions, wiring diagrams, etc.
└── README.md
```

---

## 🧱 Features

- 🧠 **Compute Module 4 (CM4)** brain
- ⌨️ **33-key ortholinear keyboard** (Qaz-style)
- 🔌 **All IO pins exposed** (GPIO, UART, SPI, I2C)
- 📶 **Wi-Fi + Bluetooth onboard**
- 🧰 **USB ports** for debugging, flashing, or peripherals
- 📏 Compact, rugged enclosure with printed parts

---

## 📷 Renders

<p align="center">
  <img src="renders/render.png" width="400"/>
</p>

(See `/renders/` for all angles)

---

## ⚙️ 3D Enclosure

- Designed in **Fusion360**
- Exports available as **.STEP**, **.STL**, and **.F3D**
- Optimized for:
  - Printability (no supports required)
  - Snap-fit and screw-in parts
  - Ventilation and GPIO access

---

## 🔌 PCB Details

- Designed in **KiCad**
- Files include:
  - Schematic
  - Board layout
  - Gerbers & drill files
- Exposes:
  - 40-pin GPIO
  - 5V and 3.3V rails
  - USB
  - UART debug header

---

## 🖥️ Boot & Usage

1. Flash Raspberry Pi OS Lite (or custom image) to CM4
2. Connect via HDMI, SSH, or serial UART
3. Use any terminal, or customize for:
   - QMK firmware
   - Custom CLI tools
   - Field diagnostics

---

## 💡 Inspiration

The Qaz Personal Terminal is influenced by:
- TRS-80 Model 100
- Cyberdeck culture
- QMK & low-profile mechanical keyboards
- Minimalist UNIX workflows

---

## 📜 License

Open-source hardware & designs under **CERN-OHL-P v2**  
Documentation and code under **MIT License**  
*(See `/LICENSE.md` for full text)*

---

## 🛠️ Roadmap

- [ ] Optional battery support (LiPo + charging)
- [ ] Low-power display integration (OLED or epaper)
- [ ] Detachable antenna mod
- [ ] Bootloader flash jig
- [ ] Keyboard firmware configurator

---

## 🤝 Contribute / Fork

This project is a starting point — feel free to fork, remix, or help expand it.  
If you build one, [tag me](mailto:your@email.com) or drop a pull request!

---

