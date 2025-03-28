# Weave Pattern Generator
*A Python GUI app to generate and visualize textile weave patterns with black borders.*

## Features
* 🖥️ **User-friendly GUI** built with Tkinter.
* 🧵 **Supports 5 weave types**:
   * Plain
   * Basket
   * Twill
   * Satin
   * Herringbone
* 🎚️ **Adjustable parameters** (grid size, weave settings).
* ⬛ **Black borders** for clear cell separation.
* 🔄 **Real-time updates** when sliders are adjusted.

## Installation
1. Ensure you have Python 3.x installed.
2. Install required libraries:
```sh
pip install numpy matplotlib
```
3. Download or copy the script (`weave_pattern_generator.ipynb`).

## Usage
Run the app on jupyter notebook

## Controls
| Widget | Functionality |
|--------|--------------|
| **Weave Type** | Dropdown to select pattern (Plain, Basket, etc.) |
| **Rows/Columns** | Sliders to set grid dimensions (5–20) |
| **Twill (a/b)** | Adjust twill float pattern (if Twill is selected) |
| **Basket (n)** | Set block size for basket weave |
| **Satin (n)** | Adjust satin harness count (5 or 8) |

## How It Works
* The app generates a binary grid where:
   * *`1`* (Black) = Warp thread **over** weft.
   * *`0`* (White) = Warp thread **under** weft.
* Borders are drawn using `matplotlib` grid lines.



