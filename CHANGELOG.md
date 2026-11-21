# Changelog

## v1.0 (first release)

- Disassembler for arm64-v8a and armeabi-v7a (ARM + Thumb-2) ELF libraries
- Functions, names (C++ demangled), strings, relocations, PLT stubs, cross-references, ELF info
- IDA View, Hex View, split view, focus mode, synchronized cursor, back / forward history
- Pseudocode decompiler (VIP) for arm64, ARM and Thumb:
  types, floating point, conditional execution / IT blocks, switch statements from jump tables,
  stack-protector and no-return detection, GOT symbol names
- Modify instruction (VIP) with quick patches, ARM Converter (ARM to hex and back)
- Word / byte highlighting, fast scrollbars
- `.aida` projects: saved analysis, names and position
- Google sign-in, VIP, device access, in-app crash log, report issue / request feature, assistant
