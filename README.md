# 🎧 Audio Filtering with IIR Filters

This project demonstrates various **IIR (Infinite Impulse Response) filters** applied to audio signals. The goal is to visualize the effects of different filters (Butterworth, Chebyshev I, and Cauer/Elliptic) on an audio file that has been corrupted by white noise. The filters are used to reduce the noise and improve the **Signal-to-Noise Ratio (SNR)** of the audio.

---

## 🧑‍🔬 Project Overview

The project reads an audio file, adds artificial white noise to simulate real-world imperfections, and applies different low-pass IIR filters to reduce the noise. The effects of these filters are then visualized in both time and frequency domains, and the **Signal-to-Noise Ratio (SNR)** is computed before and after filtering.

### Key Features:
- **Add noise** to an audio signal to simulate corrupted data.
- **Apply IIR filters**: Butterworth, Chebyshev I, and Cauer (Elliptic) filters.
- **Visualize the results** in both time and frequency domains.
- **Compute the SNR** (Signal-to-Noise Ratio) before and after filtering.

---

## 🛠️ Technologies Used

- **Python** 
- **NumPy**: for numerical operations and signal processing.
- **SciPy**: for filter design and signal manipulation.
- **Matplotlib**: for plotting signals and filter responses.
- **Soundfile**: for reading and writing audio files.

