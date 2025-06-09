# Win32 Graphics Application – Computer Graphics Project

A Win32 C++ application for drawing and manipulating geometric shapes using various computer graphics algorithms. Built with WinAPI and compiled using GCC.

---

### 👨‍💻 Submitted By

**Biswash Khanal**  
BCT 'A'  
ACE077BCT034

---

### 🛠️ Build Information

- **Compiler**: GCC 9.2 (32-bit)
- **Language Standard**: C++11
- **Linker Parameters**:-static-libgcc -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
- **Note**: If you’re unable to compile the program, run the executable (`.exe`) directly.

---

### 🎯 Objective

To create a Win32 application with:
- A toolbar and selectable options
- A canvas for shape drawing
- Support for multiple algorithms and operations from the Computer Graphics syllabus

---

### ✏️ Features

#### 🧩 **Lines**
- **DDA Algorithm**
- **Midpoint Algorithm**
- **Parameterized Technique**

#### ⭕ **Circles**
- **Direct Equation**
- **Polar Form**
- **Midpoint Algorithm**

#### 🥚 **Ellipses**
- **Direct Equation**
- **Polar Form**
- **Midpoint Algorithm**

#### 🎨 **Curves**
- Draw **Square** using Hermite Curves
- Draw **Rectangle** using Bezier Curves
- **5-point Cardinal Spline Curve**

#### 🪣 **Filling Algorithms**
- Recursive Flood Fill
- Non-Recursive Flood Fill  
*Note: May not work with very large areas due to integer overflow limits.*

#### ✂️ **Clipping**
- Circle-Line Clipping
- Rectangle-Line Clipping  
> ⚠️ **Important**: Use the *Clear* option under the **File** menu **before clipping**.

#### 🌈 **Color Support**
Add colors with just 4 lines of code. Currently available:
- Pink
- Green
- Purple
- Black

#### 🧰 **Additional Functionalities**
- Clear canvas
- Save and load drawings
- Change cursor within app (Arrow, Cross, Hand)

---

### 🖱️ How to Use

- **Line**: Select a line algorithm → Click two endpoints.
- **Circle**: Select circle algorithm → Click center → Click point on circumference.
- **Ellipse**: Select ellipse algorithm → Click center → Click point at `x-radius`, `y-radius` away.
- **Curves**:
- For Bezier/Hermite rectangle: Click two points to define width.
- For Cardinal spline: Click 5 points (start, 3 control points, end).
- **Clipping**: After using *Clear*, select clipping method → Shape appears → Click two endpoints for clipping line.
- **Filling**: Click inside the area to fill it.

---


