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
## Kort Language and Versions

### 1. **Kort (Basic Version)**
- **Target Audience**: Beginners and simple application developers.
- **Key Features**:
  - **Syntax**: Python-like with dynamic typing and indentation-based structure.
  - **Programming Paradigm**: Procedural programming with basic functions, conditionals (`elif`), and loops (`for`, `while`).
  - **Transpiler-based**: Automatically converts code to appropriate languages (like Python or C) based on the device.
  - **Output**: Uses `prt` instead of `print` (e.g., `prt["Hello World"]`).
  - **Mathematical Constants**: Supports constants like Pi (π), Euler’s number (𝑒), and others.
  - **Standard Library**: Includes basic functions for math, lists, time, and file handling.

### 2. **Kort+<version> (Intermediate Version)**
- **Target Audience**: Intermediate programmers seeking a balance between simplicity and advanced features.
- **Key Features**:
  - **Advanced Libraries**: More complex libraries than the basic version for handling advanced tasks.
  - **Intermediate Concepts**: Access to more advanced features, allowing for greater flexibility and control over programming.
  - **Additional Modules**: Expands Kort’s functionality with additional tools for various domains like networking, databases, and more.

### 3. **Kort_surface (Optimized for Surface Devices)**
- **Target Audience**: Developers working on applications for touch-based devices (e.g., tablets, smartphones).
- **Key Features**:
  - **Touchscreen UI**: Focused on creating applications that interact with users through touch-based interfaces.
  - **Surface-Specific Libraries**: Provides tools for responsive UI design and touch gestures.
  - **UI Optimization**: Optimized for creating applications that work seamlessly on touchscreens and small displays.

### 4. **Kort_edge (Optimized for Edge Devices)**
- **Target Audience**: Developers working on embedded or edge devices with limited resources.
- **Key Features**:
  - **Performance Optimizations**: Focuses on efficient code execution for devices with limited processing power and memory.
  - **Edge-Specific Libraries**: Tools for integrating with sensors, hardware components, and real-time systems.
  - **Resource-Constrained Development**: Prioritizes minimal overhead and high performance for edge computing environments.

### 5. **Kort_X (Most Advanced Version)**
- **Target Audience**: Advanced developers working on complex systems, including OS development, IoT, and AI.
- **Key Features**:
  - **AI-Powered Features**: AI-enhanced suggestions in the IDE for code completion, intelligent refactoring, and auto-fixes.
  - **Full-Spectrum Development**: Supports all types of programming, including OS development, AI, hardware integration, and IoT.
  - **Complex Code Support**: Enables the creation of large, scalable projects with advanced programming paradigms.
  - **Comprehensive Libraries**: Includes extensive libraries and modules for specialized tasks across different domains.
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
