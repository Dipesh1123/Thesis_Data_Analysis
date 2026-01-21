# Thesis_Data_Analysis

A small repository for the thesis project focused on digital health data analysis. This repository contains the working Jupyter Notebook used for exploration and analysis, plus the final research report in PDF form.

## Repository contents

- `Digital_Health.ipynb` — Primary Jupyter Notebook containing the data exploration, analysis, visualizations, and any modeling performed for the thesis. You can view this directly on GitHub or run it locally.
  - https://github.com/Dipesh1123/Thesis_Data_Analysis/blob/main/Digital_Health.ipynb
- `FINAL RESEARCH REPORT.pdf` — The final written thesis / research report summarizing methods, results, and conclusions.
  - https://github.com/Dipesh1123/Thesis_Data_Analysis/blob/main/FINAL%20RESEARCH%20REPORT.pdf

## About

This repository collects the core analysis and final report for a thesis on digital health. The Jupyter notebook contains code cells, figures, and narrative that support the analyses reported in the PDF. Use the notebook to inspect data processing steps, reproduce figures, and re-run experiments or modeling.

## How to view the content

- View on GitHub
  - GitHub renders Jupyter notebooks and PDFs directly in the browser — click the files above to inspect them.
- View the notebook via NBViewer (useful for a clean static render)
  - Example: https://nbviewer.org/ and paste the notebook URL.
- Run locally
  1. Clone the repository:
     ```bash
     git clone https://github.com/Dipesh1123/Thesis_Data_Analysis.git
     cd Thesis_Data_Analysis
     ```
  2. Start Jupyter (recommended to use a virtual environment or conda environment):
     ```bash
     # using pip / venv
     python -m venv .venv
     source .venv/bin/activate   # macOS / Linux
     .venv\Scripts\activate      # Windows

     pip install --upgrade pip
     pip install jupyter
     jupyter notebook
     ```
  3. Open `Digital_Health.ipynb` from the Jupyter interface.

## Recommended environment & dependencies

The notebook contains the specific imports and any dataset loading steps. Typical packages used in data analysis notebooks include:
- Python 3.8+
- pandas
- numpy
- matplotlib and/or seaborn
- scikit-learn (if modeling is present)
- statsmodels (for statistical analysis)
- jupyter

If you would like, I can extract the exact imports from the notebook and generate a `requirements.txt` or a conda environment file.

## Reproducing results

- Inspect the top cells of `Digital_Health.ipynb` for dataset paths, seed values, and package imports.
- Ensure any external data referenced by the notebook is available locally or update the paths to point to your data location.
- If the notebook writes outputs to disk, check the cells that save figures or CSVs to identify output folders.

## Final report

Refer to `FINAL RESEARCH REPORT.pdf` for the full written thesis, methodology, results, discussion, and conclusions. The notebook supplements the report by providing the code and figures used in the analysis.

## Contributing

This repository currently contains the final materials for the thesis. If you want changes (for example, to:
- add a requirements file,
- convert the notebook to scripts,
- modularize analysis code, or
- add reproducible data download steps),
open an issue or submit a pull request. If you'd like, I can prepare a branch with:
- a `requirements.txt` or `environment.yml`
- a lightweight script to run key analyses
- or a cleaned README (this file)

## License

No license file is included in the repository. If you want this work to be reusable by others, consider adding an open-source license (for example, MIT, CC-BY, or similar). Let me know which license you prefer and I can add it.

## Contact

Repository owner: [Dipesh1123](https://github.com/Dipesh1123)

---
