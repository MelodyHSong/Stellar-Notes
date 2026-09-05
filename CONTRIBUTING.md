# ☆ Contributing to StellarNotes ☆

> "Transmitting ideas across the cosmos, one thought at a time."

Thank you for your interest in contributing to **StellarNotes**! Whether you are fixing bugs, improving documentation, or proposing new cosmic features, all transmissions are welcome.

---

## ☆ Development Setup

### Prerequisites
- Windows 10 or Windows 11
- Python 3.8 or higher
- Git

### Getting Started
1. **Fork and clone** the repository:
   ```bash
   git clone https://github.com/MelodyHSong/StellarNotes.git
   cd StellarNotes
   ```

2. **Install dependencies**:
   ```bash
   python -m pip install -r requirements.txt
   ```

3. **Launch in development mode**:
   ```bash
   python stellar_notes.py
   # or double-click run.bat
   ```

---

## ☆ Testing Context Menu Integration

StellarNotes registers a custom context menu verb in Windows Explorer under `HKCU`:

- **Install test registry keys (Python script mode)**:
  ```bash
  python setup_context_menu.py --install --mode python
  ```
- **Check installation status**:
  ```bash
  python setup_context_menu.py --status
  ```
- **Cleanly uninstall registry keys**:
  ```bash
  python setup_context_menu.py --uninstall
  ```

---

## ☆ Building the Standalone Executable

To compile the binary executable with PyInstaller:

```bash
python setup_context_menu.py --build
# or double-click build.bat
```

The output executable will be placed in `dist/stellar_notes.exe`.

---

## ☆ Submitting Changes

1. Create a descriptive feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Commit your changes with clear, descriptive commit messages.
3. Push to your fork and submit a Pull Request targeting `main`.
4. Describe the changes and include screenshots if modifying the UI.

---

*Keep your transmissions clear— MelodyHSong (Cassiopeia Studios)*
