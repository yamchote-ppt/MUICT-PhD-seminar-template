# Project Name

This repository contains LaTeX files for composing abstracts, write-ups, and presentations for PhD seminar at MU-ICT.

## File Structure

- **abstract_main.tex**: This file is used for compiling the abstract document. Please edit the header information according to your requirements.
  
- **abstract.tex**: Use this file for writing the abstract part, to be included in both Abstract_main.tex and Writeup_main.tex.
  
- **writeup**: This folder contains all files related to the write-up. The compiled file is Writeup_main.tex. Feel free to edit other .tex files for \include or \input statements as needed.
  
- **figure**: Store all figure pictures in this folder. You can edit or remove the line "\graphicspath{ {figure/} }" in the .tex files if necessary.
  
- **presentation**: All files related to the Beamer presentation are stored in this folder.

## Usage

1. Clone this repository to your local machine.
   
2. Edit the relevant .tex files according to your project requirements.
   
3. Compile the LaTeX files using your preferred LaTeX editor or compiler. (PdfLaTeX is okay)