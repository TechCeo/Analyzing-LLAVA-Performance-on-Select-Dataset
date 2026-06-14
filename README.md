# Analyzing LLAVA Performance on LISA Traffic Dataset

This repository contains a focused model evaluation project for LLAVA using the LISA traffic light dataset.

## Repository contents

- `llava_performance_analysis.ipynb` - main notebook for dataset exploration, LLAVA inference, and analysis.
- `llava_rough_work.ipynb` - experimental notebook for rough work, test code, and extra experiments.
- `llavamodeldl.py` - Python helper script used in the LLAVA workflow.
- `README.md` - this project documentation.

## Project overview

The project evaluates LLAVA's capability to identify traffic light state and approximate location in the LISA dataset. It includes:

- dataset loading and structure inspection
- sample image visualization with bounding boxes
- traffic light annotation analysis and distributions
- LLAVA image-to-text inference experiments
- output parsing and evaluation using classification and similarity metrics
- notebook metadata cleanup to ensure GitHub rendering compatibility

## Tools and skills demonstrated

- Python data analysis with `pandas`, `numpy`, and `matplotlib`
- image handling with `opencv-python` and `Pillow`
- Jupyter Notebook workflows for exploratory analysis
- model inference with `transformers` and `huggingface_hub`
- evaluation using `scikit-learn` metrics
- notebook metadata debugging and GitHub-compatible notebook repair

## Reproducing this project

### Prerequisites

- Python 3.11+ or compatible Python 3.x
- `pip` package manager
- Jupyter Notebook or JupyterLab

### Recommended packages

```bash
pip install pandas numpy matplotlib opencv-python pillow scikit-learn transformers huggingface-hub ipywidgets
```

### Running the notebook

1. Clone or download this repository.
2. Open a terminal in the `Analyzing-LLAVA-Performance-on-Select-Dataset` folder.
3. Launch Jupyter:

   ```bash
   jupyter lab
   ```

4. Open `LlavamodelDL.ipynb` as the primary analysis notebook.
5. Update file paths in the notebook if needed to point to your local dataset or model files.

### Notes on paths and environment

- The notebooks include Google Colab-style paths such as `/content/drive/My Drive/...`.
- For local execution, change these paths to reference your own dataset and model locations.
- Avoid committing large model checkpoints or dataset files to the repository.


## Notebook rendering fix

This project includes two notebooks that suffered GitHub rendering issues from invalid widget metadata. The broken metadata entries were removed so the notebooks can display correctly on GitHub.
