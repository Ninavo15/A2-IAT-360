# L-System Generative Artwork Generator

This project is a rule-based generative art system using **L-Systems**.  
It generates complex fractal and geometric patterns by repeatedly rewriting an initial axiom
using production rules, then visualizing the result with **turtle graphics (ColabTurtle)**.

This creates multiple different artwork outcomes by: 
- L-System grammars (Square Weave, Hilbert Curve, Dragon Curve)
- Iterations
- Angles
- Color
- Line thickness

## Requirements

This project runs in **Google Colab** or any Jupyter Notebook environment.

## Required Library

- ColabTurtle

Install it with:

```bash
pip install ColabTurtle

How to Run the Project
Step 1: Open the Notebook in Google Colab

Upload or open the provided .ipynb file in Colab.

Step 2: Install Dependencies

Run the first cell:

!pip -q install ColabTurtle

Step 3: Run All Code Cells

The notebook contains:

L-System string generator

Turtle drawing renderer

Color + thickness styling functions

Preset grammars

Output runner

Step 4: Generate the Sample Outputs

At the bottom of the notebook, run:

run_5_outcomes()


This will generate and draw 5 different L-System artworks, each with different:

pattern type

iterations

angles

palettes

thickness styles

background colors

Output Examples

The project generates:

Square Weave (pastel gradient)

Square Weave (warm depth tapering)

Hilbert Curve (maze-like space filling)

Hilbert Curve (angle variation + depth styling)

Dragon Curve (high-detail candy fractal)

Customization

You can create new patterns by editing the outcomes list:

dict(
    preset="Dragon Curve",
    iterations=9,
    angle=100,
    palette_name="warm",
    thickness_mode="depth"
)


Key parameters:

iterations: controls complexity/detail

angle: changes geometry dramatically

palette_name: "fairy", "warm", "viridis_like"

color_mode: "progress" or "depth"

thickness_mode: "constant" or "depth"

bg: background color

Author

Created by: [Your Name]
Course: Generative Arts / Rule-Based Systems
Simon Fraser University


---

# ✅ What You Need to Do

Just replace:

```markdown
Created by: *[Your Name]*
