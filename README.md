# pdfTotable

This repository is dedicated to extracting tabular data from antimicrobial susceptibility testing (AST) PDF files using Python.

## File Descriptions

- **AB1_original.pdf**  
  Original AST PDF file obtained from Alborj.

- **AB1_CUT.pdf**  
  Trimmed version of the original PDF, keeping only the value-containing sections for easier processing.

- **AB1.txt**  
  Text file converted from `AB1_CUT.pdf` using Foxit PDF Editor.

- **R858.csv, D90.csv, N1092.csv**  
  Temporary datasets created as intermediate examples during the extraction process.

- **Final_AST_AB1.csv**  
  Final cleaned dataset containing the extracted tabular data — this is the target output derived from the original PDF.

- **pdftotable.ipynb**  
  Jupyter Notebook for extracting tabular data from PDF files. It contains the full workflow including PDF parsing, data cleaning, and export to CSV.

## Usage

Open and run `pdftotable.ipynb` in Jupyter Notebook or any compatible environment to process the PDF files and generate structured data.

---

