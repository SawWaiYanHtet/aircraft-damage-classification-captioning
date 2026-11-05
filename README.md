# Aircraft Damage Classification & Captioning

Classify aircraft surface damage (e.g. dent vs. crack) from images and generate natural-language captions/summaries of the damage.

## Project structure

```
data/
  raw/          # original dataset (not tracked by git)
  processed/    # preprocessed / split data (not tracked)
models/         # saved model weights & checkpoints (not tracked)
notebooks/      # Jupyter notebooks for exploration & experiments
results/        # plots, metrics, sample captions
src/            # reusable Python code (data loading, models, training)
```

## Setup

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt        # top-level deps
# or, for an exact copy of the environment:
pip install -r requirements-lock.txt
```

## Usage

```powershell
jupyter lab
```
