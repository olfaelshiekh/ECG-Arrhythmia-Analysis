# ECG Arrhythmia Analysis - ECG & HRV

Analysis of a 10-second ECG signal to detect R-peaks and calculate Heart Rate Variability (HRV) metrics.

## Dataset
- Sampling Rate: 360 Hz
- Duration: 10.0 seconds
- Signal Length: 3600 samples

## Method
1. Loaded ECG signal
2. Detected R-peaks using `scipy.signal.find_peaks`
3. Calculated RR Intervals
4. Plotted ECG with R-peaks and RR Histogram
5. Calculated HRV metrics: SDNN, RMSSD, pNN50

## Results - Final HRV Report

| Metric | Value |
| --- | --- |
| Heart Rate | 74.4 bpm |
| Mean RR | 806.25 ms |
| SDNN | 71.94 ms |
| RMSSD | 123.34 ms |
| pNN50 | 27.3 % |
| Total Beats | 13 beats in 10 seconds |

## Interpretation
- Heart Rate 74.4 bpm is within normal resting range (60-100 bpm).
- Most RR intervals are concentrated around 800 ms, indicating regular rhythm.
- SDNN of 71.94 ms indicates healthy heart rate variation.

## Files
- `ECG_Analysis.ipynb` - Main analysis notebook
- `requirements.txt` - Required libraries

## Technologies
Python, NumPy, Pandas, Matplotlib, SciPy, WFDB, Jupyter / Google Colab
