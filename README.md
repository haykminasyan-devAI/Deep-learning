### Deep Learning Project

This repository contains coursework notebooks and supporting files for deep learning experiments.

#### Contents
- `Deep_Learning_homework_1.ipynb`
- `homework_2.ipynb`
- `requirements.txt`

#### Setup
1) Ensure you have Python 3.11+ installed (macOS recommended steps):
   - Create a virtual environment:
     - `python3 -m venv .venv`
     - `source .venv/bin/activate`
2) Install dependencies:
   - `pip install --upgrade pip`
   - `pip install -r requirements.txt`

#### Usage
- Launch Jupyter Lab and open the notebooks:
  - `jupyter lab`
- Run cells top-to-bottom; adjust paths if you add datasets.

#### Project Structure (suggested as the project grows)
- `notebooks/` for all `.ipynb` notebooks
- `src/` for reusable Python modules (data loading, models, training)
- `data/` for datasets (keep large files out of git)
- `reports/` for figures/outputs

#### Notes
- Add deep learning frameworks (e.g., PyTorch or TensorFlow) to `requirements.txt` if/when needed.
- Pin versions when reproducing results for a report or submission.


