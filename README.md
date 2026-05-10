# Free-Paint

Free Paint is a lightweight yet powerful creative tool built with Python and enhanced for the Linux ecosystem. Unlike standard script-based applications, Free Paint is compiled into a standalone binary using Nuitka, ensuring maximum execution speed and zero dependencies on the user's local Python environment.
<img width="1202" height="736" alt="Screenshot_2026-05-11_01-12-21" src="https://github.com/user-attachments/assets/a7332fa6-caa3-44c4-9d32-c0dacb77d0ac" />


Key Features
True Brush Engine: Smooth, circular brush strokes for a natural drawing experience.

Vector Shapes: Draw precise lines, circles, squares, triangles, and diamonds.

Smart Star Tool: Custom-coded star algorithm that scales perfectly with brush size.

Image Manipulation: Import .png or .jpg files to edit, annotate, or draw over them.

Magic Mode ✨: Dynamic, randomized color effects for creative experimentation.

Multilingual Interface: Automatic system language detection with manual toggles for English and Romanian.

Pro Tools: Includes a flood-fill (bucket) tool, canvas clearing, undo history, and a background color cycler.

🛠 Technical Implementation
Core: Built using Tkinter and the Pillow (PIL) library for advanced image processing.

Compilation: Leverages Nuitka to produce a standalone .bin executable, eliminating "cold start" lag common in Python scripts.

Distribution: Packaged as a native Debian (.deb) file, featuring a custom desktop entry and icon integration for seamless installation on antiX, Debian, Ubuntu, and Mint.

📥 Installation
Simply download the latest .deb release and install it via your preferred package manager:

sudo apt install ./free-paint_1.1_amd64.deb
Author: Eduard Milea

Contact: aplicatiipython@outlook.com

## License
This project is proprietary. It is free for personal use, but commercial redistribution is prohibited without written permission. See the [LICENSE](LICENSE) file for details.
