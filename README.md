# MIR Notes by Andrew

A hands-on **Music Information Retrieval (MIR)** study project focused on understanding how computers represent, analyze, and extract information from audio and music signals.

The repository currently contains **10 Jupyter notebooks** that move from symbolic music representations into practical signal-processing and audio-feature analysis. The notes combine explanations, equations, visualizations, and Python experiments using real audio.

**Website:** https://mir-note-by-andrew.vercel.app/

## What This Repository Covers

The current notebooks explore:

- symbolic music representations such as MIDI and MusicXML
- audio signals in the time and frequency domains
- tuning systems and pitch/frequency relationships
- audio feature extraction for Music Information Retrieval
- basic segmentation of audio signals
- signal energy and root-mean-square energy (RMSE)
- zero-crossing rate
- Fourier analysis and frequency-domain representations
- computational experiments with Librosa, NumPy, SciPy, Matplotlib, and scikit-learn

## Notebook Index

| # | Topic | Notebook |
|---|---|---|
| 1 | Basic Musical Representations and MIR | [Note1.ipynb](Note1.ipynb) |
| 2 | Audio Representations | [Note2.ipynb](Note2.ipynb) |
| 3 | Tuning Systems | [Note3.ipynb](Note3.ipynb) |
| 4 | MIDI Note to Frequency | [Note4.ipynb](Note4.ipynb) |
| 5 | Audio Features | [Note5.ipynb](Note5.ipynb) |
| 6 | Basic Feature Extraction | [Note6.ipynb](Note6.ipynb) |
| 7 | Basic Segmentation | [Note7.ipynb](Note7.ipynb) |
| 8 | Energy and RMSE | [Note8.ipynb](Note8.ipynb) |
| 9 | Zero Crossing Rate | [Note9.ipynb](Note9.ipynb) |
| 10 | Fourier Transform | [Note10.ipynb](Note10.ipynb) |

## Technical Focus

This project is being used to build stronger foundations in **signal processing, DSP, and algorithmic audio analysis** rather than treating audio-processing libraries as black boxes.

The experiments focus on understanding how raw waveforms are transformed into useful representations and features, including how time-domain and frequency-domain methods affect downstream MIR analysis.

Topics represented across the repository include:

- waveform analysis
- sampling rate and digital audio representation
- pitch and frequency mapping
- spectral representations
- feature extraction
- segmentation
- energy-based analysis
- zero-crossing behavior
- Fourier-domain analysis

## Technologies

- **Python**
- **Jupyter Notebook**
- **Librosa**
- **NumPy**
- **SciPy**
- **Matplotlib**
- **scikit-learn**
- **IPython**

## Repository Structure

In addition to the notebooks, the repository includes:

- audio samples used in the experiments
- images and diagrams referenced by the notes
- an `index.html` site that organizes the notebooks into a browsable MIR notes website

## Running the Notebooks

Install the main dependencies:

```bash
pip install librosa numpy scipy matplotlib scikit-learn ipython
pip install git+https://github.com/musicinformationretrieval/musicinformationretrieval.com.git
```

Then open the notebooks with Jupyter:

```bash
jupyter notebook
```

## Project Status

This is an ongoing study project. The repository will continue to expand through **Fall 2026** as I work through additional signal-processing, DSP, and Music Information Retrieval concepts and add more computational experiments.

## Reference

The project follows and extends exercises and concepts from [musicinformationretrieval.com](https://musicinformationretrieval.com/), with additional notes and experiments added throughout the notebooks.
