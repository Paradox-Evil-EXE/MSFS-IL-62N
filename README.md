# IL‑62N – Native IL‑62 for Microsoft Flight Simulator

A lightweight, community-driven rebuild of the legendary Soviet IL‑62 as a **native MSFS aircraft**. Based on a legacy FSX import, the goal is to restore flight stability, build a working cockpit, and keep the flying fridge alive — without overcomplicating it.

> Bringing the infamous bird back from the dead, in a modern flight simulator

---

## 🚧 Current Status
- ✅ Imported model loads in MSFS
## ❌ Problems
- No working cockpit instruments
- No native flight systems or WASM logic
- Reversers deploy *automatically* at rotate and/or other moments on the ground (yes, really, not all the times either, worth checking out)
- Engine randomly goes to idle on runway sometimes
- Flaps sometimes retract without command during takeoff roll sometimes
## ✅ Fixed
- Barely any lift power, struggles to takeoff  
  - Increased `lift_scalar` to `1.200` for `[FLAPS.0]`  
  - Increased `thrust_scalar` to `1.250` for `[JET_ENGINE]`

---

## 🛠️ Goals
- Slight cockpit remodel to house usable gauges
- Rewrite engine logic for correct thrust behavior
- Animate and implement working instruments
- Fix weird flap/autothrottle bugs
- Keep it simple, clean, and fun — no overengineered bloat

---

## **⚠️ Heads up**:
This is a zero-budget project. I’m broke, you’re broke (probably), the IL-62 is broke(n) — we’re all here just to make something cool happen. No payments, just credit and community, and the sight of the great bird in the air again.


---

## 🤝 How to Help
Looking for contributors who can help with:
- 3D cockpit modeling (just tweaks, not a full redo)
- Flight model tuning & engine config
- Gauge/instrument animation
- Replacing legacy FSX behavior with native MSFS systems
- If you want to try editing or flying it yourself, [download the current version here via The mirror](https://drive.google.com/file/d/1XArml0h0QlA1kpqCrtPvFI85L_47ZvMp/view?usp=sharing).  
  - This link will be kept updated to match the fixes and problems listed in this README.
  - [Original file incase something goes wrong](https://drive.google.com/file/d/1XArml0h0QlA1kpqCrtPvFI85L_47ZvMp/view?usp=sharing)


Join our [Discord](https://discord.gg/x52mwgyCBU) to get involved.  
Contribute via GitHub pull requests or submit issues directly. Or by contacting me to get added to this repository

---

## 📦 Licensing

This project is currently in a **pre-license phase**. All content is intended for educational and non-commercial use only. If you are the original creator of any legacy assets used here, please reach out via GitHub or Discord to confirm licensing or request removal.

---

*This project is 100% community-led and open-source. There is no paid version, no bloat, and no promises — just progress.*
