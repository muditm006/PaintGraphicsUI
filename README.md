# OCaml Paint Interface

An OCaml-based graphical paint application that allows users to draw various objects using an intuitive interface with 14 interactive widgets. This project was implemented using the **OCaml Graphics library**, **Queue data structures**, and custom modules for widgets, GUI management, and event handling.

## Features

- **Interactive Drawing Tools**  
  Users can draw shapes, lines, and other objects using a set of 14 interactive widgets.  

- **Customizable Line Thickness**  
  Includes a custom slider for adjusting line thickness, implemented using controllers and mouse click/drag events.

- **Modular Design**  
  Built with modular components such as `Widget`, `GUI`, and `Event Loop` modules to ensure scalability and maintainability.

## Technical Details

- The **Graphics library** was used to render the interface and handle drawing operations.
- A **Queue data structure** was utilized to manage user inputs and events efficiently.
- The event loop processes mouse clicks, drags, and other interactions to update the GUI dynamically.

## File Descriptions

> *Note: Not all files required to run the GUI are included in this repository. Only the files where significant contributions were made are provided.*

- **gctx.ml**  
  Contains functions for managing graphical contexts, including rendering shapes and handling coordinate transformations.

- **gctx.mli**  
  The interface file for `gctx.ml`, defining the module's exposed functionalities.

- **paint.ml**  
  Implements the main logic of the paint application, including event handling, widget integration, and drawing operations.

- **widget.ml**  
  Defines various interactive widgets (e.g., buttons, sliders) used in the GUI for user interaction.

- **widget.mli**  
  The interface file for `widget.ml`, specifying the types and operations available for widgets.

## How to Run

1. Clone this repository to your local machine.
2. View/build off of the provided files as needed to extend or customize functionality.

