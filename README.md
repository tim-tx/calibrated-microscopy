# calibrated-microscopy

Two Python Jupyter notebooks that map cell luminance from microscopy images to MEFL units based on a calibration standard and then compare the results with equivalent FACS measurements. The notebooks do not provide reusable functions at this time. [`uv`](https://github.com/astral-sh/uv) is used for dependency management.

  1. Clone, `cd calibrated-microscopy`
  2. Add expected data into `data/`

Option 1, install an ipython kernel from the venv:

  3. `uv run python -m ipykernel install --user --name=calibrated-microscopy`
  4. `jupyter notebook`, pick calibrated-microscopy kernel

Option 2, just run Jupyter from the venv:

  3. `uv run jupyter notebook`
