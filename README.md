# CAPTCHA OCR — offline image dataset

An offline TensorFlow OCR experiment using convolutional layers, bidirectional LSTMs, and CTC sequence decoding.

## Notebooks

- [captcha.ipynb](notebooks/captcha.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/captcha)
- [notebook416e63eea2.ipynb](notebooks/notebook416e63eea2.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/notebook416e63eea2)

These notebooks use offline labeled image datasets. Dataset counts and sequence dimensions are hardcoded.

## Running

Open the original Kaggle notebook, attach its referenced data/models, choose the hardware expected by its setup cells, and run cells in order. Review install, login, and file-writing cells first.

For local use, install `requirements.txt` and adapt `/kaggle/input` paths. Dependencies are inferred from imports, not a tested lockfile; older APIs may need adjustment.

### Referenced Kaggle datasets

- [fanbyprinciple/captcha-images](https://www.kaggle.com/datasets/fanbyprinciple/captcha-images)
- [sagyamthapa/handwritten-math-symbols](https://www.kaggle.com/datasets/sagyamthapa/handwritten-math-symbols)

## Status and source

These exports have no saved execution outputs. Training was not rerun, so this archive reports no benchmark scores.

Daniel Goldberg's Kaggle notebooks have source links and hashes in [PROVENANCE.json](PROVENANCE.json). Comments and formatting were cleaned up without changing executable logic or saved outputs; unedited copies are linked in the provenance record.

Credits and tutorial links are retained. Datasets and dependencies have their own licenses; no new blanket license is assigned.
