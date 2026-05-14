# font2openscad

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Convert text to OpenSCAD `polygon()` definitions (points and paths) from any TTF/OTF font.

## Demo

Try it live: **[https://code4fukui.github.io/font2openscad/](https://code4fukui.github.io/font2openscad/)**

## How It Works

The tool provides a simple, two-panel interface in your browser:
-   **Input Panel:** Choose a font, enter your text, and fine-tune parameters like size, spacing, and precision.
-   **Output Panel:** A preview canvas shows the resulting 2D shape, and a textarea provides the generated OpenSCAD code, ready to be copied.

## Features

-   **Font Support:** Use any local TTF or OTF font file.
-   **Pre-loaded Fonts:** Includes built-in options from the Noto Sans JP and IchigoJam font families.
-   **Customizable Output:** Adjust parameters to control the final shape:
    -   Font Size (in OpenSCAD units)
    -   Letter Spacing
    -   Baseline (Y-offset)
    -   Curve Precision (flatness)
-   **Path Union:** Automatically combines overlapping character paths into a single, clean polygon