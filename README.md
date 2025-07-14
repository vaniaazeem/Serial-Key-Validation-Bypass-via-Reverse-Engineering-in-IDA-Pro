# 🔍 Reverse Engineering Lab with IDA Pro

This repository documents a practical reverse engineering exercise using **IDA Pro**, aimed at analyzing a binary executable that validates serial keys. The goal was to trace program logic, identify faulty conditions, and patch the binary to accept a user-defined serial key — all in a safe and educational setting.

---

## 🧠 Objective

To reverse engineer a given binary using IDA Pro by:
- Identifying incorrect serial key validation logic.
- Analyzing control flow using the graph view.
- Locating and modifying conditional jumps responsible for the "Wrong Key" message.
- Successfully patching the binary to bypass the faulty check and trigger the "Well Done" message.

---

## 🧰 Tools Used

- [IDA Pro Free](https://hex-rays.com/ida-free/) (Interactive Disassembler)
- Hex View & Graph View
- String references and jump instructions analysis

---

## 📝 Lab Steps Summary

1. **Opened the binary in IDA Pro** and analyzed its functions.
2. **Searched for the "Wrong" string**, which indicated where the validation logic failed.
3. **Explored control flow using the Graph View**, which revealed conditional branches.
4. **Identified the faulty conditional jump** causing incorrect output.
5. **Patched the jump instruction** to alter the flow toward the success message.
6. **Created a backup of the modified file** and tested the serial key successfully.

---

## 🔐 Ethical Disclaimer

> ⚠️ **Disclaimer:**  
> This repository is strictly for **educational purposes only**.  
> No malicious files, cracked binaries, or proprietary executables are shared.  
> The exercise was conducted in a controlled lab environment to understand reverse engineering fundamentals, not to promote software piracy or unauthorized tampering.

---

## 📁 Repository Contents

- `README.md` – This file
- `lab_report.pdf` *(optional)* – Detailed documentation and screenshots (if you choose to add one)
- Screenshots folder *(optional)* – Graph view, strings, and patching demonstration (safe to include)

---

## 📚 What You’ll Learn

- Basics of binary disassembly using IDA Pro
- String and function reference tracing
- Control flow analysis using graph view
- Binary patching techniques
- Understanding of serial key validation logic

---

## 💡 Note

To follow this lab or try similar exercises:
- Use **free or test binaries**.
- Never work on real software without legal permission.
- Always maintain ethical standards in cybersecurity practices.

