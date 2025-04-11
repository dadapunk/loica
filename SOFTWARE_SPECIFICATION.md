
# 🧾 Software Specification Document – Loica

## Project Title: **Loica**

### Version: 1.0.0  
### Document Version: 1.0  
### Last Updated: 2025-04-11  
### Author: Dadapunk  

---

## 🧭 Purpose

Loica is a local and open source rate calculator designed for freelance professionals who charge based on quantifiable units such as words, pages, minutes, or custom metrics. The software simplifies price estimation, project tracking, and quote generation in an offline, privacy-respecting environment.

---

## 🧑‍💻 Target Users

- Translators
- Proofreaders / Editors
- Transcriptionists
- Voice-over artists
- Language teachers
- Designers or creatives working per-piece/hour
- Freelancers using non-standard billing units

---

## 🧱 System Requirements

### Platform Compatibility:
- Windows 10+
- macOS 12+
- Linux (Ubuntu 20.04+ or equivalent)

### Dependencies:
- Python 3.10+
- PySide6
- SQLite
- ReportLab

---

## 🧩 Functional Requirements

### Unit System:
- Allow users to define units: word, page, minute, hour, character, custom
- Associate rates per unit
- Support multiple rates (per client or project type)

### Project Management:
- Create projects with title, client, unit count
- Auto-calculate total based on selected rate/unit
- Add project notes and status (draft, sent, approved, paid)
- Store project history and allow filtering/searching

### Client Management:
- Add/edit/remove clients
- Assign specific rate presets per client
- View client-specific project history

### Quote Generator:
- Create professional-looking PDF quotes
- Export or print directly
- Optional company logo and tax fields

### Unit Converter:
- Convert between unit types (e.g., words ↔ quartillas)
- Allow user-defined conversion ratios

### Reporting:
- Summary by date range, client, or project type
- Export report as CSV

### Security & Privacy:
- All data stored locally (SQLite)
- Optional password protection (basic encryption)

---

## 🧰 Non-Functional Requirements

- **Performance**: Must run smoothly on mid-range hardware
- **Usability**: Simple and clean interface, beginner-friendly
- **Maintainability**: Modular architecture for easy feature extension
- **Localization**: Support for multiple languages

---

## 🔄 Future Improvements

- Invoice generation
- Dark mode UI
- Cloud sync (optional)
- Time tracking integration
- Community-defined presets per profession

---

## 📦 Deliverables

- Source code (open source)
- Executables for Windows, macOS, and Linux
- README and setup instructions
- User manual / help guide

---

## 🧪 Testing Plan

- Unit tests for core logic (tariff calculation, unit conversion)
- GUI testing manually (with test data)
- Export and import validation (PDF, CSV, JSON)

---

## 📧 Contact

For technical details or collaboration, contact: [email@example.com]  
Repository: https://github.com/your-username/loica
