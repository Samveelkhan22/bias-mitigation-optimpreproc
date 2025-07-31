# Optimized Data Pre-processing for Bias Mitigation ⚖️🔍

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![AI Fairness](https://img.shields.io/badge/AI-Fairness-green.svg)
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

This repository demonstrates an optimized data pre-processing algorithm for bias mitigation using the `OptimPreproc` class from the AI Fairness 360 (aif360) toolkit.

## Overview 📊

The notebook covers:
- Implementation of debiasing using `OptimPreproc`
- Dataset partitioning (train/validation/test)
- Learning optimized pre-processing transformations
- Training classifiers and evaluating fairness metrics
- Comparing original vs. transformed dataset performance

## Features ✨

- 🏗️ Configurable parameters for dataset-specific optimization
- 📈 Fairness metrics calculation (statistical parity, disparate impact, etc.)
- ⚖️ Bias mitigation across protected attributes
- 🔄 Comparison between original and transformed data
- 📊 Visualization of results

## Supported Datasets 📂

The notebook demonstrates the approach on:
- Adult Income Dataset
- German Credit Dataset
- COMPAS Recidivism Dataset

## Installation 🛠️

```bash
pip install 'aif360[all]'
```

## Key Metrics 📏
The implementation calculates:
- Balanced accuracy
- Statistical parity difference
- Disparate impact
- Average odds difference
- Equal opportunity difference
- Theil index

## Contributing 🤝
Contributions are welcome! Please open an issue or submit a pull request.

## License 📄
This project is licensed under the MIT License - see the LICENSE file for details.
