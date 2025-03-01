# Vibration Data Analysis for Mechanical Fault Detection

## Project Overview
This project utilizes signal processing and machine learning techniques to analyze vibration data for detecting mechanical faults in rotating machinery. It includes the application of Fast Fourier Transform (FFT) for frequency analysis, feature extraction in both time and frequency domains, and classification using Support Vector Machines (SVM).

## Features
- **FFT Analysis**: Implementation of FFT to transform time-domain vibration signals into the frequency domain, focusing on frequencies up to 60 Hz.
- **Feature Extraction**: Computation of statistical features like standard deviation, RMS, variance, and peak-to-peak values from vibration signals.
- **Machine Learning**: Use of SVM for classifying the mechanical state of the equipment into healthy, unbalanced level 1, and unbalanced level 2.
- **Visualization**: Graphical representation of time-domain signals, frequency-domain spectra, and extracted features.
- **PCA Analysis**: Dimensionality reduction using PCA to visualize the separation between different mechanical states.

## Getting Started

### Prerequisites
- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn
- Seaborn (for enhanced visualizations)

### Installation
Clone this repository and install the required Python libraries:
```bash
git clone https://github.com/your-repository/mechanical-fault-detection.git
cd mechanical-fault-detection
pip install numpy pandas matplotlib scipy scikit-learn seaborn
Usage
Run the main script to process the vibration data, perform FFT, extract features, and classify the data:

bash
Copy code
python vibration_analysis.py
Data
The project uses vibration data collected from rotating machinery under different operational conditions:

Healthy
Unbalanced Level 1
Unbalanced Level 2
Data should be organized in specific directories within the project folder, and the script expects CSV files as input.

Results
The analysis includes:

Time-domain signal plots.
Frequency-domain FFT plots.
Feature comparison plots across different conditions.
SVM classification results including confusion matrices and accuracy scores.
Results are displayed in plots generated by Matplotlib and can be directly viewed during script execution.
