ECG Signal Analysis and R-Peak Detection

Student Project – Biomedical Engineering

Project Overview

This project focuses on basic ECG signal processing and R-peak detection using the MIT-BIH Arrhythmia Database.

The main goal of this work is to understand how ECG signals can be processed and analyzed using Python, and to explore how automatic detection methods perform on real ECG recordings.

Project Objectives

- Load ECG recordings from the MIT-BIH Arrhythmia Database.
- Apply filtering techniques to reduce unwanted noise.
- Detect R-peaks using the WFDB XQRS detector.
- Calculate RR intervals and heart rate.
- Explore basic time-domain HRV measurements.
- Compare detected R-peaks with reference annotations.

Tools and Libraries

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- WFDB

Dataset

The project uses the MIT-BIH Arrhythmia Database available through PhysioNet.

How to Run

1. Open "ECG_Signal_Analysis_MIT_BIH.ipynb" using Google Colab or Jupyter Notebook.
2. Run the notebook cells in order.
3. Allow the required Python libraries to be installed.
4. Allow the notebook to access the ECG recordings.
5. Review the plots and analysis results.

Learning Outcomes

Through this project, I gained practical experience with ECG signal processing, filtering, R-peak detection, and basic heart rate variability analysis.

I also learned the importance of comparing automatic detection results with reference annotations and understanding the limitations of signal-processing methods.

Limitations

This is a student learning project. The analysis is limited to the recordings and experiments included in the notebook. Detection results may be affected by noise, signal quality, and detector settings. The HRV measurements are exploratory and should not be considered clinical measurements.

Disclaimer

This project is intended for educational purposes only. It is not a medical device and should not be used for medical diagnosis or treatment decisions.
