# Steel Heat Treatment / Surface Process Decision Engine

A Windows-based engineering decision-support tool for selecting suitable **heat treatment and surface processes** based on material properties, constraints, and user priorities.

This tool is designed for **early-stage engineering decisions**, trade-off analysis, and comparative process evaluation — not for final certification or simulation.

---

## 🔧 What This Tool Does

- Evaluates heat treatment and surface processes for steels
- Applies metallurgical constraints automatically
- Ranks feasible processes based on user-defined priorities
- Explains *why* a process scores well or poorly
- Generates bar and radar charts for property trade-offs
- Supports material-to-material comparison

---

## 🖥️ Installation (Windows)

1. Download the latest installer from **Releases**
2. Run `SteelDecisionEngine_Setup_vX.X.X.exe`
3. If Python is not installed:
   - The installer will prompt you
   - A Python installer is provided
   - Install Python and rerun the app installer
4. Launch the app using the desktop or Start Menu shortcut

✔ No command line required  
✔ No manual setup after install  

---

## 🚀 Launching the Application

- Open **Steel Heat Treatment Decision Engine** from desktop or Start Menu
- Click **Launch Application**
- The UI opens automatically in your browser at:
http://localhost:8501
---

## 📂 Output Files

All generated plots are saved automatically to:
C:\Users<username>\AppData\Local\SteelDecisionEngine\outputs

Each material gets its own folder with bar and radar charts.

---

## ➕ Extending the Engine (Advanced Users)

You can add your own materials and processes using CSV files:

data/user/user_materials.csv
data/user/user_processes.csv

Rules:
- Do not modify column headers
- Leave unused numeric fields empty
- Restart the application after changes

---

## ⚠️ Disclaimer

This tool:
- Does NOT perform thermodynamic simulation
- Does NOT replace standards or certification
- Is NOT a substitute for expert metallurgical review

It is intended for **decision support**, comparison, and early-stage analysis.

---

## 📄 License

See `LICENSE.txt`
