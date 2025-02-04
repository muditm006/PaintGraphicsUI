# 🎨 OCaml Paint Interface

An **OCaml-based graphical paint application** that allows users to draw various objects using an intuitive interface with 14 interactive widgets. This project leverages the **OCaml Graphics library**, **Queue data structures**, and custom modules for widgets, GUI management, and event handling to create a robust and scalable paint program.

---

## ✨ Features

- 🖌️ **Interactive Drawing Tools**  
  Users can draw shapes, lines, and other objects using a set of 14 interactive widgets.

- 🎚️ **Customizable Line Thickness**  
  Includes a custom slider for adjusting line thickness, implemented using controllers and mouse click/drag events.

- 🏗️ **Modular Design**  
  Built with modular components such as `Widget`, `GUI`, and `Event Loop` modules to ensure scalability and maintainability.

---

## 🔧 Technical Details

- The **Graphics library** was used to render the interface and handle drawing operations in a separate window.
- A **Queue data structure** was utilized to manage user inputs and events efficiently.
- The event loop processes mouse clicks, drags, and other interactions to dynamically update the GUI.
- The application architecture consists of three main layers:
  - **Application Layer (`paint.ml`)**: Implements the paint logic.
  - **GUI Toolkit Layer (`widget.ml`, `gctx.ml`)**: Manages widgets and graphical contexts.
  - **Native Graphics Layer (OCaml Graphics Module)**: Handles low-level drawing operations.

---

## 🗂️ File Descriptions

> *Note: Not all files required to run the GUI are included in this repository. Only the files where significant contributions were made are provided.*

- **`gctx.ml`**  
  Contains functions for managing graphical contexts, including rendering shapes and handling coordinate transformations.

- **`gctx.mli`**  
  The interface file for `gctx.ml`, defining the module's exposed functionalities.

- **`paint.ml`**  
  Implements the main logic of the paint application, including event handling, widget integration, and drawing operations.

- **`widget.ml`**  
  Defines various interactive widgets (e.g., buttons, sliders) used in the GUI for user interaction.

- **`widget.mli`**  
  The interface file for `widget.ml`, specifying the types and operations available for widgets.

---

## 🛠️ How to Run

1. Clone this repository to your local machine:
git clone https://github.com/muditm006/OCaml-Paint.git
cd OCaml-Paint
2. Set up your OCaml environment:
- Install OCaml if it's not already installed on your system.
- Ensure that the `graphics.cma` library is available in your OCaml installation.
3. View/build off of the provided files as needed to extend or customize functionality.
---

## 📝 Notes

- This project demonstrates how to build a fully functional GUI application in OCaml using a layered architecture.
- The `Graphics` module provides portable drawing primitives that run in a separate window.
- The modular design makes it easy to extend functionality by adding new widgets or features.
- Ensure that you have the necessary permissions to run graphical applications on your system (e.g., X11 support on Unix-based systems).

