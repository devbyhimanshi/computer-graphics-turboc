# Computer Graphics algorithms using Turbo C++

This project is a **menu-driven Computer Graphics application** implemented in **C++ using Turbo C++ graphics (BGI)**.  
It demonstrates fundamental **line, circle, ellipse, rectangle, and triangle drawing algorithms**, commonly taught in Computer Graphics courses.

---

## 📌 Features
- Menu-driven interface
- Step-by-step pixel plotting with delay
- Classic Computer Graphics algorithms
- Suitable for **academic labs, viva, and exams**

---

## 🧮 Algorithms Implemented

### Line Drawing
- DDA (Digital Differential Analyzer) Algorithm
- Bresenham’s Line Drawing Algorithm

### Circle Drawing
- Midpoint Circle Algorithm
- Bresenham’s Circle Algorithm

### Ellipse Drawing
- Midpoint Ellipse Drawing Algorithm

### Other Shapes
- Rectangle Drawing
- Triangle Drawing

---

## 🛠️ Technologies Used
- **Language:** C++
- **Compiler:** Turbo C++
- **Graphics Library:** BGI (graphics.h)
- **Platform:** DOSBox / Turbo C++ Environment

---

## ▶️ How to Run the Program

1. Install **Turbo C++** (preferably inside DOSBox)
2. Copy `main.cpp` into:
```

C:\TURBOC3\BIN

```
3. Open Turbo C++
4. Load the file:
```

File → Open → main.cpp

````
5. Ensure BGI path is correct in code:
```cpp
initgraph(&gd, &gm, "C:\\TURBOC3\\BGI");
````

6. Compile and Run:

   ```
   Alt + F9 → Ctrl + F9
   ```

## 📋 Menu Options

```
1. Line
   - DDA Algorithm
   - Bresenham Algorithm
2. Circle
   - Bresenham Circle
   - Midpoint Circle
3. Ellipse
4. Rectangle
5. Triangle
6. Exit
```

---

## 🎯 Educational Use

This project is ideal for:

* Computer Graphics Lab Practicals
* University Assignments
* Exam & Viva Preparation
* Understanding raster graphics algorithms

---

## 📂 Project Structure

```
Computer-Graphics-TurboC/
│
├── main.cpp
├── README.md

## 👤 Author

**Himanshi Jain**


## ⭐ Acknowledgment

This project is developed for **learning and academic purposes** following standard Computer Graphics syllabus.
