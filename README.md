
# EEG Motor Imagery Classification

Learning to classify motor imagery signals from brain-computer interface data.

## What This Is

This project analyzes EEG (brain signal) data from the BCI Competition IV Dataset 2a, where subjects imagined moving their left hand, right hand, feet, or tongue. The goal is to build a classifier that can predict which movement they're imagining based only on their brain signals.

## Current Progress

- ✅ Set up Python environment with MNE-Python
- ✅ Successfully loaded and visualized EEG data
- ✅ Explored raw brain signals from multiple channels
- 🔄 Next: Learn signal processing and feature extraction

## Dataset

Using [BCI Competition IV Dataset 2a](https://www.bbci.de/competition/iv/):
- 9 subjects
- 22 EEG channels + 3 EOG channels
- 4 motor imagery tasks (left hand, right hand, feet, tongue)
- 250 Hz sampling rate

## Tools

- Python 3.10
- MNE-Python (EEG analysis)
- NumPy (numerical computing)
- Matplotlib (visualization)

## Running This Code

```bash
# Create environment
conda create -n bci python=3.10
conda activate bci

# Install dependencies
pip install mne numpy matplotlib jupyter

# Start Jupyter
jupyter notebook

Then open `01_exploring_eeg_data.ipynb`
Goals
Build a complete pipeline for:
	1.	Loading and preprocessing EEG data
	2.	Extracting features (Common Spatial Patterns)
	3.	Training a classifier (SVM, then deep learning)
	4.	Evaluating cross-subject performance
Resources I’m Using
	•	MNE-Python Documentation
	•	BCI Competition IV
	•	Fast.ai Deep Learning Course
