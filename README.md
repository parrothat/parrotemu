# 🦜 ParrotHat Emulator

**ParrotHat** is an open-source, multiplatform emulator for **8-bit** and **16-bit architectures** (more to come).  
It aims to provide a **real, fully functional emulator**, not just a simulation — designed to run directly on **Windows** and **Linux** systems.

---

## 🚀 Features
- Emulates 8-bit and 16-bit CPUs  
- Modular and extendable C++17 architecture  
- Real execution of instructions — no mock simulation  
- Runs on **Windows** and **Linux**  
- Open-source under **GPLv3**  

Planned:
- Support for 32-bit, 64-bit, and ARM architectures  
- BIOS emulation  
- Device interfaces (disk, VGA, CD-ROM, floppy)  

---

## 💾 Installation

### 🪟 Windows
1. Go to the **[Releases](https://github.com/ParrotHat/ParrotEMU/releases)** page  
2. Download **`parrothat-installer.exe`**  
3. The installer will:
   - Install ParrotHat on your system  
   - Add it to your system **PATH**

After installation, run from any terminal:
```bash
parrothat -h
```

### 🐧 Linux
Manual build is required:
```bash
git clone https://github.com/ParrotHatFoundation/ParrotHat.git
cd ParrotHat
mkdir build && cd build
cmake ..
make
sudo make install
```

Run ParrotHat:
```bash
parrothat -v
```

---

## 💻 Usage

Basic commands:
```bash
parrothat -h        # Show help
parrothat -v        # Show version info
parrothat -disk mydisk.vhd demo.bin
parrothat -cdrom game.iso
parrothat -floppy boot.img
parrothat -vga on
```

Example:
```bash
parrothat -disk system.vhd demo.bin
```

Upcoming parameters:
```
  -bios <file>     # Custom BIOS ROM
  -mem <size>      # Define memory size (e.g., -mem 128M)
  -no-vga          # Disable VGA device
  -debug           # Debug output
```

---

## 📜 License
Licensed under the **GNU General Public License v3.0 (GPLv3)**.  
See [LICENSE](./LICENSE) for full details.

---

## 🧠 About
ParrotHat is part of the **ParrotHat Virtualization Initiative** —  
an effort to create a modern, lightweight, open CPU emulator that runs real binary code and supports device-level emulation.

---

**Developed by Damián – ParrotHat Foundation**  
“**Emulate. Learn. Repeat.**”
