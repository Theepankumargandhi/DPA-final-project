## Overview
This repo contains my final DPA project work. The main file is the Jupyter notebook **`final.ipynb`** where I wrote all the code, experiments, and notes. The goal is to make it easy for anyone to open the notebook, run it, and get the same results I did.

## What’s inside
- **Notebook:** `final.ipynb` (python3)
- **Key sections (from the notebook):**

## Requirements
These are the Python packages the notebook imports (best effort):
```
IPython
graphviz
math
matplotlib
numpy
onnx
onnxruntime
os
pandas
scikit-learn
seaborn
skl2onnx
statsmodels
```

## Setup
```bash
# 1) Create virtual env
python -m venv .venv
source .venv/bin/activate   

# 2) Install Jupyter and dependencies
pip install jupyter IPython graphviz math matplotlib numpy onnx onnxruntime os pandas scikit-learn seaborn skl2onnx statsmodels
```

## How to Run
1. Create and activate a Python 3.11 environment.
2. Install dependencies from `requirements.txt` (generated below) or the list here.
3. Open the notebook:
   ```bash
   jupyter lab final.ipynb
   ```
4. Run cells from top to bottom. If a dataset path is wrong, update the path in the corresponding cell and re-run.

## Results
- Outputs are produced directly in the notebook cells (prints, tables, and plots).
- If the notebook writes files, they will appear in the same folder as the notebook (see list above).

## Reproducibility Notes
- I recommend running the notebook from a clean kernel and executing cells in order.
- If a certain cell fails due to a missing file or package, install/fix that and re-run from that point.
- Randomness: if there are any random operations, set a fixed seed at the top (e.g., `np.random.seed(42)`) to make results repeatable.

## How to Cite or Acknowledge
If you use this code or ideas, please credit this repository and mention it was part of a student final project.

---

*Thanks for checking out my project!* :)
