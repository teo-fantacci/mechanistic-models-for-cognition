# mechanistic-models-for-cognition

A collection of unified firing-rate models that reproduce cognitive functions, written as
pedagogical Jupyter notebooks. This is my personal development contribution to:

> Froudist-Walsh S., Ivanov T. G.\*, Fantacci T.\*, et al. (2026). Mechanistic computational
> models of cognition across scales and species. *Biological Psychiatry*.
> https://doi.org/10.1016/j.biopsych.2026.08.017

The lab's reference repository is
[CANNgroup/mechanistic-models-cognition](https://github.com/CANNgroup/mechanistic-models-cognition).
The notebooks were presented as a tutorial at the Predictive Brain Health Modelling Group (PBHM),
Trinity College Dublin, in June 2026.

## Contents

[`notebooks/fig3_cognition_models/`](notebooks/fig3_cognition_models/) holds five self-contained
notebooks that accompany Figure 3 of the review: multi-item working memory, perceptual decision
making, conscious access, multisensory integration and spatial working memory. Its
[README](notebooks/fig3_cognition_models/README.md) describes each model and how to cite it.

## Running

The notebooks need only NumPy and Matplotlib, and run in Google Colab or locally:

```bash
pip install -r requirements.txt
jupyter notebook
```

No data files are needed; all simulations are generated at runtime.

## License

The code is released under the [MIT License](LICENSE).
