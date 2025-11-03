# 🔢 Binary ↔ Text Converter

A lightweight, interactive web tool for **converting between text and binary (8-bit)**.  
Built using pure **HTML, CSS, and JavaScript** — no frameworks, no dependencies.

![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/built%20with-HTML5-orange)
![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow)
![Status](https://img.shields.io/badge/status-active-success)

---

## 🌐 Live Demo

 
👉 **https://sendmetirries.github.io/binary-text-converter

---

## ✨ Features

✅ **Text → Binary Conversion** – Converts each character into its 8-bit binary form.  
✅ **Binary → Text Conversion** – Translates valid binary input back to text.  
✅ **Dark / Light Mode Toggle** – Saves your theme preference using `localStorage`.  
✅ **Copy & Download** – Copy results to clipboard or download as `.txt` files.  
✅ **Animated LEDs & Sound** – Optional feedback for conversions.  
✅ **Offline Functionality** – Runs fully in your browser; no internet needed.

---

## 🧠 How It Works

The tool uses built-in JavaScript methods for conversion logic:

- **Text → Binary:**  
  Each character is converted using `charCodeAt()` → `toString(2)` (base 2), padded to 8 bits.

- **Binary → Text:**  
  Binary segments (e.g., `01001000`) are parsed with `parseInt(byte, 2)` → converted via `fromCharCode()`.

---

## 🪄 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/sendmetirries/binary-text-converter.git
   cd binary-text-converter
2. Open src/index.html (or index.html if you moved it to the root folder) in your web browser.

Type text or binary into the input area and click:

🧾 Text → Binary

💬 Binary → Text

📋 Copy Output

💾 Download Result

Toggle Dark Mode 🌙 from the top-right corner.

🧩 File Structure

  binary-text-converter/
├── src/
│   └── index.html          # Main converter file
├── .github/
│   └── workflows/pages.yml # GitHub Pages auto-deploy workflow
├── .gitignore
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── SECURITY.md

