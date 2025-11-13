# Atomic Mass Calculator for Colloquium

This repository contains the solution for my colloquium project: an interactive webpage that calculates the atomic mass of chemical compounds.

The project leverages Python with libraries such as `pandas`, `matplotlib`, `sympy`, and `mendeleev` to parse chemical formulas, fetch atomic weights, perform calculations, display data in tables, and visualize elemental contributions. The entire solution is presented as a Quarto webpage.

## Live Project Webpage

You can view the live, hosted version of this project here:
[https://bakerhenry.github.io/Colloquium-Final-atomic-mass-calculator/](https://bakerhenry.github.io/Colloquium-Final-atomic-mass-calculator/)

## Project Structure

*   `index.qmd`: The source Quarto markdown file containing all the project's explanations, Python code, tables, graphs, and SymPy equations.
*   `index.html`: The generated HTML webpage from `index.qmd`.
*   `index_files/`: Directory containing supporting assets for the HTML webpage (e.g., CSS, JavaScript, generated plot images).
*   `.gitignore`: Specifies files that Git should ignore (e.g., system files, large installer files like `quarto-linux-amd64.deb`).
*   `LICENSE`: The license under which this project is distributed.

## How to Run Locally (for developers)

To run this project on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/BakerHenry/Colloquium-Final-atomic-mass-calculator.git
    cd Colloquium-Final-atomic-mass-calculator
    ```
2.  **Install Python (if not already installed):** Follow instructions on [python.org](https://www.python.org/downloads/).
3.  **Install Quarto (if not already installed):** Follow instructions on [quarto.org](https://quarto.org/docs/getting-started/).
4.  **Install Python dependencies:**
    ```bash
    pip install pandas numpy sympy matplotlib mendeleev pubchempy
    ```
5.  **Render the Quarto document to HTML:**
    ```bash
    quarto render index.qmd
    ```
6.  **Open `index.html`** in your web browser.