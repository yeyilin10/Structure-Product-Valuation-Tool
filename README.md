# Monte Carlo Pricing Tool for Auto-callable Structured Products

This repository contains Python and Excel-based tools for pricing auto-callable structured products using Monte Carlo simulation. The tools allow the user to present indicative prices in a user-friendly manner.

## Project Overview

Auto-callable structured products are a package of financial instruments that have gained popularity over the past decade. Despite their complexity, these products are widely used by private investors. This project implements a pricing tool for such products, using Python for the heavy lifting and Excel for input/output, providing a familiar and easy-to-use interface for users.

## Keywords

Autocalls, Structured Products, Geometric Brownian motion

## Tools

Two versions of the structured product valuation tools have been implemented:

1. **Combined Version**: This Python script combines different types of structured products such as single/basket equity linked deposit/autocall. Users can enter all product details into the `Input.xlsx` file and run the script. The output, which includes potential loss and gain as well as some informative graphs, will be automatically displayed in the `Output.xlsx` file.

2. **Separated Version**: In this version, different types of structured products are evaluated by different scripts. Users need to enter product details into different sheets in the `Input.xlsx` file and run the corresponding Python scripts. The results will be automatically displayed in the `Output.xlsx` file, with each sheet in the Excel file corresponding to one contract.

## Usage

To use these tools, clone this repository and navigate to the directory containing the scripts. Ensure that you have Python and the necessary packages installed. Enter your product details into the `Input.xlsx` file, then run the appropriate Python script. The results will be displayed in the `Output.xlsx` file.

## Contribution

Contributions are always welcome. Please feel free to fork the repository. You can also open an issue if you find any bugs or have any suggestions for improvements.

## Contact

For any queries or suggestions, feel free to open an issue or reach out via GitHub.
