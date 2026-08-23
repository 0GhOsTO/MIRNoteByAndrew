# [MIR Notes by Andrew](https://mir-note-by-andrew.vercel.app/)

A hands-on study of **Music Information Retrieval (MIR)** at the intersection of **signal processing, machine learning, and music analysis**. The project uses reproducible Python/Jupyter experiments to understand how audio is represented, transformed, and converted into features for downstream audio-processing algorithms.

> **Status:** In progress — expanding the notes and experiments throughout **Fall 2026**.

## Current Focus

- Time-domain and frequency-domain audio representations
- **STFT-based spectrograms** and spectral analysis
- Audio feature extraction and comparison of spectral representations
- Musical tuning systems, pitch, MIDI, and frequency relationships
- Computational experiments with real audio using **Librosa, NumPy, and SciPy**
- Building intuition for how signal representations affect downstream MIR and machine-learning algorithms

## Notes

| # | Topic | Notebook |
|---|---|---|
| 1 | Basic Musical Representations and MIR | [Note1.ipynb](Note1.ipynb) |
| 2 | Audio Representations | [Note2.ipynb](Note2.ipynb) |
| 3 | Tuning Systems | [Note3.ipynb](Note3.ipynb) |
| 4 | MIDI Notes and Frequency | [Note4.ipynb](Note4.ipynb) |
| 5 | Audio Features | [Note5.ipynb](Note5.ipynb) |
| 6 | Basic Feature Extraction | [Note6.ipynb](Note6.ipynb) |

Additional notebooks and experiments are being developed as the project progresses.

## Technical Stack

- **Python**
- **Librosa**
- **NumPy**
- **SciPy**
- **Matplotlib**
- **Jupyter Notebook**

## Learning Goal

The goal is to move beyond using audio-processing libraries as black boxes and build a stronger understanding of the underlying **signal-processing and algorithmic concepts**, including spectral representations, feature extraction, and their effects on computational audio analysis.

These notes are based in part on the curriculum and examples from [musicinformationretrieval.com](https://musicinformationretrieval.com).

## Setup

```bash
pip install librosa numpy scipy matplotlib ipython
pip install git+https://github.com/musicinformationretrieval/musicinformationretrieval.com.git
```

## Website

[MIR Notes by Andrew](https://mir-note-by-andrew.vercel.app/)
