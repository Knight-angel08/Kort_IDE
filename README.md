# 🎯 KORT IDE 🚀  
#### **A Powerful & Smart IDE for the Kort Programming Language**  

![Kort Version](https://img.shields.io/badge/Kort-Language-blue?style=for-the-badge)  
![IDE Version](https://img.shields.io/badge/IDE-v1.0-green?style=for-the-badge)  
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)  

---

## **✨ What is Kort?**  
Kort is a **beginner-friendly programming language** that follows a **procedural approach** with support for **mathematical computations, physics simulations, and automation**. It is **transpiler-based**, meaning it converts into Python, C, or other languages based on system compatibility.  

The **Kort IDE** is a **modern, intelligent development environment** that provides a **rich feature set** with built-in AI enhancements and seamless **transpilation support**.

---

## **🚀 Features of Kort IDE**  

### 🔹 **General Features**
✔ **VS Code Compatibility**  
✔ **Auto-detection of Installed Languages**  
✔ **Built-in Compiler & Transpiler**  
✔ **Smart Auto-Suggestions for Syntax Errors**  
✔ **Google Drive Cloud Support** (*PC only*)  
✔ **GitHub & GitLab Integration**  

### 🎨 **UI & Design**
✔ **Dark & Light Theme**  
✔ **Syntax Highlighting**  
✔ **Bracket Auto-Completion**  
✔ **Floating Command Palette**  

### 📂 **File Handling**
✔ **Supported File Types:** `.kort`, `.txt`, `.csv`, `.py`, `.c`, `.html`, `.env`, `.pdf`  
✔ **New File Syntax:** `file.new["path", "filename", "<extension>"]`  
✔ **Read File:** `file.read[<path>, <filename.extension>]`  
✔ **Write File:** `file.write[<path>, <filename.extension>]`  
✔ **Delete File:** `file.delete[<path>, <filename.extension>]`  

### 🔢 **Mathematics & Physics Libraries**
✔ **Maths Library:** (`from maths import limits, integration`)  
✔ **Physics Library:** (`from phys import mechanics, optics`)  
✔ **Supports Real, Rational, Irrational, Integer, Complex Numbers**  
✔ **Auto-conversion of Scientific Notation** (e.g., `5 × 10^(-14)`)  

### ⚙ **Transpilation & Execution**
✔ **Auto-Detects Available Languages**  
✔ **Optimized Code Conversion**  
✔ **Error Handling with Detailed Logs**  
✔ **Saves Code in the Transpiled Language Format**  

### 🛠 **Debugging & Logs**
✔ **Built-in Syntax Checker & Debugger**  
✔ **Error Logs Saved as `.txt` Files**  
✔ **Reminder System for Logs (Max 7 Days Delay)**  

---

## **📌 Getting Started**
### **🔽 Installation**  
1️⃣ **Download the Latest Release** from the [GitHub Releases](#) page.  
2️⃣ **Extract & Install** the package.  
3️⃣ **Run the IDE & Start Coding!**  

---
## **📜 Example Code in Kort**
```kort
from maths import limits

def f[x] = x^2 + 3x - 5
prt["Limit of f[x] as x → 2: ", limits.solve[f, x→2]]

# output: Limit of f[x] as x → 2: 5
