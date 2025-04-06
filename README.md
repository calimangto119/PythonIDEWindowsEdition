# Portable Python IDE

## Description

**Portable Python IDE** is a lightweight and modern desktop Python development environment built with PyQt5. Designed for **Windows users with standard Python installations**, this app provides everything you need to write, run, and manage Python scripts in a user-friendly interface.

Whether you're a developer, student, or tinkerer, this IDE simplifies Python development — no need for heavyweight environments or complex setup.

## Features

- 📝 **Modern Code Editor**  
  - Syntax highlighting
  - Line numbering
  - Search & Replace with advanced options
  - Auto-indent and tab-width control
  - Theme support (Modern & Dark)

- 🧰 **Python Package Management**  
  - Install/uninstall Python packages
  - Detect and auto-install missing imports
  - Export/import `requirements.txt`
  - Upgrade outdated packages
  - pip updater included

- 🚀 **Run Python Scripts**  
  Execute `.pyw` scripts directly inside the app using your local Python installation.

- 🧱 **Create Standalone Applications**  
  Use PyInstaller integration to package your script into a standalone `.exe` — no Python required on the target machine.

- 💾 **Auto Save**  
  Auto-saves your work every 5 minutes, either to your current script file or a time-stamped backup folder.

## How It Works

1. On first launch, the app detects your existing Python installation or prompts you to select `python.exe`.
2. Scripts can be written, saved, and executed using your system's Python interpreter.
3. Missing packages? The IDE will prompt to install them.
4. Convert your script to a standalone `.exe` with just a few clicks.

## Requirements

- Windows OS
- Python 3.6+ (must be installed and accessible)
- Admin rights may be needed for pip-based operations

> PyQt5 is automatically installed on first launch if missing.

## License

Licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.  
See [LICENSE](./LICENSE.txt) for full details.

## Disclaimer

This software is provided “as-is” without warranties. Use at your own risk.
