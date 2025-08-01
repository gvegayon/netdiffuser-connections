# A netdiffuseR Tutorial: Estimating Network Influences on Behavior within the Diffusion Paradigm

This repository contains the materials to reproduce the paper "A netdiffuseR Tutorial: Estimating Network Influences on Behavior within the Diffusion Paradigm".

## Prerequisites

To build the paper, you need the following software installed on your system:

- **R** (version 4.4.0 or higher recommended)
- **netdiffuseR** R package (version 1.23.0 or higher)
- **Quarto** (for document rendering)

This repository also contains a [Devcontainer environment](.devcontainer) reproducing the exact system configuration during the development of the manuscript.

## Building the Paper

Once you have all prerequisites installed:

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd netdiffuser-connections
   ```

2. Render the paper using Quarto:
   ```bash
   quarto render paper.qmd
   ```

The rendered paper will be generated as `paper.pdf` (or other formats as specified in the document header).

## Repository Structure

- `paper.qmd`: Main Quarto document containing the tutorial
- `README.md`: This file with setup instructions
- Additional data files and scripts (if any) used in the tutorial

## About the Paper

This tutorial provides a comprehensive introduction to using the netdiffuseR package for estimating network influences on behavior within the diffusion paradigm. The paper covers theoretical foundations, practical applications, and step-by-step examples using R.

## Troubleshooting

If you encounter issues:

1. Ensure all dependencies are properly installed
2. Check that you're using compatible versions of R and the required packages
3. Make sure Quarto is accessible from your command line/terminal

For package-specific issues, consult the [netdiffuseR documentation](https://github.com/USCCANA/netdiffuseR).
