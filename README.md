<div align="center">

# Android IDA

**ARM disassembler & decompiler for Android, right on your phone.**

Open any `.so` library, browse its functions, read ARM code, and turn it into readable C-like pseudocode.

[![Release](https://img.shields.io/github/v/release/aadilmodsofficial/Android-IDA?label=latest&color=3B82F6)](https://github.com/aadilmodsofficial/Android-IDA/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/aadilmodsofficial/Android-IDA/total?color=17B5D6)](https://github.com/aadilmodsofficial/Android-IDA/releases)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![ABI](https://img.shields.io/badge/ABI-arm64--v8a%20%7C%20armeabi--v7a-555)

[**⬇ Download the latest APK**](https://github.com/aadilmodsofficial/Android-IDA/releases/latest)

</div>

---

## Features

### Analysis
- Opens ELF shared libraries (`.so`) and executables: **arm64-v8a**, **armeabi-v7a (ARM & Thumb-2)**
- Automatic function discovery, symbols (with C++ demangling), strings, relocations, PLT stubs, xrefs
- ELF info: header, sections, segments, dynamic table
- Projects (`.aida`): the analysis is saved, so reopening is instant

### Views
- **IDA View**: disassembly with names, branch targets and data references
- **Pseudocode** *(VIP)*: C-like decompiler for arm64, ARM and Thumb
  - typed variables, parameters and return values (`bool`, `int`, `float`, `double`, `char *`, `std::string`, pointers, etc.)
  - `if` / `while` / `do-while` / `switch` (jump tables), floating point (VFP / AArch64 FP)
- **Hex View**: file bytes with offsets and ASCII
- **Strings**, **Names**, **Relocations**, **ELF Info**
- Split view, focus mode, synchronized cursor across all views
- Tap a word to highlight it everywhere (registers, variables, names); fast scrollbar on every list

### Patching
- **Modify instruction** *(VIP)*: return a fixed `bool` / `int` / `int64` / `float` / `double`, NOP, always / never jump, invert a condition, skip a call, or any custom ARM code
- **ARM Converter**: ARM to hex and back for arm64, ARM and Thumb, with the instruction address for correct branch targets
- Copy bytes as hex or as a C++ array, save function offsets

---

## Download & install

1. Go to **[Releases](https://github.com/aadilmodsofficial/Android-IDA/releases/latest)** and download `Android-IDA-vX.Y.apk`.
2. Open it on your phone and allow *Install unknown apps* for your browser / file manager if Android asks.
3. Sign in with Google.

**Requirements:** Android 7.0 (API 24) or newer, an ARM phone (arm64 or 32-bit ARM), internet connection.

---

## Free vs VIP

| | Free | VIP |
|---|:---:|:---:|
| IDA View, Hex View, Strings, Names, ELF Info, Relocations | ✅ | ✅ |
| ARM Converter | ✅ | ✅ |
| Pseudocode (decompiler) | ❌ | ✅ |
| Modify instruction | ❌ | ✅ |
| Device access | free activation | ✅ always |
| Ads | yes | **no ads** |

VIP is linked to one device. You can get it from the **VIP** tab in the app.

---

## Screenshots

<!-- Add images to the screenshots/ folder and they will show here -->
| Projects | IDA View | Pseudocode |
|---|---|---|
| ![Projects](screenshots/projects.png) | ![IDA View](screenshots/ida-view.png) | ![Pseudocode](screenshots/pseudocode.png) |

---

## Support

- 🐞 **Bugs / ideas:** use *Report an issue* / *Request a feature* inside the app, or open an [issue](https://github.com/aadilmodsofficial/Android-IDA/issues)
- 💬 **Discord:** [discord.gg/cnw8tYRRbN](https://discord.gg/cnw8tYRRbN)
- ✈️ **Telegram:** [t.me/aadilmodsofficial](https://t.me/aadilmodsofficial)
- 📸 **Instagram:** [@aadilmods](https://instagram.com/aadilmods)

---

## Notice

Android IDA is **closed source**; this repository only hosts releases and documentation.
It is an independent project and is **not affiliated with Hex-Rays or IDA Pro**.
Use it only on software you own or are allowed to analyse.

See [LICENSE](LICENSE) for the terms of use.
