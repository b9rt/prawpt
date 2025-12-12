# Prawpt — A privacy-first teleprompter that finally keeps your eyes on the camera  
A fast, local-only teleprompter app for macOS.  
Built for creators, founders, streamers, and anyone who wants to look confident on camera without memorizing lines.

Prawpt listens to your delivery, scrolls with your voice, and keeps your script exactly where your eyes already are.

![Prawpt Screenshot](docs/screenshot.png)  
*(Placeholder — add an app screenshot here when ready)*

---

## 🚀 Why Prawpt?
Most teleprompters are slow, ugly, or shove your script miles away from the lens.  
Prawpt does the opposite:

### **• Voice-reactive smooth scroll**  
The text moves with your delivery — not on a timer.

### **• Hover-to-pause + tap-to-resume**  
Feels like controlling a prompter with telekinesis.

### **• Ultra-light build**  
Opens instantly. Barely touches your CPU. Runs fully offline.

### **• Local-only**  
Nothing leaves your machine. No tracking. No cloud anything.

### **• Keyboard-first workflow**  
Start, pause, speed adjustments — everything is shortcut-friendly.

---

## 🧪 Features (v0.1.0)

- Voice-reactive scrolling  
- Adjustable speed, font size, margins  
- Mirroring mode  
- Instant paste-and-format  
- Hover-to-pause  
- Hidden cursor mode  
- Ultra-low latency renderer  
- Full privacy (no network requests, no analytics)  
- macOS DMG available via GitHub Releases  

Upcoming:  
- Virtual Camera (Pro)  
- Eye-lens overlay mode  
- Script management  
- Presenter notes  
- Auto-format blocks & headings  

---

## 💻 Installation (macOS)
Download the latest `.dmg` from:

👉 **https://github.com/b9rt/prawpt/releases/latest**

Drag Prawpt into Applications and launch it.

If macOS warns you about an unidentified developer:  
Right-click → Open → Open.

(Prawpt notarization and code-signing will be added soon.)

---

## 🔐 Security & Privacy
Prawpt is designed privacy-first.

- No cloud APIs  
- No telemetry  
- No tracking  
- No accounts  
- No internet connection required  
- Script processing happens 100% locally  

### SHA-256 checksums  
Checksums for every build are published in GitHub Releases.  
You can verify with:
shasum -a 256 prawpt.dmg

## 🛠 Development

Prawpt is built with:
- Tauri (Rust + TypeScript)
- Vite
- WebGL renderer for ultra-smooth text rendering
- Rust audio engine for voice-reactive scrolling

## 📡 Roadmap
- Virtual Camera (Prawpt Cam Pro)
- Lens-overlaid script view
- Multi-script project system
- Auto-formatting (markdown-like)
- Windows + Linux support
- Custom themes
- Auto-update channel

## 🧑‍💻 Creator
Designed & built by Bart Andrzejewski
https://bartbeyond.art
