# verilog_code_generator

# 🔧 Verilog Module Generator – 150+ Parametrized RTL Components

**Verilog Module Generator**, a plug-and-play utility for electronics engineers, FPGA developers, and digital design enthusiasts. This tool allows you to instantly generate over **150 reusable, synthesizable, and parameterized Verilog modules** by simply running a Python script.

---

## 📌 Overview

This tool is designed to accelerate RTL development by providing a **ready-to-use library of Verilog modules** — covering everything from arithmetic units and FIFOs to FSMs, counters, I/O interfaces, and more.

Each module is:
- Cleanly written and synthesizable
- Properly parameterized for flexibility
- Well-commented for clarity
- Designed for **plug-and-play** usage in real-world digital designs

---

## ✨ Features

- ✅ 150+ pre-defined Verilog modules
- ✅ Synthesizable & production-ready
- ✅ Parameterized for reuse and configurability
- ✅ Structured JSON-based architecture
- ✅ Just one Python script to generate any module or the entire library
- ✅ Helpful comments inside generated Verilog for quick understanding
- ✅ Works offline — no dependencies beyond Python itself

---

## 📁 Repository Structure

```

📦verilog-module-generator
┣ 📄 run.py                     # Python script to generate Verilog files
┣ 📄 verilog\_library\_dump.json # JSON file containing all module templates
┗ 📄 README.md                 # You're reading it :)

````

---

## 🚀 How to Use

1. **Download the following two files:**
   - `run.py` → the generator script
   - `verilog_library_dump.json` → the complete Verilog module library

2. Place both files in the **same folder**.

3. Run the script using Python:

```bash
python run.py
````

This will show a list of all available modules.

---

## 🔍 Usage Options

```bash
usage: run.py [-h] [--input INPUT] [--output OUTPUT] [--module MODULE]

Generate Verilog modules from an aggregated JSON library.

optional arguments:
  -h, --help           Show this help message and exit
  --input INPUT        Path to input JSON file (e.g. verilog_library_dump.json)
  --output OUTPUT      Name of output directory (default: verilog_library)
  --module MODULE      (Optional) Name of specific module to generate
```

### ✅ Example 1: Generate all modules

```bash
python run.py
```

This will generate the entire library inside a folder named `verilog_library`.

### ✅ Example 2: Generate only the `adder` module

```bash
python run.py --module adder
```

---

## 🧠 What's Inside the Library?

Over **150 common digital design modules**, including:

* 🔢 Arithmetic Units: `adder`, `multiplier_pipelined`, `divider`, `comparator`, etc.
* 📦 Storage: `fifo`, `ram`, `register_file`, `shift_registers`
* ⏱️ Counters: `binary_counter`, `bcd_counter`, `ring_counter`, `lfsr`
* 🧠 FSMs and Arbiters: `moore_fsm`, `round_robin_arbiter`, etc.
* 🔀 Multiplexers & Decoders: `mux_4_to_1`, `priority_encoder`, etc.
* ⏰ Clock & Reset: `clock_divider`, `reset_synchronizer`
* 📡 I/O Interfaces: `uart`, `spi`, `i2c`, `gpio`, `vga`
* 🧩 Synchronizers and CDC modules
* 🔌 Basic gates: `and`, `or`, `xor`, etc.
* 🧮 Error detection: `crc8`, `parity_generator`, `hamming_encoder`

All modules are documented with inline comments and built for immediate use.

---

## 📈 Roadmap

✅ Initial release with 150+ modules
🔜 Add support for SystemVerilog `interface` generation
🔜 Include testbenches and formal property sets
🔜 GUI tool for interactive module selection
🔜 User-submitted module templates

---

💬 Feedback & Contributions

If you have ideas, bug reports, or want to contribute your own Verilog templates:

* Create an issue or open a PR
* Fork the repo and submit improvements
* Or just drop a comment — all feedback is welcome!

💬 Constructive reviews help make this better for everyone. If you try it out, let me know what worked and what didn’t — I’d love to improve it based on real usage!



## ❤️ Built for the Hardware Community

This project is made by and for electronics engineers, RTL designers, and students who love clean, reusable digital design.
Let’s stop rewriting the same code — and start designing smarter.

