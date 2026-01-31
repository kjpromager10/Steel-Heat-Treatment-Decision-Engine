# Changelog

## v1.0.1 — Installer & Deployment Stabilization (Current)

### Added
- Windows installer (Inno Setup) with desktop and start-menu shortcuts
- GUI-based application launcher
- Automatic detection of Python installation
- Guided Python installation workflow for systems without Python
- Persistent user output storage in Local AppData
- Material comparison mode (Best vs Best & Manual)
- Clear output file structure and documentation
- User-extensible materials and processes via CSV files

### Changed
- Output files are now stored in:
C:\Users<username>\AppData\Local\SteelDecisionEngine\outputs
- Application no longer writes to Program Files
- Launcher runs Streamlit in background thread (prevents UI freezing)
- Installer no longer attempts silent Python installation (manual install is prompted instead)
- UI content reorganized for clarity and stability

### Fixed
- Permission errors when running from Program Files
- Streamlit GUI freezing during startup
- Missing dependency issues on fresh systems
- Installer failures on systems without Python
- Output folder access issues
- Missing UI pages after deployment

---

## v1.0.0 — Initial Engine Release

- Core decision engine implemented
- Single-material evaluation
- Constraint-based process filtering
- Weighted scoring and ranking
- Visualization generation (bar + radar charts)
- Streamlit-based UI (development use)
