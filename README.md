# paper-code
This repository contains the code for the paper titled 'Development and temporal validation of a clinical prediction model for necrotizing pneumonia in children with Mycoplasma pneumoniae pneumonia' published in Children.

# paper-code

Code to reproduce the analyses for the paper:  
**"Development and temporal validation of a clinical prediction model for necrotizing pneumonia in children with Mycoplasma pneumoniae pneumonia"**.

## Quick start
1. Open `reproduce.ipynb`
2. Set the dataset path in the notebook (e.g., `excel_path = "data/dataset.xlsx"`)
3. Run all cells to reproduce the results.

## Data format (input)
- **File type:** Excel `.xlsx` (single sheet)
- **Label column:** `group` (binary: 0/1)
- **All predictors are numeric** (binary indicators use 0/1)

### Clinical variables / Laboratory tests
Binary indicators are encoded as **0 = absent / 1 = present**.

## Notes
- The repository does **not** include any patient-level data.
- Please ensure the input file contains no identifiable information.



