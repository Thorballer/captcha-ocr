# CAPTCHA OCR — offline image dataset

An offline TensorFlow OCR experiment using convolutional layers, bidirectional LSTMs, and CTC sequence decoding.

## Project status

Historical notebooks from Daniel Goldberg’s Kaggle account, organized for a maker portfolio. The model code is preserved, not rewritten during packaging. See [PROVENANCE.json](PROVENANCE.json) for original notebook URLs, timestamps, and SHA-256 hashes.

## Notebooks

- [captcha.ipynb](notebooks/captcha.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/captcha)
- [notebook416e63eea2.ipynb](notebooks/notebook416e63eea2.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/notebook416e63eea2)

## Running

Use the original Kaggle environment where possible: open the source notebook, attach its declared datasets/models, select the hardware expected by its setup cells, and run cells in order. Inspect any install, account-login, upload, or filesystem-changing cells before executing them.

For a local adaptation, install the packages listed in `requirements.txt` in an isolated environment and adjust `/kaggle/input` paths. Those packages are inferred from imports, **not** a tested lockfile. Historical APIs and accelerator assumptions can require changes. Do not run all training notebooks at once.

### Referenced Kaggle datasets

- [fanbyprinciple/captcha-images](https://www.kaggle.com/datasets/fanbyprinciple/captcha-images)
- [sagyamthapa/handwritten-math-symbols](https://www.kaggle.com/datasets/sagyamthapa/handwritten-math-symbols)

## Results and limitations

This archive concerns a static labeled image dataset, not interacting with live verification services. Hardcoded dataset counts and sequence dimensions remain in the original source.

The recovered Kaggle source exports contain no retained executed outputs; this repository therefore does not advertise a numeric result based on notebook titles or training settings. Training was not rerun as part of organization. Structural validation is not a runtime or scientific validation.

## Attribution and rights

Original notebook attribution, comments, and tutorial links are preserved. Standard TensorFlow/Keras examples and tutorial-style code should not be represented as newly invented algorithms. The precise human/AI/tool contribution history is not reconstructed by this archive. No blanket new license is assigned to third-party material. Datasets, pretrained models, and tutorial-derived content retain their own licenses and access requirements; their bytes are not bundled here.
