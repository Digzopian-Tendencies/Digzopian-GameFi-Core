# 🧘 Sovereign Lab Setup: Lenovo Yoga 9 Edition

This document outlines the optimal configuration for the **Digzopian Sovereign Lab** running on the Lenovo Yoga 9.

## 🖥️ Hardware Profile
- **Device**: Lenovo Yoga 9 (Convertible)
- **Focus**: Mobile Sovereignty, Touch Interface, Power Efficiency.

## 🛠️ Environment Configuration

### 1. Power Management
To maximize battery life during off-grid coding sessions:
- Use the **Lenovo Vantage** "Quiet" or "Battery Saver" mode.
- The Core is designed to be lightweight (`npm run dev`) to minimize CPU cycles.

### 2. Development Interface (Touch Optimized)
When using the device in **Tablet Mode**:
- **VS Code Settings**:
  - Increase `Editor: Font Size` to 16px for better readability.
  - Enable `Workbench > List: Open Mode` to `singleClick`.
  - Use **Zen Mode** (`Ctrl+K Z`) to maximize screen real estate.

### 3. Local-First AI Integration
For autonomous operation without cloud dependencies:
- **Recommended**: Run a local LLM server (e.g., Ollama or LM Studio) compatible with the Yoga 9's GPU/NPU.
- **Integration**: This repo will support local API endpoints in future updates.

## 🌐 Network Independence
- All dependencies are defined in `package.json`.
- Run `npm install` while connected, then you are free to roam offline.
- Documentation in `docs/` is self-contained.

---
*Architected for the Digzopian Nomad.*
