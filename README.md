# FreeCAD Parametric Hatch Generator

A powerful parametric hatch generator for FreeCAD with over 100 built-in patterns and extensive randomization controls. This macro creates a fully parametric `Part::FeaturePython` object, allowing you to edit hatch properties at any time.

[![Screenshot of the main dialog](https://imgur.com/a/Tk6X85y)]()

## Features
- **Large Pattern Library:** Over 100 built-in patterns, from simple lines to complex fractals and material textures.
- **Parametric:** Creates an editable feature object. Change any parameter later in the Property View.
- **Custom Patterns:** Use any FreeCAD object as a custom pattern shape.
- **Multiple Objects:** Supports multiple base shapes, pattern shapes, and subtraction objects for complex results.
- **Advanced Distribution:** Includes tiling, grid, radial, random, and adaptive distribution modes.
- **Variation Controls:** Randomize the placement, scale, rotation, spacing, and color of pattern tiles.
- **User-Friendly GUI:** A comprehensive dialog makes it easy to create and preview hatches.

## Installation
This macro is available in the FreeCAD **Addon Manager**.
1.  Go to **Tools → Addon Manager**.
2.  Select the **Macros** tab.
3.  Find **"Hatch Generator"** in the list and click **Install**.
4.  Restart FreeCAD.

The macro will now be available in your list of macros.

## How to Use
1.  Run the macro from the **Macro → Macros...** menu.
2.  Select a base object (e.g., a face of a solid, or a Sketch).
3.  Choose a pattern source:
    - **Built-in:** Select a pattern from the dropdown list.
    - **Custom:** Select a custom FreeCAD object to use as a pattern.
4.  Adjust the distribution, scaling, rotation, and other parameters in the dialog.
5.  Click **"Preview"** to see a temporary result, or **"Create Parametric Hatch"** to create the final object.

## Dependencies
- The macro works out-of-the-box for most patterns.
- An **optional** dependency on the `scipy` Python library is required to use the "Voronoi" and "VoronoiMesh" patterns.

## License
This project is licensed under the **GNU Lesser General Public License v2.1** - see the [LICENSE](LICENSE) file for details.
