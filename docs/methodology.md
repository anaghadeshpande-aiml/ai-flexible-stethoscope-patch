# Methodology

## Signal Acquisition
Heart and lung sounds are captured using MEMS acoustic sensors embedded in a flexible patch.

## Preprocessing
Noise removal is performed using Butterworth filters and wavelet denoising.

## Feature Extraction
MFCCs and spectrogram-based features are extracted for model input.

## AI Models
- CNN for cardiac murmur detection
- RNN/LSTM for respiratory anomaly classification

## Data Transmission
Processed data is transmitted via Bluetooth or Wi-Fi to a mobile and cloud dashboard.
