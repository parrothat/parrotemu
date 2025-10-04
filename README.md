# 🦜 ParrotEMU

**ParrotEMU** is an open-source, multiplatform CPU emulator for **Windows** and **Linux**.  
It focuses on **8-bit and 16-bit CPUs**, with planned support for **32-bit, 64-bit, and ARM** architectures.

---

## 🚀 Features
- Clean, modular **C++17** codebase  
- Accurate instruction emulation  
- Runs on Windows and Linux  
- Open-source under **GPLv3**

---

## 💾 Download

### 🪟 Windows
Go to the **[Releases](https://github.com/ParrotHat/ParrotEMU/releases)** page and download  
➡️ **`parrotemu-installer-vXXX.exe`**

The installer will automatically:
- Install **ParrotEMU** on your system  
- Add it to your system **PATH**, so you can run it from any terminal  

Example:
```bash
parrotemu demo.bin
```

### 🐧 Linux
ParrotEMU must be built manually on Linux:

```bash
git clone https://github.com/ParrotHatFoundation/ParrotEMU.git
cd ParrotEMU
mkdir build && cd build
cmake ..
make
sudo make install
```

---

## 📜 License
Licensed under the **GNU General Public License v3.0 (GPLv3)**.  
See [LICENSE](./LICENSE) for details.

---

**Developed by ParrotHat Foundation**  
“**Emulate. Learn. Repeat.**”
